# Recursive-Hexagonal-Grid-Visualizer
It generates a recursive grid of **hexagonal cells**, outputs the data as an **interactive HTML visualization**, and supports dynamic exploration of the hexagonal hierarchy.

## 🛠️ Technologies Used

- **C (Core Logic, Geometry, Recursive Structure)**
- **HTML + CSS (Hexagon Layout)**
- **JavaScript (DOM Interactions)**
  
## 📁 How it Works

1. The C code:
   - Divides each cell into 7 child hexagons
   - Recursively builds the structure to a desired resolution (`requiredRes`)
   - Outputs an interactive HTML file (`hexagon_grid.html`)

2. The HTML file:
   - Renders the grid using CSS `clip-path` to draw hexagons
   - Allows clicking and searching hexagons by path ID
   - Highlights clicked/searched hexagons dynamically

