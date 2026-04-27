# Mystery_Solver: A Bayesian Network-Based Decision Support System for Probabilistic Crime Analysis

# Overview
The Mystery Solver application is an intelligent decision-support system that uses Bayesian Networks to solve fictional mystery scenarios by calculating the probability of each suspect being guilty based on available evidence. In this project, users enter clues such as alibis, motives, witness statements, fingerprints, or other pieces of evidence, and the system models the relationships between suspects, motives, opportunities, and evidence using probabilistic graphical models. Each clue updates the belief about a suspect’s guilt through Bayesian inference, meaning the system continuously revises probabilities as new information is added. The application demonstrates how uncertainty can be handled mathematically rather than relying on simple rule-based logic, making it more realistic and intelligent. It highlights key concepts such as conditional probability, prior and posterior probabilities, and probabilistic reasoning under uncertainty. Overall, the project combines artificial intelligence and probability theory to create an interactive and educational tool that simulates real-world investigative reasoning in a structured, data-driven way.

# Features
Input (evidences): Users can share any clues or pieces of evidence they think might be connected to the crime, making the process more engaging and participatory.
Bayesian Inference: The system uses Bayesian networks to help figure out how likely it is that each suspect is guilty, based on the clues provided by users.
Interactive UI: The application provides an easy-to-use interface for adding clues, viewing results, and understanding the logic behind the probability calculations.
Mystery Scenarios: The app can be used for various fictional mysteries, making it adaptable to a wide range of situations.

# Project structure
Mystery_Solver/
│
├── main.py                  # Main code file to run the project
├── README.md                # Project documentation (this file)
├── requirements.txt         # List of libraries and dependencies
├── data/                    # Subfolder containing datasets
├── support/__pycache__      # Subfolder containing other code files
│   ├── __init__.py          # Code for Bayesian network logic
│   ├── mystery_solver.py    # Code to handle clue input from the user
│
└── others/                      # Subfolder for project-related documents
    ├── Final presentation.pptx  # Final presentation file
    ├── final report.pdf         # Final project report
    ├── Update Presentation.pptx # Updated presentation file
    ├── update report.pdf        # Updated project report
    └── demo video               # Google drive link of the demo video

# Requirements
This project relies on the following technologies:

**numpy** - For numerical calculations.
**pgmpy** - For creating and manipulating Bayesian networks.
**streamlit** - Web application interface.
**Graphviz** - Visualization of network structures.
**matplotlib** - For visualizing the Bayesian network and results.
**json** - For handling input and output in JSON format.
**Python 3.11** - Version of Python PL.

