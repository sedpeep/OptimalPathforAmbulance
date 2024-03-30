```markdown
# Pathfinding in Lahore's Map

This project involves simulating a map of Lahore and applying pathfinding algorithms to determine the optimal paths between various points to 1122 for ambulance on the map.

## Installation

Before running the scripts, you need to install the necessary Python modules. Execute the following commands in your Python environment:

```bash
pip install osmnx geopandas matplotlib pandas
```

## Usage

To use the code, follow these steps:

1. Import the required libraries:

```python
import osmnx as ox
import geopandas as gpd
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
import random
import time
```

2. Simulate Lahore's map using OSMnx by defining the coordinates for the bounding box and retrieving the network within this bounding box.

3. Customize the map visualization by defining colors based on road types.

4. Create a grid representing the area and populate it with road information.

5. Introduce random obstacles and simulate dynamic traffic patterns and road closures to mimic real-world conditions.

6. Define rescue stations and emergency points.

7. Implement the A* Search Algorithm and the Genetic Algorithm (GA) for pathfinding.

8. Compare both algorithms by visualizing the paths and displaying the results in a DataFrame.

## Visualization

The project includes functionality to visualize the grid, the path generated by A* Search, and the path generated by the Genetic Algorithm. To view the paths, use the `plot_path` function provided in the script.

## Comparison

After running both pathfinding algorithms, compare their results using the pandas DataFrame to analyze the path lengths, costs, and computation times.
```
