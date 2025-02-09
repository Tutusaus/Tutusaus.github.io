---
layout: page
title: Geometry
description: A Geogebra clone with an original mathematics engine
img: assets/img/geogebra-export-crop.png
importance: 1
#redirect: http://youtube.com
category: fun
giscus_comments: false
related_publications: false
---

### **Introduction**
[GeoGebra](https://www.geogebra.org/3d?lang=es) is a widely used, free software application that combines geometry, algebra, calculus, and other branches of mathematics into a single, interactive platform. It is particularly popular in educational settings for teaching and learning mathematics, as well as for exploring mathematical concepts visually and dynamically. 

The **Geometry** project is a Python-based graphical application mainly built using **Pygame** and **Numpy**. Its goal is to create a 3D interactive geometric exploration tool inspired by GeoGebra. The tool features an original mathematics engine to handle advanced geometric transformations, projections, and object manipulations.

---

### **Main Features**
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

---

### **Functionalities Available**
- **Axis Manipulation**:
  - The 3D coordinate axis is rendered dynamically. Users can click and drag to reposition it within the viewport.
- **Projection to 2D**:
  - Points in 3D space are projected onto a 2D plane, offering insights into 3D-to-2D transformations.
- **Advanced Transformations**:
  - Perform translations, rotations, and scalings on geometric entities with intuitive results.
- **Event Handling**:
  - Responds to mouse clicks and movement for interactive geometry exploration.

---

### **Planned Enhancements**
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

---

### **Technological Highlights**
- **Python + Pygame**:
  - Delivers a simple yet powerful interactive graphics framework.
- **Numpy Integration**:
  - Efficient mathematical computation and matrix manipulation.
- **Object-Oriented Programming**:
  - Ensures modularity and extensibility.

---

### **How to Download the Project from GitHub**
- [GitHub Repository](https://github.com/Tutusaus/Geometry) provides access to the source code.

To download the full project, follow one of these two steps:

#### **1. Clone Using Git (Recommended)**
To clone the repository using Git, follow these steps:

1. Open a terminal or command prompt.
2. Ensure you have Git installed. If not, download and install it from [git-scm.com](https://git-scm.com/).
3. Run the following command:

   ```sh
   git clone https://github.com/Tutusaus/Geometry.git
   ```

4. Navigate into the cloned directory:

   ```sh
   cd Geometry
   ```

This will create a local copy of the repository on your computer.

#### **2. Download as a ZIP File**
If you prefer to download the repository as a ZIP file, follow these steps:

1. Go to the repository page: [Geometry Repository](https://github.com/Tutusaus/Geometry)
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Extract the downloaded ZIP file to access the files.

---

### **Images**