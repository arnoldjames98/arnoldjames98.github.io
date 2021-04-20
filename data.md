---
title: Data
---


# Data


Data (.csv) collected for the [Dynamics](https://nbviewer.jupyter.org/url/arnoldjames98.github.io/systemDynamicsAll.ipynb) assignment. Daniel collected this data for characterizing the damping of the cardboard material. Each row of data cooresponds to 1 timestep. The columns are indicated at the top of each file.
*  [Damping Characterization - Motion Capture Data](https://raw.githubusercontent.com/arnoldjames98/arnoldjames98.github.io/main/other/damping.csv)

---
   
Data (.txt) collected from the [Design Optimization](https://nbviewer.jupyter.org/url/arnoldjames98.github.io/designOptimization.ipynb) assignment. The data is in the form of a .txt file of the output of running the optimization code.
*  [Optimization Results - Full Code Output](https://raw.githubusercontent.com/arnoldjames98/arnoldjames98.github.io/main/optimization/optimizationOutput.txt)

Below is an example of how to pull data from this .txt file using regular expressions in Python while working in Google Colab.
```
# Import the Python package for regular expressions
import re

# Pull the .txt file containing the output
!npx degit arnoldjames98/arnoldjames98.github.io/optimization -f

# Now the file is locally in colab, so can load it in via /content
input_filename = 'optimizationOuput.txt'

# Load the text file
with open('/content/optimizationOutput.txt', 'r') as file:
    data = file.read().replace('\n', '')
    
# Pulling all the stiffness inputs to the optimization
allStiffness = re.findall(r'Stiffness: \[(\d+\.?\d*)\]', data)
stiffnessFloats = [float(numeric_string) for numeric_string in allStiffness]

# Pulling all the performance metrics results for each stiffness input
allPerformance = re.findall(r'Performance Metric to Minimize: (\d+\.?\d*)', data)
performanceFloats = [float(numeric_string) for numeric_string in allPerformance]
```
---

Data (.csv) collected for the [Experimental Validation](https://nbviewer.jupyter.org/url/arnoldjames98.github.io/dataCollection.ipynb) assignment. Each row of data cooresponds to 1 timestep. The columns are indicated at the top of each file.
*  [Low Stiffness Experiment - Motion Capture Data](https://raw.githubusercontent.com/arnoldjames98/arnoldjames98.github.io/main/lowStiff/data_low.csv) 
*  [Medium Stiffness Experiment - Motion Capture Data](https://raw.githubusercontent.com/arnoldjames98/arnoldjames98.github.io/main/mediumStiff/data_medium.csv) 
*  [High Stiffness Experiment - Motion Capture Data](https://raw.githubusercontent.com/arnoldjames98/arnoldjames98.github.io/main/highStiff/data_high.csv) 
