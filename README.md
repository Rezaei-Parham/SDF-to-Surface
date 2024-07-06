# Surface Extraction using Signed Distance Functions with Gradient Descent and Langevin Dynamics

## Introduction

In this notebook, we will explore methods for extracting surfaces using Signed Distance Functions (SDFs). Specifically, we will compare two optimization techniques:
- **Gradient Descent**
- **Langevin Dynamics**

### Objectives

The primary goal is to demonstrate that Langevin Dynamics can mitigate the problem of gradient descent becoming peaky on the surface, thereby achieving more uniform surface coverage. 

### Approach

1. **Shape Construction**: Create a 3D shape consisting of a sphere and a pyramid.
2. **SDF Calculation**: Compute the signed distance function (SDF) for the constructed shape.
3. **Random Point Generation**: Generate random points within the 3D space.
4. **Optimization Techniques**:
    - **Gradient Descent**: Optimize the positions of the points using gradient descent.
    - **Langevin Dynamics**: Optimize the positions of the points using Langevin dynamics, which adds stochastic noise to the gradient updates.
5. **Visualization**: Use Plotly for interactive 3D visualization of the surfaces and optimized points.

### Required Libraries

To run this notebook, you will need the following Python libraries:
- numpy
- plotly
- scipy
- scikit-image

You can install these libraries using pip:
```bash
pip install numpy plotly scipy scikit-image
