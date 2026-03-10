# Implementing my own Machine Learning Algorithms

## Overview

This repository contains didactic machine learning projects developed with a clear objective: to understand how core ML algorithms work by implementing them from scratch.

The focus here is not on production-ready pipelines or heavy use of specialized machine learning frameworks. Instead, the goal is to study the logic, mathematics, and programming structure behind these methods in a direct and practical way.

Another important principle of this repository is to avoid using AI to generate the project code itself. The intention is educational. Writing the code manually helps strengthen intuition, problem-solving skills, and familiarity with the underlying mechanics of each algorithm.

## Purpose

The purpose of this repository is to serve as a study space for implementing machine learning algorithms with minimal abstraction.

This includes:

- building algorithms step by step
- understanding the mathematical ideas behind them
- practicing data manipulation and numerical computation
- comparing custom implementations with standard references when appropriate
- documenting the reasoning behind each project in a clear way

The repository is intended as a learning resource, not as a shortcut to ready-made solutions.

## Project Philosophy

The projects in this repository follow a few simple principles:

- implement the main logic manually whenever possible
- avoid relying on specialized machine learning libraries for the core algorithm
- use external libraries only when they support data handling, numerical operations, plotting, or validation
- keep the code readable and educational
- prioritize understanding over optimization

## Main Technologies

The repository mainly uses:

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- uv

Some projects may also use small portions of other libraries for comparison or validation, but the central algorithmic logic is intended to be implemented from scratch.

## Repository Structure

Each notebook is organized as a self-contained study project. In general, the projects include:

- A short introduction to the problem
- Dataset loading and inspection
- Implementation of the algorithm from scratch
- Intermediate steps and explanations
- Tests, results, or comparisons
- Conclusions about the behavior of the method

## Current Projects

### Binary Classification with a Simple Neural Network
A machine learning notebook focused on implementing a small binary classification model directly in Python, with emphasis on readability, manual logic, and understanding the steps of the method.

### Implementing my own PCA algorithm for Dimensionality Reduction
A PCA project built around a custom implementation of Principal Component Analysis, including data preparation, dimensionality reduction, and comparison with a reference implementation.

## How to Use

This repository uses `uv` for environment and dependency management. The configuration files included in the repository are part of the intended workflow, so anyone cloning the project can recreate the environment in a consistent way.

### 1. Clone the repository

```bash
git clone https://github.com/your-username/implementing_ml_algorithms.git
cd implementing_ml_algorithms
```

### 2. Install uv

If `uv` is not installed on your machine, install it first. You can install it using the official installation method for your operating system.

### 3. Sync the environment and dependencies

With the repository files already in place, run:

```bash
uv sync
```

This will create the virtual environment and install the dependencies defined in the project configuration.

### 4. Activate the virtual environment

On Linux or macOS:

```bash
source .venv/bin/activate
```

On Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

On Windows Command Prompt:

```cmd
.venv\Scripts\activate.bat
```

### 5. Launch Jupyter

After the environment is ready, start Jupyter, VSCode, or something else that you use.

## Environment Management

This repository uses `uv` as the standard tool for managing the Python environment and project dependencies. The included configuration files are meant to make setup straightforward and reproducible for anyone who wants to run the notebooks locally.

If dependencies are updated in the project configuration, run:

```bash
uv sync
```

again to bring the environment in line with the current repository state.

## Intended Audience

This repository is meant for:

- students learning machine learning fundamentals
- anyone who wants to understand how algorithms work internally
- people practicing Python through mathematically grounded projects
- learners who prefer building methods themselves before depending on high-level tools

## Notes

These projects are intentionally didactic. Some implementations may be more explicit than optimized, because the main objective is to make the reasoning visible.

This repository should be read as a learning record and a practical study resource centered on implementing machine learning algorithms from scratch.

---
## **Author and Links**

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://avatars.githubusercontent.com/u/145709364?v=4"
    />
    <p>&nbsp&nbsp&nbspGuilherme (Gui) Freire Oliveira<br>
    &nbsp&nbsp&nbsp
    <a href="https://github.com/guilhermeefoliveira">
    GitHub</a>&nbsp;|&nbsp;
    <a href="https://www.linkedin.com/in/guilhermeefoliveira/">LinkedIn</a>
    </p>
</p>
<br/><br/>
<p>
