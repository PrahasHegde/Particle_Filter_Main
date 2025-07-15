# 🎯 Particle Filter for Multi-Ball Tracking under Dropout Conditions

This project implements a **Particle Filter-based tracking system** to estimate the trajectories of **multiple balls** in a 2D environment. It simulates projectile motion, introduces observation noise and dropout (i.e., missing measurements), and uses **independent particle filters** for each ball to robustly track their motion.

---

## 🔍 Features

- Simulates the 2D trajectory of multiple balls using projectile physics  
- Adds noise to simulate real-world sensor inaccuracies  
- Handles **dropout conditions** (temporary loss of observations)  
- Tracks each ball using its own particle filter  
- Real-time visualization of actual vs. estimated trajectories

---

## 🧠 Technologies Used

- **Python**
- **NumPy** – Numerical computations
- **Matplotlib** – Visualization
- **Custom Classes** – For simulation and particle filtering

---

## 🚀 How It Works

1. **Simulation**:  
   Generates synthetic projectile trajectories for multiple balls using physics equations.

2. **Noise + Dropout**:  
   Adds Gaussian noise to simulate sensor errors and randomly drops measurements to mimic tracking loss.

3. **Particle Filter**:  
   - Initializes a cloud of particles for each ball  
   - Predicts motion using physics  
   - Updates weights based on noisy observations  
   - Resamples particles to focus on high-probability states

4. **Visualization**:  
   Plots ground truth, noisy observations, and estimated paths in real time.

---

## 📂 Project Structure

```
📁 ParticleFilterProject/
│
├── portfolio2.ipynb        # Jupyter Notebook with full implementation
├── README.md               # This file
```

---

## 📸 Sample Output

(You can add a screenshot here showing tracking vs. ground truth for clarity.)

---

## 🛠️ How to Run

1. Clone the repository or download the notebook.  
2. Make sure you have the required libraries:

```bash
pip install numpy matplotlib
```

3. Open the notebook:

```bash
jupyter notebook portfolio2.ipynb
```

4. Run all cells to simulate and visualize the tracking.

---

## 📬 Contact

For questions or feedback, feel free to connect with me on [LinkedIn](#) or check out the code on [GitHub](#).
