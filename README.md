# Page Replacement Algorithm Simulator

## Overview

This project is an interactive Page Replacement Algorithm Simulator developed using Python and Streamlit. It allows users to simulate and compare classic page replacement algorithms with real-time step‑by‑step visualization and performance metrics.

## Features

Implementation of 3 page replacement algorithms :

- **FIFO (First In First Out)**
- **LRU (Least Recently Used)**
- **Optimal (OPT)**

Interactive user interface using Streamlit

Step‑by‑step simulation table with colour‑coded Hit/Miss indicators

Calculation of performance metrics :

- Total Page Faults
- Total Hits
- Hit Ratio
- Miss Ratio

Frame occupancy over time (matrix‑style table)

Algorithm comparison using bar charts (page faults and hit ratio)

Belady’s anomaly analysis : line chart showing page faults vs frame count (1 to 7)

Export simulation steps as CSV

## Technologies Used

- Python
- Streamlit
- Plotly
- Pandas

## How to Run

1. Clone the repository :
   ```
   git clone https://github.com/ParavSharma007/Page-Replacement-Simulator.git
   ```

2. Navigate to the project folder :
   ```
   cd Page-Replacement-Simulator
   ```

3. Install dependencies :
   ```
   pip install -r requirements.txt
   ```

4. Run the app :
   ```
   streamlit run app.py
   ```

## Learning Outcome

This project helps in understanding the behaviour and performance of different page replacement algorithms (FIFO, LRU, Optimal) through step‑by‑step visualisation and comparison. It also demonstrates Belady’s anomaly in FIFO.

## Future Scope

- Add more algorithms : Clock, Second Chance, Enhanced Second Chance
- Working set model simulation
- Animation mode for step‑by‑step execution
- Real‑time side‑by‑side comparison of two algorithms
- Export results as PDF reports

## Author

**Parav Sharma**  
B.E. IT, UIET Panjab University
