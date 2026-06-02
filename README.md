# Pathfinder Visualizer

A web-based pathfinding visualizer built with **React**, **JavaScript**, **HTML**, and **CSS** that demonstrates how **Dijkstra's Algorithm** finds the shortest path between two nodes in a grid.

## 🚀 Features

* Interactive grid visualization
* Start and finish node selection
* Wall/obstacle creation
* Dijkstra's shortest path algorithm implementation
* Animated node exploration
* Shortest path highlighting
* Responsive and user-friendly interface

## 🖼️ Demo

The application visualizes how Dijkstra's Algorithm explores nodes and determines the shortest path from the start node to the destination node while avoiding obstacles.

## 🛠️ Technologies Used

* React
* JavaScript (ES6+)
* HTML5
* CSS3
* Vite

## 📂 Project Structure

```text
src/
├── algorithms/
│   └── dijkstra.js
├── PathfindingVisualizer/
│   ├── Node/
│   │   ├── Node.jsx
│   │   └── Node.css
│   ├── PathfindingVisualizer.jsx
│   └── PathfindingVisualizer.css
├── App.jsx
├── main.jsx
└── index.css
```

## 🧠 Dijkstra's Algorithm

Dijkstra's Algorithm is a graph traversal algorithm used to find the shortest path between nodes in a weighted graph.

### Steps

1. Start at the source node.
2. Mark all nodes as unvisited.
3. Assign a tentative distance value:

   * Source node = 0
   * All other nodes = Infinity
4. Visit the unvisited node with the smallest distance.
5. Update distances of its neighboring nodes.
6. Repeat until the destination node is reached.
7. Reconstruct and display the shortest path.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/pathfinder-visualizer.git
```

Navigate to the project directory:

```bash
cd pathfinder-visualizer
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:5173
```

## 🎮 Usage

1. Launch the application.
2. Create walls by clicking or dragging on the grid.
3. Select the start and finish nodes.
4. Click the **Visualize Dijkstra** button.
5. Watch the algorithm explore the grid and find the shortest path.

## 📈 Future Improvements

* A* Search Algorithm
* Breadth First Search (BFS)
* Depth First Search (DFS)
* Weighted nodes
* Maze generation
* Speed controls
* Mobile optimization

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

Developed as a learning project to understand pathfinding algorithms, graph traversal, React component architecture, and algorithm visualization.

