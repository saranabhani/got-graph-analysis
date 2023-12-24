# Game of Thrones Graph Analysis
## Overview
This repository hosts a Jupyter Notebook for a university course assignment, focusing on graph analysis with nxneo4j on the "Game of Thrones" dataset. Originally developed by Andrew Beveridge, this dataset represents interactions between characters across all five books of the series.

## Dataset
The dataset labels characters as Character and categorizes relationships as INTERACTS1, INTERACTS2, INTERACTS3, and INTERACTS45, each signifying interactions between characters across the series' books.

## Analyses Performed in the Notebook
* PageRank Algorithm: To identify the most influential characters.
* Betweenness Centrality: To find characters that act as connectors within the character network.
* Degree Centrality: Analysis of INTERACTS2 relationships to pinpoint characters with the most interactions.
* Visualizations: Graphical representations of relationships among characters.

## Tools and Libraries Used
* nxneo4j: Combines NetworkX and Neo4j for graph analytics.
* Neo4j: For managing the dataset.
* Cypher: For data querying and manipulation.
* Matplotlib: For visualizing graphs.
