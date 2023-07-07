# Drag & Drop Application

This is a simple web-based application demonstrating drag-and-drop functionality built using HTML, CSS, and JavaScript.

## Overview

The application simulates a task board with three columns: 'Start', 'In Progress', and 'Done'. Users can drag a task from one column and drop it into another, allowing them to visually manage the progress of their tasks.

Drag and drop operations are managed through native HTML5 drag and drop API, enhanced with JavaScript to handle the events.

## Files

The application consists of three main files:

1. `index.html`: This is the main page of the application, where the task board is displayed. Each column of the board includes a header and a placeholder for dropping the tasks.

2. `styles.css`: This file contains the styling for the application, including the layout of the task board, task item, and the visual effects during the drag and drop operation.

3. `app.js`: This is the main logic of the application. It handles the drag and drop operations of the task item, including the visual effects during dragging, and the placement of the task item upon drop.

## Usage

1. Open `index.html` in your preferred web browser to start the application.
2. You'll see a task named "Drag Me" in the 'Start' column. Click and hold on the task to start dragging it.
3. Drag the task to 'In Progress' or 'Done' column and release the mouse button to drop the task.
4. You can continue to drag and drop the task between columns as much as you like.
