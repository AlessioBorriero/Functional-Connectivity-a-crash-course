# Functional-Connectivity-a-crash-course

## Overview

**Functional-Connectivity-a-crash-course** is a hands-on crash course designed to guide you through fMRI-based functional connectivity analysis using Python and Jupyter Notebooks. This repository contains four step-by-step notebooks that cover data preprocessing, time‑series extraction, connectivity estimation, and graph‑theoretical metrics.

## Repository Structure

````
Functional-Connectivity-a-crash-course/
├── notebooks/
│   ├── lecture_1_seed_based_functional_connectivity.ipynb
│   ├── lecture_1_seed_based_functional_connectivity_CompleteVersion.ipynb
│   ├── lecture_2_PCA&ICA_based_functional_connectivity.ipynb
│   ├── lecture_2_PCA&ICA_based_functional_connectivity_CompleteVersion.ipynb
│   ├── lecture_3_graph-based_functional_connectivity.ipynb
│   ├── lecture_3_graph-based_functional_connectivity_COMPLETEVERSION.ipynb
│   ├── lecture_4_dynamic_functional_connectivity.ipynb
│   ├── lecture_4_dynamic_functional_connectivity_GLASSER.ipynb
│   └── lecture_4_dynamic_functional_connectivity_SCHAEFER.ipynb
|
├── slides/
│   └── FunctionalConnectivityLectures_v3.pdf
├── requirements.txt
└── README.md**: This document.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Packages listed in `requirements.txt` (e.g., NumPy, SciPy, NiBabel, Nilearn, Matplotlib, NetworkX)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Functional-Connectivity-a-crash-course.git
   cd Functional-Connectivity-a-crash-course
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Data

The example fMRI dataset is not included in this repository due to size constraints. To access the data, please open an issue or email the maintainers. Once you have the data, place it in a folder named `data/` at the root of this project.

## Lectures

The notebooks cover 4 different topics regarding functional connectivity:
1. Seed-based functional connectivity
2. PCA and ICA -based functional connectivity
3. Graph-based functional connectivity
4. Dynamic functional connectivity

Each lecture is provided in two versions: an incomplete version that allows you to build the analysis from scratch, and a complete version that provides full step-by-step solutions.

## Contributing

Contributions are welcome! Please fork the repo and submit a pull request. For major changes, open an issue first to discuss your ideas.

## Contact

Alessio Borriero – [alessio.borriero@unito.it](mailto:alessio.borriero@unito.it)

Project Link: [https://github.com/your-username/Functional-Connectivity-a-crash-course](https://github.com/your-username/Functional-Connectivity-a-crash-course)
