# AutoPath: Intelligent Navigation

## 🚗 Project Overview

AutoPath is a simulation-based path planning project that demonstrates how a self-driving vehicle can navigate from a start point to a destination while avoiding obstacles using **Ant Colony Optimization (ACO)**.

The system dynamically recalculates the shortest path whenever new obstacles are introduced, making it suitable for autonomous navigation and intelligent routing applications.

---

## 🎯 Objective

- Simulate autonomous vehicle movement in a grid environment  
- Find optimal path using Ant Colony Optimization  
- Handle dynamic obstacles in real time  
- Demonstrate nature-inspired computing in path planning  

---

## 🧠 Algorithm Used

## Ant Colony Optimization (ACO)

ACO is a nature-inspired optimization algorithm based on the behavior of ants searching for food.

Ants leave pheromone trails, and over time the shortest route receives stronger pheromone concentration. This principle is used to find optimal navigation paths.

---

## ⚙️ Features

- Grid-based environment simulation  
- Start point and destination point  
- Random static obstacles  
- Moving vehicle visualization  
- Dynamic obstacle insertion using mouse click  
- Automatic route recalculation  
- "No Path Found" detection  

---

## 🛠️ Technologies Used

- Python  
- Pygame  
- NumPy  

---

## 📂 Project Structure

```text
AutoPath/
│── main.py
│── aco.py
│── grid.py
│── config.py
│── README.md
