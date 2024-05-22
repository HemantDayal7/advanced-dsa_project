# London Underground Pathfinding

This project provides a Python application for finding the shortest path between stations on the London Underground. It uses Dijkstra's algorithm to compute the shortest routes and travel times based on user input.

## Description

The application is structured into several modules, each handling a specific part of the program's functionality:
- `graph.py`: Manages the graph data structure representing the tube network.
- `loader.py`: Responsible for loading data from CSV files into the graph.
- `main.py`: The main driver of the application, handling user interactions and algorithm execution.
- `user_interface.py`: Manages user input and output interactions.
- `dijkstra_interface.py`: Adapts the graph data for use with the Dijkstra algorithm provided by the `clrsPython` package.

## Installation

To run this project, you will need Python installed on your system. Follow these steps to set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/hemantdayal7/london-underground-pathfinder.git
