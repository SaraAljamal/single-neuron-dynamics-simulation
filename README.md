# single-neuron-dynamics-simulation
This project simulates the dynamics of a single neuron based on the Nagumo model, utilizing Python to analyze action potentials through differential equations. It includes visualizations, parameter tuning using empirical electrophysiological data, and the application of optimization techniques for improved simulation accuracy.

_**Problem Statement**_

Understanding the behavior of single neurons is crucial for advancing our knowledge of neural dynamics and the functioning of the brain. Traditional methods of studying neuronal activity can be challenging and time-consuming. The Nagumo model offers a simplified yet effective mathematical framework for simulating action potentials in neurons. This project aims to utilize Python to simulate the Nagumo model, visualize neuronal dynamics, and optimize model parameters using empirical data. By doing so, it seeks to enhance our understanding of neuronal behavior and provide insights into the factors influencing action potentials, ultimately contributing to the fields of neuroscience and computational biology.

_**Dataset**_

The empirical data for this project provides electrophysiological recordings of neurons, it includes measurements of neuronal output V(t) in response to various input values I(t).

_**Project Workflow**_

1- Data Loading and Exploration:

•	Loaded and explored the dataset, while also selecting a portion of the dataset through masking.

2- Simulation of First-Order Equations:

•	Simulated the two first-order equations representing the Nagumo model, analyzing their behavior and dynamics.

3- Simulation of Second-Order Equation:

•	Combined the first-order equations to simulate a second-order system, examining the input-output relationship.

4- Optimization Algorithms:

•	Implemented various optimization techniques from scratch to tune the parameters of the simulation, including Gradient Descent, Simulated Annealing, and Genetic Algorithm.

5- Exploration of Alternative Models:

•	Investigated the leaky integrate-and-fire model as an additional approach to neuron behavior simulation, comparing its performance with the Nagumo model.

_**Tech Stack**_
- Python: Programming language used for simulation and analysis.
- NumPy: For numerical operations and handling arrays.
- Matplotlib: For data visualization and plotting results.
- Pandas: For data manipulation and analysis.
- Colab Notebook: For interactive coding and experimentation.

_**How to Use**_
1.	Single_Neuron_Simulation.ipynb Notebook:
   
•	The notebook contains all steps of the project
•	To run each notebook, open the it in Google Colab:
-	Click on the notebook file (Single_Neuron_Simulation.ipynb).
-	Choose "Open in Colab" from the GitHub file preview.
-	You can run the cells sequentially to see the steps and results.

2.	Single Neuron Dynamics Simulation Report:
   
•	The report (Single Neuron Dynamics Simulation Report.docx) discusses the theoretical principles, results, and insights from the simulations, including the application of different optimization techniques.

•	You can view or download the report directly from the repository to understand the project background and conclusions.

