# 🚀 Intelligent CPU Scheduler Simulator

> A modern, web-based simulator that visualizes CPU scheduling algorithms with an interactive UI, dynamic Gantt chart, and real-time performance metrics.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📌 Overview

The **Intelligent CPU Scheduler Simulator** is an educational tool designed to demonstrate how different CPU scheduling algorithms operate in real operating systems. Users can define process details, choose a scheduling algorithm, and instantly observe how execution order and timing affect system performance — all visualized in the browser.

---

## ✨ Features

- 🎯 **Multiple Scheduling Algorithms**
  - FCFS (First Come First Serve)
  - SJF (Shortest Job First)
  - Priority Scheduling
  - Round Robin (with configurable Time Quantum)

- 📊 **Real-Time Performance Metrics**
  - CPU Utilization
  - Average Waiting Time
  - Average Turnaround Time
  - Average Response Time
  - Throughput

- 📈 **Dynamic Gantt Chart** — live visualization of process execution order
- 🧠 **Interactive Process Management** — add, delete, or clear processes with instant feedback
- 🎨 **Modern Cyber-Style UI** with smooth animations

---

## 📸 Screenshots

### 🔵 FCFS — First Come First Serve
![FCFS Simulation](screenshot_fcfs.png)

---

### 🟢 SJF — Shortest Job First
![SJF Simulation](screenshot_sjf.png)

---

### 🟣 Round Robin (Q=2)
![Round Robin Simulation](screenshot_rr.png)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Application structure |
| CSS3 | Styling and UI design |
| JavaScript (Vanilla) | Algorithm logic and simulation |

---

## ⚙️ How It Works

1. **Enter process details:**
   - Arrival Time
   - Burst Time
   - Priority *(required for Priority Scheduling)*

2. **Select** a scheduling algorithm from the panel

3. **Click** `Execute Simulation`

4. **View results:**
   - 📊 Gantt Chart visualization
   - 📋 Process execution table
   - 📈 Performance metrics summary

---

## 🧠 Algorithms Implemented

### 1. FCFS — First Come First Serve
Processes are executed strictly in the order they arrive. Simple and non-preemptive.

### 2. SJF — Shortest Job First
The process with the smallest burst time is selected next. Minimizes average waiting time.

### 3. Priority Scheduling
Processes are ordered by priority level. Lower priority number = higher priority (configurable).

### 4. Round Robin
Each process is given a fixed CPU time slice (quantum). Processes cycle through the queue until complete. Best for time-sharing systems.

---

## 📂 Project Structure
