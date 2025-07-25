# fdf

<p align="center">
 <img width="400" height="235" alt="Screenshot from 2025-07-25 17-04-09" src="https://github.com/user-attachments/assets/b34b4129-dd65-4be5-b7a4-dae1bad7b2d3" />
 <img width="400" height="235" alt="Screenshot from 2025-07-25 17-02-07" src="https://github.com/user-attachments/assets/87a1a00f-a16a-4f2f-904e-b257ffbacf79" />
</p>

The ***fdf*** (Fil de Fer) project is a 42 graphics assignment where I created a 3D wireframe renderer using C and the **MiniLibX graphics library**. The core objective was to take a map file containing elevation data and transform it into an interactive 3D visualization, implementing various projections and transformations.

What I had to do:
* Parse and validate map files containing height values in a grid format
* Transform the 2D coordinate and height data into 3D space
* Implement different projection methods:
  * Isometric projection
  * Parallel projection
* Create an interactive visualization with:
  * Zoom controls
  * Rotation on all axes
  * Translation capabilities
* Handle color gradients based on elevation
* Manage proper line drawing between points using Bresenham's algorithm

To achieve this, I had to:
* Implement matrix operations for 3D transformations
* Use **Bresenham's line algorithm** for precise line drawing
* Apply proper scaling and centering for different map sizes
* Handle keyboard inputs for real-time manipulation
* Manage memory efficiently for large maps
* Create a robust error handling system

Bonus Features:
* Added extra transformations and controls:
  * Color gradients based on elevation
  * Multiple projection types
  * Smooth rotation controls
  * Dynamic zoom and movement
  * These features enhanced the visualization capabilities and user experience

What I Learned:
* Fundamentals of 3D graphics programming
* Matrix operations and transformations
* Line drawing algorithms and optimization
* Event-driven programming with graphics
* Efficient memory management for large datasets
* Working with mathematical projections and coordinate systems

FdF was an excellent introduction to 3D graphics programming, teaching me both the mathematical foundations and practical implementation aspects of creating wireframe visualizations.
