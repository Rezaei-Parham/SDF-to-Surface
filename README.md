# Surface Extraction using Signed Distance Functions with Gradient Descent and Langevin Dynamics

## Overview

This project demonstrates methods for extracting surfaces using Signed Distance Functions (SDFs). It compares two optimization techniques:
- **Gradient Descent**
- **Langevin Dynamics**

The primary goal is to show that Langevin Dynamics can mitigate the problem of gradient descent becoming peaky on the surface, thereby achieving more uniform surface coverage.

## Objectives

1. Load a detailed 3D mesh (Stanford Bunny).
2. Compute the signed distance function (SDF) for the loaded mesh.
3. Generate random points within the 3D space.
4. Optimize the positions of the points using Gradient Descent and Langevin Dynamics.
5. Visualize the initial and final positions of the points using Plotly.

## Requirements

To run this project, you need the following Python libraries:

- numpy
- plotly
- scipy
- scikit-image

You can install these libraries using pip:

```bash
pip install numpy plotly scipy scikit-image
