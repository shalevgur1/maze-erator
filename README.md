# Maze Generator Script

This script generates a customizable maze layout using a grid-based approach.
The maze is initialized with a starting and ending point, which are marked
distinctly, and then a random path is created to connect them. Walls and paths
are defined using a combination of integers and enums to distinguish different
tile types.

### Key Features:
- Randomized Path Creation: A trail from the starting point to the ending
  point is created by selecting adjacent tiles, ensuring there is at least one
  valid path.
- Tile Types: The maze includes several tile types:
  - Wall tiles: Represent impassable areas.
  - Path tiles: Represent walkable areas.
- Visualization: The maze is visualized using matplotlib, with each tile type
  represented by a specific color (e.g., green for paths, black for walls,
  and blue for start/end points).

## Usage:
1. Run this script to generate a maze with a single solution.
2. Adjust parameters within the script for different maze sizes and layouts.
3. Use the visualization function to render the maze in a readable format,
   with each tile color-coded for easy understanding.

### Dependencies:
- numpy: For matrix operations and grid representation.
- matplotlib: For visualizing the generated maze layout.

### To Run:
1. Configure your desired maze inside the maze_generator.py file in the configuration section.
2. Run the command:
   ```
   python maze_generator.py
   ``` 
