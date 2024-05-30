<<<<<<< HEAD
# ADV_ADS Coursework Project

## Description
This project is part of the Advanced Algorithms and Data Structures coursework. It includes a journey planner for the London Underground system.

## Directory Structure
```
ADV_ADS_Coursework/
├── data/
│   └── London_underground_data.csv
├── docs/
│   ├── GroupX_ID1_ID2_ID3_ID4_ID5.pdf
│   └── progress_journal.pdf
├── src/
│   ├── __init__.py
│   ├── task1.py
│   ├── task1a.py
│   ├── task2.py
│   ├── task2a.py
│   ├── task3.py
│   ├── task3a.py
│   ├── task4a.py
│   ├── shutdown_analysis.py
│   ├── shutdown_routes.py
│   ├── histogram.py
│   ├── tests/
│   │   ├── __init__.py
│   │   └── testing.py
│   │   └── testing2.py
│   │   └── testing3.py
│   │   └── testingHist.py
├── .gitignore
└── README.md
```

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repository-name.git
   ```
2. Navigate to the project directory:
   ```sh
   cd ADV_ADS_Coursework
   ```
3. Install the required Python libraries:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the main script:
```sh
python src/task1.py
```

## Tests
Run the tests using:
```sh
pytest src/tests/
```
=======
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



### Additional Notes:
- **GitHub Repository Details**: Replace `https://github.com/yourusername/london-underground-pathfinder.git` with your actual GitHub repository URL.
- **Contributing Guidelines**: If you decide to include detailed contributing guidelines, create a separate `CONTRIBUTING.md` file in your repository.
- **License**: The example assumes an MIT License. Make sure to create a `LICENSE.md` file in your repository containing the license text. If you choose a different license, update the README accordingly.
- **Acknowledgments**: Customize this section to give credit to any resources or individuals who helped in the development of the project.

This README file will help users understand what your project does, how to set it up, and how to contribute, creating a welcoming and informative front page for your GitHub repository.
>>>>>>> 13da76b157a97ad0bbd51a6dc1ba76e7350da3f1
