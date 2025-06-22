# 2D Floor Planner

A Java Swing-based desktop application for designing simple 2D floor plans interactively. Users can add rooms, place furniture, and manage room layouts with visual feedback and placement constraints.

## Features

- 🧱 Add rooms with specific dimensions and color-coded by type:
  - Bedroom (Green)
  - Bathroom (Blue)
  - Kitchen (Red)
  - Living/Dining Room (Yellow/Orange)
- 🚫 Overlap detection: Prevents overlapping room placements.
- ➕ Relative room placement (north, south, east, west with alignment).
- 🪟 Add doors and windows with constraints (e.g., no exterior bathroom doors).
- 🛏️ Add and rotate basic furniture and fixtures (bed, chair, sofa, etc.).
- 🖱️ Drag-and-drop support for moving rooms.
- 💾 Save and load floor plans in a custom format.

## File Structure

- 📁 **Furniture Images** – Directory containing PNG images for furniture and fixtures.  
- 📄 **Canvas.java** – Main file that sets up the GUI, canvas area, and core rendering logic.  
- 📄 **Door.java** – Class for handling door elements and placement logic.  
- 📄 **Furniture.java** – Handles adding, placing, and rotating furniture items.  
- 📄 **Room.java** – Represents individual rooms with attributes like dimensions, position, and type.  
- 📄 **RoomCommand.java** – Handles logic for room placement and alignment.  
- 📄 **newFrame.java** – Utility class used for re-rendering or refreshing the UI when needed.  
- 📄 **README.md** – Project description and documentation.

## How to Run

1. Compile the Java files:
   ```bash
   javac *.java
2. Run the application:   
   ```bash
   java Canvas

