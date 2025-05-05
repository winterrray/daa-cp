# daa-cp

# Bipartite Matching & Maximum Flow Visualizer

A responsive React web application that visualizes bipartite matching and maximum flow algorithms. This interactive tool helps users understand how these important graph algorithms work through visual representation and step-by-step execution.

![Bipartite Matching Visualizer](https://placeholder.svg?height=400&width=800&query=Bipartite+Matching+and+Maximum+Flow+Visualizer+Screenshot)

## Features

### 📊 Input Panel
- Configure the number of workers and tasks
- Add edges between workers and tasks (e.g., Worker 1 → Task 3)
- Run either Hopcroft-Karp or Edmonds-Karp algorithms with a single click

### 🧠 Algorithm Execution Panel
- Display detailed steps of algorithm execution
- Show matched pairs for Hopcroft-Karp algorithm
- Display max flow value and matched edges for Edmonds-Karp algorithm
- Syntax-highlighted results for better readability

### 🖼️ Graph Visualization
- Interactive bipartite graph visualization
- Workers displayed on the left side, tasks on the right
- Matched edges highlighted in green
- Powered by vis-network.js for smooth interaction

### 🎨 Modern UI/UX
- Fully responsive layout using Tailwind CSS
- Soft-rounded cards and clear typography
- Tab-based interface for easy navigation
- Toast notifications for user feedback

## Installation

### Prerequisites
- Node.js 16.x or higher
- npm or yarn

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bipartite-flow-visualizer.git
   cd bipartite-flow-visualizer
