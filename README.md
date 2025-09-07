# 2D FRAP Simulations  

Simulate and analyze fluorescence recovery after photobleaching (FRAP) in a 2D square cell. Key highlights:

- **Cell Setup**:  
  - Square cell: 2 µm × 2 µm  
  - Central bleached region: 0.2 µm × 0.2 µm  
  - Initial fluorescence: 1 µM in unbleached regions  
  - Lattice: 200 × 200 points (10 nm spacing)  
  - Diffusion coefficient: 10 µm²/s  

- **Random Walker Simulation**:  
  - Place walkers in unbleached regions only  
  - Reflecting boundaries keep walkers inside the cell  
  - Run hundreds to thousands of simulations for robust averaging  
  - Visualize how average concentration maps approach equilibrium  
  - Track recovery of fluorescence in the bleached region over time  

- **Analysis Goals**:  
  - Examine spatial recovery across the cell  
  - Monitor time-dependent recovery of the bleached region  
  - Compare simulated dynamics to theoretical expectations  

- **Technical Details**:  
  - Fully vectorized simulations in Python for efficiency  
  - Libraries: `numpy`, `matplotlib`, `seaborn`  

This repository provides a computational framework for exploring diffusion-driven fluorescence recovery and comparing different FRAP simulation methods.
