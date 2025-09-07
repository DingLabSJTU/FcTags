# Fluoro-changing Tags Based on DNA Strand Displacement Enable Highly Multiplexed Protein Imaging
## Overview of FcTags
Fluoro-changing Tags (FcTags) are capable of generating exponentially scalable antibody tags for spatial proteomics imaging with easily accessible equipment and reagent. To decode proteins from FcTag-based images, we developed a algorithm based on linear unmixing here. Step-by-step codes and important notes are provided in each section, with data stored in the corresponding folders.

## Environmental setup
See pyproject.toml file for library version and various dependencies. Here are the steps to setup the python environment:

### 1. Install Jupyter Notebook 7.x (or Python 3.x)
The algorithm is crafted in Python and executed within Jupyter Notebook.  To execute the files, you have the option to install either `Python 3.x` or `Jupyter Notebook 7.x`.

To install Jupyter Notebook 7.x, you can download it from the [official Jupyter website](https://jupyter.org/).

To install Python 3.x, you can download it from the [official Python website](https://www.python.org/).

### 2. Update `pip` (optional)
It's a good practice to keep `pip` up to date. Open a terminal (or command prompt) and run the following command:

```bash
python -m pip install --upgrade pip
```

### 3. Install Required Libraries
To install the necessary packages (`numpy`, `PIL`, `cv2`, `pandas`), run the following command in your terminal or command prompt:

```bash
pip install numpy scipy scikit-image pandas
```

### 4. Verify Installation
After installation, you can verify that the libraries are installed correctly by running this Python script:

```python
import numpy as np
import cv2
import pandas as pd

print(f"numpy version: {np.__version__}")
print(f"cv2 version: {cv2.__version__}")
print(f"pandas version: {pd.__version__}")
```

This script will print the installed versions of the libraries. If you see the version numbers printed without any errors, the libraries were installed successfully.
