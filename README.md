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

2. **Select** a scheduling algorithm from the dropdown

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

```
cpu-scheduler-simulator/
│
└── index.html        # Main application (HTML + CSS + JS combined)
```

---

## ▶️ Getting Started

### Option 1 — Run Locally
```bash
# Clone the repository
git clone https://github.com/your-username/cpu-scheduler-simulator.git

# Navigate into the folder
cd cpu-scheduler-simulator

# Open in browser
open index.html
```

### Option 2 — Direct Download
1. Download or clone this repository
2. Open `index.html` in any modern browser
3. Start simulating!

> ✅ No installation, no dependencies, no server required.

---

## 📸 Screenshots

> *Add screenshots of your simulator here*

| Input Panel | Gantt Chart | Metrics |
|-------------|-------------|---------|
| *(screenshot)* | *(screenshot)* | *(screenshot)* |

---

## 🔮 Future Improvements

- [ ] Preemptive versions of SJF and Priority Scheduling
- [ ] Save and load process data (JSON export/import)
- [ ] Mobile responsiveness improvements
- [ ] Step-by-step animation mode
- [ ] Backend integration for persistent data storage
- [ ] Comparison view across multiple algorithms

---

## 👨‍💻 Author

**Mohd Sahil**  
B.Tech CSE Student

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📜 License

This project is intended for **educational purposes**.  
Feel free to use, modify, and distribute it for learning and academic use.

---

<p align="center">Made with ❤️ by Mohd Sahil</p>
