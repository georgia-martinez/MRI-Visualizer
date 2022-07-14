# MRI Visualizer

This repository contains code to visualize MRI volumes in 2D and 3D.

First, install the necessary libraries:
```
pip3 install -r requirements.txt
```

There are two different notebooks: one for 2D and one for 3D visualizations. Both notebooks utilize SimpleITK to read the MRI files and convert them into numpy arrays.

The 2D visualizer notebook will walk you through how to view individual slices in an MRI volume with matplotlib.

The 3D visualizer notebook will walk you through how to create a 3D model of a specific region in an MRI volume (e.g. tumor). The models are generated using the marching cubes algorithm from skimage. The models are also interactive and were created with plotly. The plotly models can be saved as HTML files.
