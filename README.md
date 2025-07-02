# 🚗 Multi-Lane Traffic Simulation in Python

This project simulates traffic flow on multi-lane roads using a cellular automata model. It supports:

- Configurable number of lanes, speed limit (Vmax), slowdown probability, lane-changing behavior
- Three lane-changing strategies: no change, right-hand preference, and free change
- Visualization of:
  - Flow vs. Density
  - Average speed vs. Density
  - Flow vs. Lane count / Vmax / p_slowdown / p_change_lane
  - Velocity distribution with confidence interval

## 📂 Files

- `notebook_demo.ipynb`: interactive demo of the simulation
- `requirements.txt`: dependencies for easy installation


## 📊 Example Visualization

Results include plots such as flow-density curve and velocity histograms.

## 🔧 Future Improvements

- GUI-based simulation controller
- Add real-time animation
- Calibration with real traffic data
