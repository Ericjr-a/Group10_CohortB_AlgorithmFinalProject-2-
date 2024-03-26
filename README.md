Closest Pair Finder in 3D Space
Brief Description:
This Python program identifies the closest pair(s) of points within a given set in 3-dimensional space. It is designed to process large datasets efficiently, utilizing both brute-force and divide-and-conquer strategies to optimize performance. The program also visualizes the dataset and highlights the closest pairs, making it a useful tool for data analysis and collision detection in simulations.

Requirements
Python 3
Pandas
NumPy
Plotly

Usage:
Prepare your dataset: Ensure that your dataset is in the correct format.

Modify the script to point to your dataset file: Replace the file path in the pd.read_csv() function with the path to your dataset file.

Adjusting the collision threshold: The collision_threshold variable can be adjusted based on the desired sensitivity of collision detection. A lower value will identify pairs of points that are closer together.

Run the script: Execute the script using Python. The script will read the dataset, identify the closest pair(s) of points based on the provided threshold, and visualize the points in 3D space using Plotly. Closest pairs will be highlighted(red)

Viewing results:
The script generates a 3D scatter plot with all points visualized. Points that form the closest pair(s) are connected with lines and highlighted in a different color(red) for easy identification.

Features
Efficiently processes large datasets to find the closest pair(s) of points in 3D space.
Utilizes both brute-force and divide-and-conquer strategies for optimal performance.
Visualizes the dataset and highlights the closest pairs, aiding in data analysis and collision detection.
Customizable collision threshold for flexible sensitivity adjustment.

The dataset used was from : https://www.dropbox.com/sh/ehhv9thpuvb36jq/AADQowvv9FfQ8ZYdAPL9qJs1a?dl=0
specifically , the 3D_VisualSim_10M.pbbs dataset was used. The dataset was too large to be tested on and even to be uploaded here so 200 entries of selected inputs were used from '3D_VisualSim_10M.pbbs'

Link to github repository : https://github.com/Ericjr-a/Group10_CohortB_AlgorithmFinalProject-2-/tree/main
