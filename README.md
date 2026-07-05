
# 🗺️ A* Path Planning Algorithm Visualization

A Python implementation of the **A* (A-Star) Path Planning Algorithm** for finding the shortest path between a start and a goal position in a 2D grid environment with obstacles. The project includes a visualization of the computed path using **Matplotlib**, making it ideal for learning and demonstrating autonomous navigation concepts.

---

## 📌 Overview

Path planning is one of the fundamental components of robotics, autonomous vehicles, and intelligent navigation systems. This project demonstrates how the **A* Search Algorithm** efficiently computes an optimal path by combining the actual path cost with a heuristic estimate of the remaining distance.

The algorithm searches through a grid-based environment while avoiding obstacles and produces the shortest traversable path.

---

## ✨ Features

- 🚀 A* shortest path search
- 📍 Grid-based environment
- 🚧 Obstacle avoidance
- 📊 Path visualization using Matplotlib
- ⚡ Manhattan Distance heuristic
- 🧩 Easy to modify for custom maps
- 🎓 Educational implementation for robotics and AI

---

## 🛠 Technologies Used

- Python 3.x
- NumPy
- Matplotlib
- Heapq (Priority Queue)

---

## 📂 Project Structure

```text
A-Star-Path-Planning/
│
├── astar.py
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Kaushal1525/A-Star-Path-Planning.git
```

### 2. Navigate to the project directory

```bash
cd A-Star-Path-Planning
```

### 3. Install the required packages

```bash
pip install numpy matplotlib
```

or

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python astar.py
```

A visualization window will appear showing:

- Grid map
- Obstacles
- Start node (Green)
- Goal node (Blue)
- Optimal path (Red)

---

## 🧠 Algorithm Workflow

1. Initialize the open set with the start node.
2. Calculate the heuristic using Manhattan Distance.
3. Explore neighboring cells.
4. Skip blocked cells (obstacles).
5. Update path costs whenever a shorter route is found.
6. Continue until the goal is reached.
7. Reconstruct and visualize the shortest path.

---

## 📊 Grid Representation

```text
0 → Free Cell
1 → Obstacle
```

Example Grid:

```text
S X . . .
. X . X .
. . . X .
. X X X .
. . . . G
```

Where:

- **S** = Start
- **G** = Goal
- **X** = Obstacle
- **.** = Free Space

---

## 📸 Output

The generated visualization includes:

- 🟢 Start Position
- 🔵 Goal Position
- 🔴 Computed Shortest Path
- ⚪ Free Cells
- ⚫ Obstacles

---

## 📈 Future Improvements

- Diagonal movement support
- Weighted terrain costs
- Dynamic obstacle avoidance
- Interactive grid editor
- Animated pathfinding visualization
- ROS integration
- Gazebo simulation
- Multi-goal path planning
- D* Lite and Hybrid A* implementation
- Autonomous mobile robot integration

---

## 🎯 Applications

- Autonomous Mobile Robots
- Autonomous Vehicles
- Robot Navigation
- Warehouse Automation
- Game AI
- Drone Navigation
- Indoor Mapping
- Smart Logistics
- Autonomous Delivery Robots
- Research in Artificial Intelligence

---

## 📚 Understanding A*

The A* algorithm evaluates each node using:

```text
f(n) = g(n) + h(n)
```

Where:

- **g(n)** = Cost from the start node to the current node.
- **h(n)** = Estimated cost from the current node to the goal (heuristic).
- **f(n)** = Total estimated cost used to prioritize exploration.

This combination allows A* to efficiently find an optimal path while minimizing unnecessary exploration.

---

## 📋 Requirements

- Python 3.8+
- NumPy
- Matplotlib

---

## 👨‍💻 Author

**Kaushal Reddy**

AI & Autonomous Systems Engineer

GitHub: https://github.com/Kaushal1525

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is licensed under the MIT License.

Feel free to use, modify, and distribute this project for educational and research purposes.
````
