# Autonomous Delivery Robot

## Project Overview
This project involves the implementation of an autonomous delivery robot that navigates a city environment to deliver grocery orders. The robot must avoid obstacles, dynamically adapt to changes, and efficiently plan its paths using informed search algorithms such as Best-First Search and A*.

## Features
- **Environment Representation**: A 15x15 grid-based city map with buildings, houses, roads, vehicles, and delivery points.
- **Path Planning Algorithms**: Implementation of Best-First Search and A* for motion planning.
- **Dynamic Environment Handling**: Changes in the environment, such as varying delivery locations and moving vehicles.
- **Path Execution & Control**: The robot follows planned paths while avoiding obstacles.
- **User Interface & Visualization**: A GUI for interacting with the simulation and visualizing the robot's movement in real-time.
- **Performance Evaluation**: Comparison of path optimality, execution time, and adaptability.
- **Bonus Feature**: Multi-robot coordination to optimize deliveries and prevent collisions.

## Implementation Details
### Environment Representation
- The city area is represented as a **15x15 grid**.
- Buildings, houses, vehicles, and delivery points are marked within the grid.
- The robot starts at a fixed location.

### Motion Planning Algorithm
- **Best-First Search and A*** are implemented and compared for efficiency.
- The heuristic function is based on **Euclidean distance**.
- Movement cost is randomly generated between **1 to 20**.

### Dynamic Environment
- The environment updates **after each delivery**, setting the previous goal as the new start location.
- Vehicle positions change dynamically to simulate real-world traffic conditions.

### Path Execution
- The robot follows the calculated path, avoiding obstacles and moving towards the goal.
- **Five delivery locations** are assigned one after another.

### Visualization & GUI
- The simulation is visualized using **Matplotlib, Pygame, Tkinter, or PyQt**.
- The robot's movement, obstacles, and delivery points are displayed in real-time.
- Users can interact with the simulation, assign deliveries, and observe robot behavior.

### Performance Evaluation
- Comparison of **A* and Best-First Search** based on:
  - Path optimality
  - Execution time
  - Adaptability to dynamic changes

### Multi-Robot Coordination (Bonus Task)
- Implementation of multiple autonomous robots navigating the environment.
- Collision prevention and route optimization strategies.

## Installation & Setup
### Prerequisites
Ensure you have the following dependencies installed:
```sh
pip install matplotlib pygame tkinter PyQt5
```

### Running the Simulation
1. Clone the repository:
   ```sh
   git clone https://github.com/muradhameed921/autonomous-delivery-robot.git
   cd autonomous-delivery-robot
   ```
2. Run the simulation script:
   ```sh
   python main.py
   ```
3. Use the GUI to assign deliveries and observe the robot’s movement.
=======
# AI-PROBLEM-1
>>>>>>> cf142ca (Initial commit)
