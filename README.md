# Mysetry_Solver: A Bayesian Network based decision support system for probabilistic crime analysis

# Overview

Mystery_Solver is an intelligent decision support system that leverages Bayesian Networks to assist investigators and forensic professionals in solving crimes through probabilistic reasoning. By modeling conditional dependencies between variables such as physical evidence, witness testimony, suspect profiles, motives, and opportunity within a directed acyclic graph structure, the system enables real-time belief updating as new evidence is introduced  producing posterior probability distributions that reflect the true state of investigative knowledge at any point in time. Unlike deterministic approaches, Mystery_Solver embraces the inherent uncertainty of criminal investigation, allowing users to integrate heterogeneous evidence sources, perform sensitivity analysis, simulate hypothetical scenarios, and identify which evidence nodes carry the greatest inferential weight all through an interpretable visual interface designed to make probabilistic outputs accessible to non-technical users. Suitable for active case analysis, cold case re-evaluation, multi-suspect triage, and forensic training, the system provides a mathematically rigorous, transparent, and auditable framework that not only ranks suspects by likelihood but explains the reasoning behind each inference.

# Features
```
**Input (clues):** Users can provide various clues or pieces of evidence that may relate to the crime.
**Bayesian Inference:** The system applies Bayesian networks to calculate the likelihood of suspects being guilty based on inputted clues.
**Interactive UI:** The application provides an easy-to-use interface for adding clues, viewing results, and understanding the logic behind the probability calculations.
**Mystery Scenarios:** The app can be used for various fictional mystery scenarios, making it adaptable to a variety of situations.

```
# Project structure

```
Mystery_Solver/
├── main.py                  # Main code file to run the project
├── README.md                # Project documentation (this file)
├── requirements.txt         # List of libraries and dependencies
├── data/                    # Subfolder for containing datasets
├── support/                 # Subfolder containing other code files
│   ├── __init__.py          # Code for Bayesian network logic
│   └── mystery_solver.py    # Code to handle clue input from the user
└── others/                  # Subfolder for project-related documents
    ├── Final presentation.pptx  # Final presentation file
    ├── final report.pdf         # Final project report
    ├── Update Presentation.pptx # Updated presentation file
    ├── update report.pdf        # Updated project report
    └── demo video               # Google drive link of the demo video
```
# Requirements
```
This project relies on the following technologies:

**numpy** - For numerical calculations
**pgmpy** - For creating and manipulating Bayesian networks
**streamlit** - Web application interface
**Graphviz** - Visualization of network structures
**matplotlib** - For visualizing the Bayesian network and results
**json** - For handling input and output in JSON format
Python 3.11
```
