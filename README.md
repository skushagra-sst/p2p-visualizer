# Peer-to-Peer Network Simulator

A web-based Peer-to-Peer (P2P) Network Diagram Editor and Visualizer built with D3.js. This interactive tool lets you add and delete nodes (devices), create and remove connections (edges), switch themes, generate random connected graphs, and visualize graph algorithms like BFS, DFS, and Single Point of Failure (Bridge) detection.

## Demo Video

[Loom URL](https://www.loom.com/share/bae6f4b51eb14163a46a86298e0a9dca?sid=859a09d8-b0f4-4342-bdab-b1521ac69da6)

## Features

- Add and delete devices (nodes) via toolbar
- Connect and remove connections (edges) between devices
- Dark and light theme support
- Generate a random connected graph with 10 nodes
- Visualize graph traversal algorithms:
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - Single Point of Failure (Bridge) detection (SPOF)
- Interactive highlighting and animation of nodes and edges
- Responsive, pan-enabled canvas with grid background

## Demo

Open `index.html` in your browser or serve the directory with a local HTTP server:

```bash
# Using Python 3
python3 -m http.server 8080
# Then open http://localhost:8080/index.html
```

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/p2p-network-simulator.git
   cd p2p-network-simulator
   ```

2. **Open or serve**

   ```bash
   # Using Python 3
   python3 -m http.server 8080

   # Then open http://localhost:8080/index.html
   ```

3. **Interact**

   - Use the toolbar buttons at the bottom to add/delete nodes and edges.
   - Switch between BFS, DFS, and SPOF panels using the tabs on the bottom right.
   - Select start and end nodes in the dropdowns and click *Visualize* to animate traversal.

## Controls

| Button            | Description                |
| ----------------- | -------------------------- |
| ➕ Add Computer   | Add a new node             |
| 🔗 Connect Devices| Toggle connection mode     |
| 🗑️ Delete Device | Toggle node deletion mode  |
| ➖ Remove Edge    | Toggle edge removal mode   |
| 🌗 Switch Theme  | Toggle dark/light theme    |
| 🔀 Random Graph  | Generate random connected graph |

## Dependencies

- [D3.js v7](https://d3js.org/) loaded via CDN
- Google Fonts: Inter
- Material Icons

## Project Structure

```text
├── index.html       # Main application
├── README.md        # Project documentation
```

## License

This project is licensed under the MIT License.
