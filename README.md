# CPU Scheduling Simulator

A browser-based CPU scheduling simulator for learning and comparing classic operating-system scheduling algorithms. The project presents a simple virtual lab experience with documentation pages, an interactive simulator, and visual output for process execution.

## Features

- Simulate multiple CPU scheduling algorithms in the browser.
- Enter process arrival time, burst time, and priority values.
- Visualize execution with a Gantt-style chart and summary tables.
- Review turnaround time, waiting time, and CPU utilization.
- Browse built-in documentation pages that explain scheduling concepts.

## Supported Algorithms

- First Come First Serve (FCFS)
- Shortest Job First (SJF, non-preemptive)
- Shortest Remaining Job First (SRJF, preemptive)
- Round Robin
- Priority Scheduling

## Project Structure

- `index.html` - landing page for the virtual lab
- `docs.html` - CPU scheduling notes and algorithm explanations
- `about.html` - team/about page
- `backend/ganttcharts.html` - main interactive simulator
- `backend/js/` - scheduling logic and UI scripts
- `backend/css/` - simulator styles
- `style.css` / `docs.css` - site-wide and documentation styling

## Getting Started

This project is a static website, so no build step is required.

### Option 1: Open locally

1. Download or clone the repository.
2. Open `index.html` in your browser.
3. Click `Simulator` to launch the interactive scheduler.

### Option 2: Use VS Code Live Server

1. Install the Live Server extension in VS Code.
2. Open the project folder.
3. Right-click `index.html` and choose `Open with Live Server`.

## How to Use the Simulator

1. Open the simulator from the homepage or by visiting `backend/ganttcharts.html`.
2. Enter process arrival times, burst times, and priorities.
3. Choose a scheduling algorithm from the dropdown.
4. Adjust the number of processes if needed.
5. Run the simulation to view the execution order, charts, and calculated metrics.

## Built With

- HTML5
- CSS3
- JavaScript
- Bootstrap
- jQuery
- Chart.js
- MathJax

## Notes

- The project uses CDN-hosted libraries for some UI and chart features.
- It is designed as an educational tool for understanding CPU scheduling behavior.

## License

No license file is currently included. Add one before publishing if you want to define reuse terms.

## Author

Sambhav Koshta