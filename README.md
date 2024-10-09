![image](https://github.com/user-attachments/assets/eb9bcc73-68de-4eae-8429-2b9094eafd08)

# determine_surface

# Molecule Distribution Analysis in Visual Molecular Dynamics (VMD)

This Python program analyzes the distribution of molecules based on data exported from Visual Molecular Dynamics (VMD). It uses interpolation, integration, and statistical techniques to evaluate molecular density across various bins and identifies key indices of molecular distribution.

## Purpose

This program was initially designed to analyze water flow across membranes, aiding in the design of ion exchange membranes for water purification systems.

## Features

- **Data Handling**: Loads molecular distribution data from `.dat` text files.
- **Average Density Calculation**: Computes the average density of molecules across different bin sizes.
- **Key Index Identification**: Uses integration techniques to locate key points in the density profile.
- **Graph Visualization**: Displays a graph with key points and density intervals.
- **Supports Multiple Bin Sizes**: Processes data with different bin sizes.

## Requirements

To run this program, make sure you have Python 3.x installed, and install the following Python packages using either `pip` or `conda`.

### Installation

You can install the required packages as follows:

```bash
# Using pip
pip install numpy matplotlib pandas scipy
```

```bash
# Using conda
conda install numpy matplotlib pandas scipy
```

## step 1

Open your terminal

```
git clone https://github.com/greysonkim98/determine_surface.git
```

## step 2

in the second and thrid block, set your .dat file's directory

## step 3

In the thrid block, set your data file name as a parameter

data = np.loadtext(" ")

## step 4 

Run the program. the color of the read 


