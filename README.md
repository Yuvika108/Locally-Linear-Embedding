# Locally Linear Embedding (LLE) Visualization

## Overview

This project demonstrates dimensionality reduction using Locally Linear Embedding (LLE) on a synthetic Swiss Roll dataset. It transforms 3D data into a 2D representation while preserving local structure.

## Dataset

Generated using:

```python
from sklearn.datasets import make_swiss_roll
```

* 1000 samples
* 3D non-linear structure

## Method

* Apply LLE to reduce dimensions from 3D to 2D
* Preserve relationships between neighboring points

## Technologies

* Python
* NumPy
* Matplotlib
* Scikit-learn

## Usage

1. Install dependencies:

```bash
pip install numpy matplotlib scikit-learn
```

2. Run the script:

```bash
python your_file.py
```

## Output

* Original data (2D projection of 3D)
* Reduced 2D representation using LLE

## Note

Use Python 3.10 or 3.11 for compatibility.

## Author

Srishti Mishra
