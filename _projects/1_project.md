---
layout: page
title: Geometry
description: A Geogebra clone with an original mathematics engine
img: assets/img/Torus.png
importance: 1
category: work
related_publications: false
---

[GeoGebra](https://www.geogebra.org/3d?lang=es) is a widely used, free software application that combines geometry, algebra, calculus, and other branches of mathematics into a single, interactive platform. It is particularly popular in educational settings for teaching and learning mathematics, as well as for exploring mathematical concepts visually and dynamically. 

The Geometry project is a Python-based graphical application built using **Pygame** and **Numpy**. Its goal is to create a 3D interactive geometric exploration tool inspired by GeoGebra. The tool features an original mathematics engine to handle advanced geometric transformations, projections, and object manipulations.

#### **Main Features**
1. **Interactive Visualization**:
   - A user-friendly Pygame interface with a resizable canvas for geometric visualization.
   - An interactive coordinate axis that can respond to user actions like mouse clicks and drags.

2. **Mathematical Engine**:
   - Core mathematical functions include:
     - **Change of Basis**: Converts vectors between arbitrary bases for advanced linear algebra operations.
     - **Translation**: Moves points in space using specified directional vectors.
     - **Homothety**: Scales objects relative to a center point with a specific ratio.
     - **Rotation**: Supports 3D rotations using roll, pitch, and yaw angles.
     - **Projection**: Projects 3D points into 2D space for visualization.

3. **Modular Object-Oriented Design**:
   - The code separates concerns through modules for rendering (`objects.py`), mathematical transformations (`transformations.py`), and the main application logic (`main.py`).
   - Scalability is inherent, allowing for the integration of new shapes or geometric tools.

4. **Real-Time Updates**:
   - The application employs a **delta-time loop** to ensure smooth and consistent animation and interaction across different hardware.

5. **Customizable Geometry**:
   - Users can define, manipulate, and observe geometric entities like axes and vectors, allowing hands-on exploration of mathematical concepts.

#### **Functionalities Available**
- **Axis Manipulation**:
  - The 3D coordinate axis is rendered dynamically. Users can click and drag to reposition it within the viewport.
- **Projection to 2D**:
  - Points in 3D space are projected onto a 2D plane, offering insights into 3D-to-2D transformations.
- **Advanced Transformations**:
  - Perform translations, rotations, and scalings on geometric entities with intuitive results.
- **Event Handling**:
  - Responds to mouse clicks and movement for interactive geometry exploration.

#### **Planned Enhancements**
1. **Enhanced Shape Library**:
   - Add common geometric objects like circles, polygons, and curves for visualization.
2. **Dynamic Inputs**:
   - Implement input dialogs for users to provide equations, coordinates, or parameters dynamically.
3. **Educational Tools**:
   - Include step-by-step explanations and visualizations for transformations.
4. **Export Features**:
   - Save visualizations as image files or export data for further analysis.
5. **3D Object Rendering**:
   - Extend the engine to render 3D objects with depth, lighting, and perspective.

#### **Technological Highlights**
- **Python + Pygame**:
  - Delivers a simple yet powerful interactive graphics framework.
- **Numpy Integration**:
  - Efficient mathematical computation and matrix manipulation.
- **Object-Oriented Programming**:
  - Ensures modularity and extensibility.

#### **Project Repository**
- [GitHub Repository](https://github.com/Tutusaus/Geometry) provides access to the source code, detailed documentation, and examples.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>