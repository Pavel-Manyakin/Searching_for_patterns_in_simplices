# Searching for Patterns in Simplices

Research project focused on studying patterns in simplicial complexes, graph structures, and probabilistic models using mathematical analysis and computational experiments.

## Project Overview

This research investigates how structural patterns emerge in simplicial complexes of different dimensions and how the number of subcomplexes changes depending on the number of vertices and topology.

The project combines:

* Graph theory
* Topology
* Probability theory
* Computational mathematics
* Experimental analysis

The main goal was to identify how the dimension and structure of simplicial complexes influence the number of smaller subcomplexes contained within them .

## Research Motivation

Studying simplicial structures is important in:

* Data Science
* Network analysis
* Topological data analysis (TDA)
* Graph theory
* Machine learning
* Complex systems modelling

Understanding structural patterns allows better analysis of complex networks and high-dimensional data .

## Mathematical Background

### Simplices

A simplex is the simplest geometric object in a given dimension:

| Dimension | Object       |
| --------- | ------------ |
| 0D        | Point        |
| 1D        | Line segment |
| 2D        | Triangle     |
| 3D        | Tetrahedron  |

Higher dimensional simplices generalize this concept to arbitrary dimensions .

### Simplicial Complexes

A simplicial complex is a collection of simplices satisfying closure properties:

* Every face of a simplex belongs to the complex
* Intersections of simplices are also simplices

These structures are widely used in topology and data science .

### Graph Theory Concepts Used

The project also explores:

* Graph isomorphism
* Graph homeomorphism
* Whitney theorem
* Random graph models
* Barycentric subdivision

These concepts help analyze structural similarity between complexes .

## Methodology

The research consisted of several stages:

### 1 Theoretical research

Study of:

* Simplices
* Simplicial complexes
* Graph theory structures
* Random graph models

### 2 Computational experiments

The main experiment:

* Generate random simplicial complexes
* Select small complexes
* Count occurrences inside larger complexes
* Repeat experiment 1000 times
* Compute mean and standard deviation

The baseline experiment used:

* 10 vertices
* 1000 simulations .

### 3 Statistical analysis

Metrics used:

* Mean number of subcomplexes
* Standard deviation
* Growth patterns
* Dimensional analysis

## Key Results

### 1-dimensional simplices

Results show linear growth:

| Size | Mean | Std |
| ---- | ---- | --- |
| 2    | 1    | 0   |
| 3    | 3    | 0   |
| 4    | 6    | 0   |
| 10   | 45   | 0   |

This shows deterministic growth in subcomplex count .

### Higher dimensional simplices

Key findings:

With increasing dimension:

* Number of subcomplexes increases
* Variability changes
* More structural combinations appear

This confirms structural complexity growth in higher dimensions .

### Cyclic vs Acyclic complexes

Observed differences:

Cyclic complexes:

* Higher number of subcomplexes
* Larger variability

Acyclic complexes:

* More stable structure
* Lower variability

This indicates topology affects structural behaviour .

## Key Findings

Main conclusions:

* Dimension strongly affects structural complexity
* Higher dimensions produce more combinations
* Cyclic complexes contain more patterns
* Standard deviation reflects structural stability

This demonstrates predictable structural growth patterns in simplicial complexes .

## Technologies Used

Python

Libraries (example):

* numpy
* networkx
* matplotlib
* scipy

## Project Structure

```
project/
│
├── notebook.ipynb
├── report.pdf
├── README.md
└── requirements.txt
```

## How to Run

Clone repository:

```
git clone https://github.com/yourusername/simplicial-patterns
```

Install dependencies:

```
pip install -r requirements.txt
```

Run notebook:

```
jupyter notebook
```

## Possible Improvements

Future research directions:

* Persistent homology
* Topological data analysis
* Higher dimensional simulations
* ML on simplicial structures
* Network topology analysis
