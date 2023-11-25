# Supply-Chain-Disruption

Introduction
This Python script simulates a network model and assesses the impact of hazardous events on the network's functionality. The simulation includes the following main steps:

Network Generation: The script generates a network using a specified set of parameters such as seed, level sizes, colors, allowed out-degrees, and maximum production by product allowed.
Visualization: It visualizes the generated network using the NetworkX library and plots the graph.
Event Simulation: The script simulates a hazardous event affecting specific nodes in the network. It assigns damage states and downtime to affected nodes based on hazard intensity.
Recovery and Production Loss: It calculates the recovery time and production loss for the affected nodes, considering a specific set of downtime and damage state values.

Usage
To run the script:
Ensure you have Python installed on your machine.
Install required libraries using the following command:
Copy and paste the script into a Python file (e.g., network_simulation.py).
Run the script using a Python interpreter.

Outputs
The script outputs various metrics, including:

Graph visualization of the network.
Visualization of the affected nodes and their recovery.
Production loss metrics, including total loss, percentage loss, and average window time.
Important Notes
This script uses NetworkX for graph representation and visualization.

Contact
For questions or issues, please contact Reyhaneh Mohammadi at mohammadi.reyhane@gmail.com
