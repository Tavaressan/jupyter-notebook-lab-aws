# Vertebral Spine Data Analysis

This repository contains a Jupyter Notebook used for a lab in the AWS AI Certification course. The notebook demonstrates how to import and perform an initial analysis of the Vertebral Column dataset from the UCI Machine Learning Repository.

## About the Notebook

The `ImportingDataVertebralSpine.ipynb` notebook performs the following steps:
1.  Downloads the Vertebral Column dataset from the UCI repository.
2.  Extracts the data from the downloaded zip file.
3.  Loads the data from the `column_2C_weka.arff` file into a pandas DataFrame.
4.  Displays the first few rows of the DataFrame.

## Dataset

The dataset used in this notebook is the **Vertebral Column Data Set**.

-   **Source:** [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Vertebral+Column)
-   **Files:** The notebook downloads the data, which includes `column_2C_weka.arff` and other files.

## Running the Notebook

To run this notebook, you need to have Jupyter Notebook or JupyterLab installed, along with the following Python libraries:

-   `requests`
-   `pandas`
-   `scipy`

You can install these libraries using pip:
```bash
pip install requests pandas scipy
```

After installing the dependencies, you can launch Jupyter and open the `ImportingDataVertebralSpine.ipynb` file.
