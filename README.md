# Computational Physics Lab Assignments

The Jupyter notebooks included here explore a wide range of numerical methods used to solve physical problems, from basic integration to complex differential equations and stochastic simulations.

---

## Notebooks Overview

### 1. Python Programming Foundations
**File:** `1. Python Programming.ipynb`  
**Focus:** Fundamental programming logic and sequence generation.  

**Key Tasks:**
- Implementing functions for the Fibonacci sequence.
- Handling large numerical values (up to \(10^9\)) and analyzing relative differences in series.

---

### 2. Numerical Integrals and Derivatives
**File:** `2. Integrals and Derivatives.ipynb`  
**Focus:** Approximating calculus operations numerically.  

**Key Tasks:**
- Comparing the **Trapezoidal Rule** and **Simpson's Rule** for integration across varying slice counts (10 to 1,000).  
- Numerical differentiation of complex functions and error analysis relative to analytical derivatives.

---

### 3. Linear and Nonlinear Equations
**File:** `3. Linear and Nonlinear Equations.ipynb`  
**Focus:** Solving systems of equations and root-finding.  

**Key Tasks:**
- Matrix inversion and **LU Decomposition** for simultaneous linear equations.  
- Implementing **Newton's Method** and the **Secant Method** to find roots of nonlinear physical equations.

---

### 4. Fourier Transforms
**File:** `4. Fourier Transform.ipynb`  
**Focus:** Signal processing and image deblurring.  

**Key Tasks:**
- Performing **Discrete Fourier Transforms (DFT)** of modulated sine waves.  
- Utilizing `rfft2` and `irfft2` to perform image deconvolution (de-blurring) by dividing the signal by a **Point Spread Function (PSF)**.

---

### 5. Ordinary Differential Equations (ODEs)
**File:** `5. Ordinary Differential Equations.ipynb`  
**Focus:** Modeling dynamic systems over time.  

**Key Tasks:**
- Solving the **Lotka-Volterra equations** to model predator-prey population dynamics.  
- Solving the **Schrödinger equation** for an oscillator in a box to find stationary states and normalized wavefunctions.

---

### 6. Partial Differential Equations (PDEs)
**File:** `6. Partial Differential Equations.ipynb`  
**Focus:** Time-dependent wave propagation.  

**Key Tasks:**
- Implementing the **Crank-Nicolson method** to solve the time-dependent Schrödinger equation.  
- Visualizing a wavefunction as it disperses and reflects off the boundaries of a finite potential box.

---

### 7. Random Processes and Monte Carlo Methods
**File:** `7. Random Process and Monte Carlo Methods.ipynb`  
**Focus:** Stochastic modeling and statistical mechanics.  

**Key Tasks:**
- **Monte Carlo Integration:** Comparing the "hit-or-miss" method vs. the mean value method for complex integrals.  
- **Ising Model:** Simulating spin configurations and calculating magnetization trends.

---

## Requirements
To run these notebooks, ensure you have the following Python environment:

- **Python:** 3.x  
- **Core Libraries:** `numpy`, `matplotlib`, `scipy`  
- **Optional:** `tqdm` (for progress bars)

---

## Acknowledgements
The problems in these modules are largely based on the textbook **_Computational Physics_** by Mark Newman.
