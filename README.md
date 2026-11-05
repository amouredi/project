# AFCON 2025 | Fixture-Stadium Fairness Optimization

## Project Overview

This project investigates whether stadium and fixture assignments for the **2025 Africa Cup of Nations (AFCON)** could be optimized to improve competitive fairness by minimizing travel disparities between participating teams.

Using **Python and Gurobi Optimizer**, I developed an integer programming model that minimizes the maximum travel burden experienced by any team, subject to real-world constraints including stadium capacity, host-nation requirements, and geographic considerations.

To evaluate the effectiveness of the optimization model, I developed a **greedy heuristic** as a benchmark and compared both approaches against the Confederation of African Football's (CAF) official tournament allocations.

## Key Results

- **Group Stage:** Reproduced CAF's allocation performance, with a maximum team travel burden of 5.66 hours and 79.26 total travel hours.
- **Knockout Stage:** Reduced Egypt's modeled travel burden from 15.73 to 9.60 hours, representing a **39% improvement** over the official allocation.
- **Benchmark Comparison:** Outperformed the greedy heuristic, which achieved 11.14 hours for Egypt's knockout-stage travel.

## Engineering Significance

The project demonstrates how **operations research, mathematical optimization, and algorithmic decision-making** can improve resource allocation while balancing competing objectives and operational constraints.

Although developed for tournament scheduling, the methodology is transferable to industrial engineering applications such as production scheduling, facility allocation, logistics network optimization, and manufacturing resource planning.
