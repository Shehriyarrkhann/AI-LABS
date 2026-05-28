# 🛡️ AI-Based Cyber Attack Path Simulator

## 📌 Project Overview
The AI-Based Cyber Attack Path Simulator is a cybersecurity-based AI project that models a computer network as a weighted graph. The system simulates how an attacker can traverse the network from a starting node to a target node using different AI search algorithms.

The main objective is to analyze and compare various search strategies based on path cost, efficiency, and execution time.

---

## 🎯 Objectives
- Model a real-world network using graph data structures
- Simulate cyber attack path discovery
- Implement multiple AI search algorithms
- Compare performance of algorithms
- Visualize optimal attack paths

---

## ⚙️ Technologies Used
- Python
- Google Colab
- NetworkX (Graph visualization)
- Matplotlib (Plotting graphs)
- Pandas (Data comparison tables)

---

## 🧠 Algorithms Implemented

### 🔹 Uninformed Search
- Breadth First Search (BFS)
- Depth First Search (DFS)

### 🔹 Informed Search
- Uniform Cost Search (UCS)
- A* Search Algorithm

### 🔹 Local Search
- Hill Climbing Algorithm (demonstrates local maxima limitation)

### 🔹 Adversarial Search
- Minimax Algorithm (Attacker vs Defender model)
- Alpha-Beta Pruning (optimized Minimax)

---

## 🌐 Problem Representation

- **Nodes** represent systems (servers, routers, databases, etc.)
- **Edges** represent connections between systems
- **Weights** represent cost, risk, or difficulty of traversal
- **Start Node** is attacker entry point
- **Goal Node** is target system

---

## 📊 Output Metrics
For each algorithm, the system calculates:

- Path discovered
- Total cost of path
- Number of nodes expanded
- Execution time (in milliseconds)

These results are compared in a final analysis table.

---

## 📈 Visualization
The project includes:
- Network graph visualization using NetworkX
- Highlighted optimal attack path
- Comparative table of all algorithms
- Step-by-step algorithm execution results.


---
## 📥 Installation Requirements
No installation required if using Google Colab.
If running locally:
pip install networkx matplotlib pandas.



## ▶️ How to Run the Project

### 🔹 Using Google Colab
1. Open the `.ipynb` notebook file
2. Install required libraries:

pip install networkx matplotlib pandas

3. Run all cells sequentially
4. View outputs (graphs, tables, and results)

---



## 📁 Project Structure

AI_Cyber_Attack_Simulator/
│
├── notebook.ipynb
├── README.md
├── report.pdf (Overleaf Report)
└── figma_ui.png (UI/UX Design Screenshot)


---

## 🎨 UI/UX Design
A cybersecurity dashboard-style UI was designed using Figma to represent:
- Algorithm selection panel
- Network graph visualization area
- Real-time results panel (path, cost, execution time)

This provides a SOC (Security Operations Center) style interface for better understanding of AI-based attack simulation.

---

## 🔐 Key Features
- Multi-algorithm comparison
- Cybersecurity attack path simulation
- Graph-based network modeling
- Real-time performance analysis
- Adversarial AI modeling (attacker vs defender)

---

## 👨‍💻 Author
Mid-Term AI Project Group. 
Developed for educational purposes in Artificial Intelligence and Cybersecurity simulation.

---

## 📌 Note
This project is implemented in Google Colab and is fully executable without any additional setup except required Python libraries.
