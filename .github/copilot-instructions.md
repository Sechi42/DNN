# Copilot Instructions for DNN Deep Neural Networks Learning Project (UdeG)

## Project Purpose & Big Picture
This repository is for the course "Redes Neuronales Profundas" (Deep Neural Networks) at Universidad de Guadalajara, Maestría en Ingeniería y Ciencia de Datos. The main goal is to learn, implement, and experiment with DNNs, pattern recognition, and machine learning fundamentals. All work is educational and focused on clarity, reproducibility, and step-by-step exploration.

## Architecture & Workflow
- **Notebook-Driven**: All code, theory, and experiments are in Jupyter Notebooks (e.g., `DNN_WEEK_1/Auto_Diff.ipynb`). No standalone scripts or modules.
- **Sectional Structure**: Each notebook is organized by topic (see course syllabus below). Use Markdown headers to separate theory, methodology, results, discussion, and conclusions.
- **Theory First**: Start each section with a markdown cell explaining the concept, referencing course objectives and bibliography.
- **Code Next**: Follow with Python code cells for implementation, using clear variable names, proper indentation, and comments.
- **Results & Analysis**: Present outputs (tables, plots, print statements) and discuss findings in markdown cells.
- **Minimal Dependencies**: Use only standard Python and essential packages (NumPy, matplotlib, etc.). Document any new dependency in markdown before use.
- **Self-Contained**: Each notebook should run independently. Include all imports and definitions needed for each section.

## Course Topics (Structure Notebooks Accordingly)
1. Shallow Neural Networks (logistic regression, activation functions, gradient calculation, bias/variance, regularization, sklearn usage)
2. Deep Neural Networks (vectorized direct/inverse problems, backpropagation for regression/classification, dropout)
3. Alternative Optimization Algorithms (BFGS, Levenberg-Marquardt, genetic/differential/memetic algorithms, Python optimization packages)
4. Convolutional Neural Networks (motivation, operations, image processing applications)
5. Radial Basis Function Networks (motivation, universal approximation, function approximation)
6. Recurrent & Recursive Neural Networks (motivation, deep architectures, universal approximation)
7. Reinforcement Learning (motivation, general model, implementation, applications)

## Developer & Homework Conventions
- **Markdown for Theory**: Use clear, structured markdown for explanations. Start each exercise with its statement.
- **Python for Practice**: Use code cells for implementation. Comment code for clarity. Use print statements and plots for visible results.
- **Reproducibility**: Ensure code runs and produces outputs. Test with sample data before finalizing.
- **Reporting**: Structure notebooks for easy export to PDF. Include introduction, methodology, results, discussion, and conclusion sections.
- **Homework Submission**: Deliverables are a PDF report (with code and outputs) and the `.ipynb` file. Do not split files or submit images alone.

## Example Notebook Pattern
```markdown
# 2. Deep Neural Networks: Backpropagation
Explain the concept, reference course bibliography, and outline objectives.
```
```python
import numpy as np
# Implementation of backpropagation for regression
# ... code ...
```
```markdown
## Results & Discussion
Present outputs, analyze results, and discuss implications.
```

## Key File
- `DNN_WEEK_1/Auto_Diff.ipynb`: Main notebook for Week 1 (automatic differentiation).

## Bibliography
- Goodfellow, Bengio, Courville: Deep Learning (MIT Press, 2016)
- Bishop: Pattern Recognition and Machine Learning (Springer, 2006)
- Haykin: Neural Networks and Learning Machines (Pearson, 2009)
- Sutton & Barto: Reinforcement Learning (Bradford Book, 2018)

---
For questions or unclear conventions, ask for clarification or review with the user. Prioritize clarity, reproducibility, and educational value in all contributions.
