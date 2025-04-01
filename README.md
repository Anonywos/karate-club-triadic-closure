# Triadic Closure Analysis in Zachary's Karate Club Network

## Description

This code was developed as an assignment for the course Tópicos em Inteligência Artificial at Universidade Federal do Piauí.

This project analyzes the effect of triadic closure in the social network of the karate club studied by Wayne Zachary. The original network is loaded using the `networkx` library, and the simulation adds fictitious connections between node pairs that share a common neighbor. The analysis compares the clustering coefficient before and after the modification to assess the impact on network connectivity.

##Professors

Glauber Dias Gonçalves e Raimundo Santos Moura.

## Technologies Used

- Python 3
- Jupyter Notebook
- NetworkX
- Matplotlib
- NumPy

## Features

- Load Zachary's karate club network.
- Compute and visualize the clustering coefficient distribution.
- Apply triadic closure.
- Compare the average clustering coefficient before and after modification.
- Generate graphs for visual analysis of network changes.

## How to Run

1. Install the required dependencies:
   ```bash
   pip install networkx matplotlib numpy
   ```
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Run the code in the notebook to view the results.

## Conclusion

The simulation demonstrated that triadic closure strengthens the network structure, making it more connected and facilitating information propagation. This effect is visible in the increase in the clustering coefficient and the redistribution of values to higher levels.

