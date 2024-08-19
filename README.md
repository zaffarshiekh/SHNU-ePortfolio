# SHNU-ePortfolio


## Introduction

Welcome to my professional ePortfolio, which demonstrates my growth and expertise in three key areas of computer science: **Software Design and Engineering**, **Algorithms and Data Structures**, and **Database Management**. This repository contains three artifacts, each representing a different facet of my development throughout my Computer Science program.

## Table of Contents

1. [Artifact 1: 3D Pyramid Visualization](#artifact-1-3d-pyramid-visualization)
   - [Overview](#overview)
   - [Enhancements](#enhancements)
   - [How to Run](#how-to-run)
2. [Artifact 2: Grazioso Salvare Dashboard - Algorithms and Data Structures](#artifact-2-grazioso-salvare-dashboard---algorithms-and-data-structures)
   - [Overview](#overview)
   - [Enhancements](#enhancements)
   - [How to Run](#how-to-run)
3. [Artifact 3: Grazioso Salvare Dashboard - Database Management](#artifact-3-grazioso-salvare-dashboard---database-management)
   - [Overview](#overview)
   - [Enhancements](#enhancements)
   - [How to Run](#how-to-run)
4. [Professional Self-Assessment](#professional-self-assessment)

## Artifact 1: 3D Pyramid Visualization

### Overview

The **3D Pyramid Visualization** project is a C++ and OpenGL-based application initially designed to demonstrate basic 3D rendering techniques. This project involved rendering a 3D pyramid and providing user interaction capabilities such as rotating the model to view it from different angles.

### Enhancements

1. **Advanced Viewing Controls**: Enhanced the user interaction by implementing dynamic camera controls, allowing users to rotate, zoom, and pan the pyramid for a more intuitive experience.
2. **Rendering Optimization**: Improved the rendering pipeline for better performance by refactoring the shader management and scene rendering code.
3. **Enhanced User Interface**: Added a UI overlay to display real-time camera position and viewing angle, giving users immediate feedback during interactions.

### How to Run

1. **Environment Setup**:
   - Install OpenGL and GLEW on your system.
   - Ensure that a C++ compiler (like GCC or MSVC) is installed.

2. **Compiling and Running**:
   - Navigate to the project directory.
   - Compile the code using your C++ compiler:
     ```bash
     g++ -o PyramidVisualization maincode.cpp -lGL -lGLEW -lglfw
     ```
   - Run the executable:
     ```bash
     ./PyramidVisualization
     ```

## Artifact 2: Grazioso Salvare Dashboard - Algorithms and Data Structures

### Overview

The **Grazioso Salvare Dashboard** is a web-based application built using Python and Dash, designed to display and filter animal rescue data interactively. The original implementation provided basic filtering and data display capabilities.

### Enhancements

1. **Binary Search Integration**: Implemented a binary search algorithm for efficient data retrieval from sorted datasets, reducing search time complexity.
2. **Hash-Based Searching**: Added hash-based searching using Python dictionaries for constant-time lookups of commonly queried data.
3. **Data Caching**: Introduced an LRU caching mechanism to store frequently accessed data, reducing redundant database queries and improving response times.
4. **Enhanced Filtering Logic**: Updated the filtering logic to include multiple fields and conditions, ensuring comprehensive results, including both dogs and cats in the "Disaster or Individual Tracking" category.

### How to Run

1. **Environment Setup**:
   - Install Python 3.x and Jupyter Lab or VSCode.
   - Install required Python packages:
     ```bash
     pip install pandas dash dash_table pymongo
     ```

2. **Running the Dashboard**:
   - Place `AAC.animals.json` in the project directory.
   - Open the `example_notebook.ipynb` in Jupyter Lab or `example_script.py` in VSCode.
   - Run all cells in the notebook or execute the Python script to launch the dashboard.
   - Access the dashboard at [http://127.0.0.1:8050/](http://127.0.0.1:8050/).

## Artifact 3: Grazioso Salvare Dashboard - Database Management

### Overview

This artifact focuses on the backend database management for the **Grazioso Salvare Dashboard**. The dashboard interacts with a MongoDB database to store and retrieve animal rescue data, initially implemented with basic CRUD operations.

### Enhancements

1. **Advanced Query Techniques**: Utilized MongoDB’s aggregation framework for complex data manipulations within the database, reducing the application's processing load.
2. **Database Indexing**: Created indexes on frequently queried fields like `rescue_type` and `location` to improve data retrieval speed.
3. **Data Security Enhancements**: Implemented role-based access control (RBAC) for managing user permissions and added encryption for sensitive data fields.
4. **Backup and Recovery**: Set up automated backup and recovery using MongoDB’s `mongodump` and `mongorestore` utilities to ensure data integrity and availability.

### How to Run

1. **Environment Setup**:
   - Ensure MongoDB and MongoDB Compass are installed.
   - Install required Python packages:
     ```bash
     pip install pandas dash dash_table pymongo
     ```

2. **Running the Dashboard**:
   - Place `AAC.animals.json` in the project directory.
   - Open the `example_notebook.ipynb` in Jupyter Lab or `example_script.py` in VSCode.
   - Run all cells in the notebook or execute the Python script to launch the dashboard.
   - Access the dashboard at [http://127.0.0.1:8050/](http://127.0.0.1:8050/).

## Professional Self-Assessment

This section contains my professional self-assessment, reflecting on my journey through the Computer Science program. It highlights how the coursework and the development of this ePortfolio have helped shape my professional goals and prepare me for a career in the computer science field.

[Link to Professional Self-Assessment Document]
