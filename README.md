# ILCsimu

Interactive browser-based simulation of an Iterative Learning Control (ILC) algorithm.

The simulation is a JavaScript implementation of a MATLAB script used for teaching ILC.  
It allows students to experiment directly in the browser by adjusting key parameters and observing the resulting learning behavior.

## 🌐 Live Demo

https://BoBernhardsson.github.io/ILCsimu/

## ⚙️ Adjustable Parameters

- **k** – learning gain  
- **delta** – learning shift (samples)  
- **wf** – low-pass filter bandwidth  
- **Displayed iteration** – manually inspect each learning step  

## 🎬 Features

- 15 s internal simulation (to avoid end effects)
- 10 s visible plot window
- Zero-phase filtering (`filtfilt`-style forward/backward IIR)
- Exact ZOH discretization of the plant
- Animation of learning iterations (non-looping, restartable)

## 📊 Signals

- **yd** – reference signal  
- **y** – plant output (red)  
- **u** – control signal (blue)  

## 🎓 Purpose

This tool is intended for educational use in automatic control courses to help students:

- Visualize iterative learning behavior  
- Explore stability vs. learning gain  
- Understand filtering and phase effects  
- Experiment interactively without MATLAB  

---

Developed for teaching purposes.