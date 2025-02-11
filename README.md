# Projet : ANTSEON

The goal of this project is to optimize delivery routes using the Ant Colony Optimization (ACO) algorithm. Over time, the system calculates the best routes by applying a reward-based mechanism, which helps in determining the most efficient paths.

## Key Features:
- Ant Colony Algorithm: Used to find optimal routes considering various constraints.
- Interactive Interface: Built with Tkinter, this interface allows workers to input parameters, modify constraints, and control the system easily.
- Constraints: Several constraints like delivery time windows, vehicle capacities, and others are considered to make the solution more realistic. All constraints were taken into account in this project.

## How It Works:
1.	Ant Colony Algorithm: Simulates the behavior of ants to find optimal routes, adjusting based on rewards.
2.	User Interface: Allows users to input parameters such as the number of routes, points, and more. The interface also provides control over the optimization process.

The system aims to improve the efficiency of deliveries by minimizing the number of trucks and the overall travel time/distance.

Install the required dependencies by running:
```bash
pip install -r requirements.txt
```

To launch the interface, simply run the following command:
```bash
python interface.py
```


















