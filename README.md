[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KIMhwtUS)
# Towards Reasoning About Adversarial Protocol Interaction
This repository contains the course project for CSCI 7000: Principles of Program Analysis.
This project focuses on defining adversarial equivalence, a notion of protocol equivalence with respect to an active symbolic adversary.
Adversarial equivalence is defined with respect to an actor-style protocol language called DYAct.
This project also provides a concrete and collecting semantics for DYAct protocols and adversaries.
The intention is to provide a foundation on which to explore abstractions that could ease verification of adversarial equivalence.

## Organization

This repository is organized as follows:

```
.
├── README.md
├── paper
│   ├── Makefile
│   ├── README.md
|   ├── languages
|   ├── sections
│   ├── mydefs.tex
│   ├── llncs.cls
│   ├── splncs04.bst
│   ├── main.bib
│   ├── main.pdf
│   └── main.tex
└── talk
    ├── README.md
    └── symbolic-.pptx
```

## Assignment

### Repository Organization

This project is organized into the following directories:
- [paper](paper/) for the project paper; and
- [talk](talk/) for the project presentation slides.

### Paper Organization

The paper for this project is located in the `paper/` directory.
The main LaTeX file is `main.tex`, while the output paper file is `main.pdf`.
The bibliography is managed in `main.bib`.
The style files `llncs.cls` and `splncs04.bst` are provided to format the paper according to the Lecture Notes in Computer Science (LNCS) guidelines.
The `mydefs.tex` file contains custom LaTeX macros that are used throughout the paper, including macros for generating inference rules.
The `sections/` directory contains the LaTeX files for individual sections of the paper, which are then included in `main.tex`.
The `languages/` directory contains the styles for displaying the programming languages used in the paper.
In particular, this directory includes the styling for the DYAct language.
The `Makefile` is used to compile the LaTeX source files into the final PDF document.

### Talk Organization (`talk/`)
The presentation slides for this project are in the `symbolic-equivalence-project-presentation.pptx` file.
