This repository contains code to visualize MRI volumes in 2D and 3D. Make sure to install all the dependencies with the command "pip3 install -r requirements.txt" before trying to run any of the notebooks.

The 2D visualizer notebook will walk you through how to view individual slices in an MRI volume with the matplotlib library.

The 3D visualizer notebook will walk you through how to create a 3D model of a specific region in an MRI volume (e.g. tumor). The models are generated using the marching cubes algorithm from the skimage library. The models are also interactive and were created with the plotly library.