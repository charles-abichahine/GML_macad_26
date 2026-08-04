# Topologic building graphs

Three studies from the Graph Machine Learning seminar at MaCAD, IAAC, each turning a building into a graph and then asking something of it.

All three are built on [TopologicPy](https://github.com/wassimj/topologicpy): geometry in, topology out, graph analysis on top.

## 01 · Graph generation

A courthouse modelled in Rhino, with its doors and windows carried as separate geometry, rebuilt as a spatial graph.

`Graph-ML-Seminar/01-Graph Generation/` holds the Rhino source, the notebook and the PDF.

## 02 · Graph analysis

The courthouse gallery plan is sliced by a grid into a topologic shell, then read three ways: navigation, through closeness and betweenness centrality and shortest path; visibility, through isovists cast at every cell and assembled into a visibility graph; and structure, through degree centrality and community detection.

`Graph-ML-Seminar/02-Graph Analysis/` holds three notebooks and the PDF.

## 03 · Building graph representation

The Seagram Building classified against the Building-Ground Relationship dataset: a graph neural network sorting buildings by how they meet the ground, across five classes. Separation, separation with plinth, adherence, adherence with plinth, interlock.

The notebooks build the graph, train on the dataset and predict an unseen one. The exercise is whether the model agrees with your own reading of the building.

`Graph-ML-Seminar/03-Building Graph Representation/` holds the dataset, three notebooks, the trained model and the report.

## Stack

TopologicPy · PyTorch Geometric · pandas

## Context

Graph Machine Learning seminar, Master in Advanced Computation for Architecture & Design (MaCAD), IAAC Barcelona, 2025–26.
