# A model of beta-cell mass, insulin, and glucose kinetics: pathways to diabetes

This project explores the dynamics of glucose and insulin in the body using mathematical modeling. It focuses on understanding the interplay between glucose, insulin, and β-cell mass, and how changes in these factors can lead to hyperglycemia.

## Features

- Nullcline analysis: The project includes code to plot glucose and insulin nullclines for different β-cell mass values. This helps visualize the equilibrium points and the behavior of the system.

- Phase plane analysis: The code generates a phase plane plot using quiver plots to illustrate the direction and magnitude of change in glucose and insulin levels over time.

- Replication and death rates: The project examines the replication and death rates of glucose as functions of glucose and insulin levels. It identifies different zones of behavior based on these rates.

- 3D phase portrait: A 3D phase portrait is generated using Plotly to visualize the dynamics of glucose, insulin, and β-cell mass in a three-dimensional space.

- Bifurcation analysis: The project explores the relationship between glucose levels and the replication rate coefficient (r1). It identifies saddle node and transcritical bifurcations in the system.

- Dynamical hyperglycemia model: The code includes an approximation of the dynamical hyperglycemia model, which relates β-cell mass to insulin sensitivity. It illustrates the different zones of behavior based on insulin sensitivity.

## Dependencies

The project requires the following dependencies:

- NumPy
- Matplotlib
- Plotly

Make sure to install these dependencies before running the code.

## Usage

To run the code, simply execute the Python script. The code is divided into sections, each focusing on a specific aspect of the analysis. You can modify the parameters and explore different scenarios by adjusting the values in the code.

The generated plots will be displayed using Matplotlib and Plotly. You can interact with the 3D phase portrait plot to rotate and zoom in/out for better visualization.

## Acknowledgements

This project is based on the research and findings presented in this [paper](https://pubmed.ncbi.nlm.nih.gov/11013117/). The code and analysis are inspired by the concepts and equations discussed in the paper.

