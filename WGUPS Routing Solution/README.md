# WGUPS Routing Solution

## Overview

This project is a package-routing optimization program for the WGU Postal Service scenario. It uses package data and distance data to create efficient delivery routes and allows users to check package status at a selected time.

The project demonstrates algorithmic problem-solving, data structures, routing logic, and CSV-based data processing.

---

## Problem

The application needed to assign packages to delivery routes using available package and distance data, then report package status based on time.

This is related to the classic Traveling Salesman Problem, where the goal is to minimize travel distance while satisfying delivery constraints.

---

## Skills Demonstrated

- Python programming
- Routing algorithms
- Heuristic optimization
- CSV data processing
- Data structures
- Time-based package status logic
- Command-line interaction

---

## Project Structure

```text
WGUPS Routing Solution/
├── WGUPS_Distance_Table.csv
├── WGUPS_Package_File.csv
├── main.py
└── README.md
```

---

## How to Run

Ensure these files are in the project folder:

- `WGUPS_Distance_Table.csv`
- `WGUPS_Package_File.csv`

Run:

```bash
python main.py
```

The program will prompt for package information and display status based on the selected time.

---

## Use Cases

The routing approach could be adapted to other delivery or route-planning situations when provided with:

- package or stop data
- location/distance data
- delivery constraints
- time-based status requirements

---

## Future Improvements

- Add map-based visualization.
- Add route comparison metrics.
- Add additional delivery constraints.
- Add automated tests.
- Refactor route logic into separate modules.
- Add documentation of the heuristic strategy.

---

## Portfolio Relevance

This project is especially relevant to GIS and spatial problem-solving because it demonstrates routing logic, distance-based optimization, and practical handling of location-related data.
