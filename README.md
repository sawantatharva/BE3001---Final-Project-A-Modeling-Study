# Investigating Stochastic Influences on Coinfection Dynamics of Respiratory Viruses: A Modeling Study

## Overview
This repository contains code for a university course project titled "Investigating Stochastic Influences on Coinfection Dynamics of Respiratory Viruses: A Modeling Study." The project explores coinfection dynamics using stochastic models and visualizes various aspects of viral growth, peak viral loads, and coinfection durations.

## Code Structure
The code is organized into six main plots, each investigating different aspects of the coinfection dynamics.

### Plot 1
This plot generates a simulated time-series of viral load for two viruses using a continuous-time Markov chain (CTMC) model. The data is then visualized using a line plot with different colors for each virus.

### Plot 2
The second plot explores the distribution of peak viral loads and the time of peak viral load for two viruses under different conditions. It uses histograms to represent the distribution of these parameters.

### Plot 3
This plot analyzes the growth rates of various model parameters using a lowess curve. It visualizes how different parameters evolve over time and how they contribute to the overall model.

### Plot 4
The fourth plot investigates the relationship between the relative viral production rate and the probability of one virus having a higher peak viral load than the other. It uses a line plot to display the relationship.

### Plot 5
This plot compares the peak viral loads, time of peak viral loads, and coinfection duration between an ordinary differential equation (ODE) model and a CTMC model. It uses multiple subplots to visualize these comparisons.

### Plot 6
The final plot displays a curve representing the probability of virus extinction based on the relative viral production rate. It combines a parabolic function with sinusoidal fluctuations and noise to create the curve.

## Usage
To run the code, ensure you have the required dependencies installed, such as NumPy, Matplotlib, Pandas, Seaborn, and Statsmodels. The code is written in Python and can be executed in a Jupyter notebook or any other Python environment.

Feel free to modify parameters, explore different scenarios, or adapt the code for your specific research needs.

## Acknowledgments
This code was created as part of a university course project by Atharva Sawant (U20210020) for the BE3001 course. The project aims to provide insights into the stochastic influences on coinfection dynamics of respiratory viruses through modeling and analysis.

## License
This code is provided under the MIT License. Feel free to use and modify the code for academic and research purposes, giving appropriate credit to the original author.

For any questions or concerns, please contact Atharva Sawant at atharva.sawant@plaksha.edu.in.
