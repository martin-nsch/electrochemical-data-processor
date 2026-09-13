# electrochemical-data-processor
Tool to automate extraction of ECSA, resistances from CV and PEIS for redox flow batteries
written in python 3.8.8
old project from 2023, so code is not up to date
code was written for very specific use case
usefull part for other projects is the toolbox jupyter file containing 3 functins

![Set up](set_up.jpeg)
## Overview
* **`data_processor.ipynb`**:
  
* **`toolbox.ipynb`**:

  
## Requirements
* **Python 3.8.8** (or newer)
* **os library**
* **pandas library**
* **numpy library**


## Usage

```text
📁 repository_root/
├── 📄 data_processor.ipynb
├── 📄 toolbox.ipynb
├── 📄 weight.xlsx
├── 📁 data/
├── 📁 results/
├── 📁 Experiment_01/
│   ├── 📄 CV_test1.txt
│   ├── 📄 PERF_test1_PEIS.txt
│   ├── 📄 PERF_test1_PCGA.txt
│   └── 📄 PERF_test1_PEIS.txt
└── 📁 Experiment_02/
```

## Theoretical Background
## Cyclic Voltametry
Cyclic Voltametry (CV) is to determine electrochemically active surface area.
![CV example](CV_example.png)
### Potentiostatic Electrochemical Impedance Spectroscopy
Potentiostatic Electrochemical Impedance Spectroscopy (PEIS) is used to determine half-cell resistances.
![PEIS1 example](PEIS1_example.png)
![PEIS2 example](PEIS2_example.png)
### Potentiodynamic Cycling with Galvanostatic Acceleration
Potentiodynamic Cycling with Galvanostatic Acceleration (PCGA) is used to determine half-cell performance
![PCGA example](PCGA_example.png)

