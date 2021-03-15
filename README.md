# graphSEG2: a Python based interactive Seismic Refraction Graphing Toolset. 

The use of seismic refraction datasets is crucial to Near-surface geophysical explorations and are often used to delineate depths to bedrock. This project will utilize the Obspy python framework to read SEG2 refraction datasets and plot interactive stream datasets using the matplotlib.pyplot.ginput function.


Table of contents
-----------------
- [Installation](#Installation)
- [Importing](#Importing-function)
- [graphSEG2.pick](#graphSEG2.pick)
  *  [Making First Arrival Picks](#first-arrivals)
- [graphSEG2.analyze](#graphSEG2.analyze)
  *  [Slope Break Method](#slope-break)
  *  [Linestatistics.py](#linestatistics)
- [graphSEG2.crossover](#graphSEG2.crossover)
  *  [Findclosestpoint.py](#Findclosestpoint)
  *  [Running Findclosestpoint.py](#RunningFindclosestpoint.py)


## Installation

1.	Add obspy to separate conda environment:
```bash 
conda create -n obspy python=3.6
```
2.	Initialize the environment using the command while in the anaconda command prompt: 
```bash
conda activate obspy
```
3.	Since this module works best with spyder, while in activated obspy environment install spyder using:
```bash 
conda install spyder 
```
then update all packages using:
```bash 
conda update --all 
```
4.	For missing dependencies e.g. pandas use:
``` bash
conda install pandas
```
6.	To get started, activate spyder by typing spyder in open terminal.


## Importing

To import the function, use the code:`from graphSEG2_v2 import graphSEG2` in python script.
This allows the user script in use to have access to the graphSEG2 function and its executables. While in spyder highlight graphSEG2_v2 in the script and press *CTRL + i* for a mini user guide.

