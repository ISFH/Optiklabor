# Optiklabor
*  Author: Marlon Schlemminger
*  Contact: m.schlemminger@isfh.de
*  Version: 1.0

## Description
This package includes the code used to process measurements from the ISFH Optiklabor. 

## Install instructions
Open your Git Bash (search for it in your Windows Search after you installed Git). Choose a folder on your local file system where you want to install this software. Navigate to this folder by typing ```cd <folder>```. Clone this repository to this folder by typing:
```git clone https://github.com/ISFH/Optiklabor```

Create a new conda environment in your Anaconda Prompt with:
```conda create --name optiklabor python=3.9```

Activate the environment:
```conda activate optiklabor```

Within your Anaconda Prompt, navigate to your Optiklabor-folder and install the package with all requirements:
```pip install .```


Run the executable script by:
```python optiklabor.py```
