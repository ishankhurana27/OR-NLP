OR-NLP Offline Optimization System (LLM + Classical OR Hybrid Engine)
🚀 Overview

This project is an offline NLP + LLM–powered optimization system designed to solve classical Operations Research (OR) problems such as Linear Programming (LP), Traveling Salesman Problem (TSP), Game Theory, and Multi-Criteria Decision Making (MCDM).
It combines lightweight LLMs (Phi-3) with custom optimizers to deliver fast, accurate, and fully offline problem-solving capabilities.

The system includes QLoRA fine-tuning on domain-specific eBooks and OR literature, enabling the model to understand mathematical structures, constraints, payoffs, and optimization heuristics.

🔍 Key Features
1. Offline NLP + LLM Engine (Phi-3)

Runs fully offline—no cloud dependency

Understands OR problem statements in natural language

Converts text into mathematical structures (constraints, objective functions, matrices)

2. Solves Multiple OR Problem Types

Linear Programming (LP)

Traveling Salesman Problem (TSP)

Game Theory (Nash, dominance, payoff matrices)

MCDM (AHP, TOPSIS, weighted scoring)

3. QLoRA Fine-Tuning on OR Domain Data

Trained on OR eBooks, academic PDFs, and domain notes

Enhances reasoning over mathematical constraints

Boosts problem understanding and step-by-step accuracy

4. Hybrid ML + OR Algorithm Pipeline

LLM interprets and structures the problem

Custom OR solvers compute the optimal result

LLM explains the final answer with reasoning

Achieved 25–30% accuracy boost compared to baseline offline LLMs

5. Instant Solution Generation

Optimized pipeline reduces computation time drastically:

LP and MCDM results generated instantly

TSP and Game Theory solved using heuristic + LLM-guided pruning

Offline system suitable for low-resource environments

🧠 Why This Project Matters

Traditional OR solvers require structured input. This system:

Accepts pure natural language

Converts it into solvable mathematical form

Uses fine-tuned LLMs for domain-aware reasoning

Delivers fast, offline optimization without GPUs or cloud

It demonstrates how LLMs can augment classical algorithms to create a new category of autonomous OR assistants.

🛠️ Tech Stack

Phi-3 LLM

QLoRA fine-tuning

PyTorch / Transformers

Classical OR libraries (PuLP / OR-Tools / custom solvers)

Python (main engine)

PDF/eBook preprocessors

📁 Project Structure

/models/ — QLoRA fine-tuned Phi-3 weights

/data/ — OR textbook datasets, domain corpora

/solvers/ — LP, TSP, Game Theory, MCDM algorithms

/nlp/ — parsing & mathematical structuring

/inference/ — offline generation engine

/examples/ — sample OR problems with outputs
