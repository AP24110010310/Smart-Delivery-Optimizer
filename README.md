# 🚚 Smart Delivery Optimizer 

## 📌 Project Overview
Smart Delivery Optimizer is a C-based application that simulates a real-world delivery management system. It demonstrates how fundamental algorithms can be applied to optimize logistics operations such as order prioritization, delivery scheduling, package selection, and route optimization.

The project integrates multiple algorithmic techniques including sorting, greedy methods, dynamic programming, and graph algorithms to improve efficiency in delivery systems.

---

## 🎯 Objectives
- Apply core algorithm concepts in a real-world scenario  
- Optimize delivery processes using efficient techniques  
- Demonstrate practical implementation of data structures and algorithms  
- Build a structured and modular C-based application  

---

## 🧠 Algorithms Used

### 🔄 Sorting (Bubble Sort)
Orders are sorted based on priority so that urgent deliveries are handled first.

### ⚡ Greedy Algorithm
Selects deliveries with the shortest delivery time first to minimize total delivery time.

### 📦 Dynamic Programming (0/1 Knapsack)
Optimizes package selection to maximize value within limited capacity.

### 🗺️ Dijkstra’s Algorithm
Finds the shortest route from warehouse to delivery locations.

---

## ⚙️ System Workflow
1. Orders are assigned priorities and delivery times  
2. Orders are sorted based on priority  
3. Greedy approach selects fastest deliveries  
4. Knapsack optimizes package selection  
5. Dijkstra computes shortest routes  
6. Results are displayed  

---

## 🧩 Key Features
- Menu-driven interface  
- Integration of multiple algorithms  
- Real-world delivery simulation  
- Efficient decision-making  
- Simple and readable code  

---

## 💻 Technologies Used
- C Programming Language  
- Data Structures  
- Algorithms  

---

## ▶️ How to Run

```bash
gcc main.c -o delivery
./delivery
