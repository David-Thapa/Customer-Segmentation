# Customer Segmentation Project using K-means Clustering

## Overview

This project applies K-means clustering algorithm to perform customer segmentation. Customer segmentation involves grouping customers with similar characteristics or behavior, which can be valuable for targeted marketing strategies.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)

## Installation

**1) Clone the repository to your local machine:***

```
git clone https://github.com/your-username/customer-segmentation.git
```
**2) Install the Required Dependencies from requirement.txt:**

Using Pip:
```
pip install -r requirements.txt
```
Using Conda
```
conda install --file requirements.txt
```

## Usage
**1) Navigate to the project Directory:**
```
cd Customer-Segmentation
```

**2) Activate your virtual Environment:**

Using Pip:
```
pipenv shell
```
Using Conda:
```
conda activate "env-name"
```
**3) Run Jupyter Notebook**

For Linux:
```
jupyter-lab
```

## Data

**Student Performance Data Set**

*Source: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?resource=download*

**Atribute Information**

1. customerID - customer's unique iD (numeric: from 1 to 200)
2. gender - customer's sex (binary: male or female)
3. age - customer's age (numeric: from 18 to 70)
4. annual income (k$) - customer's annual income (numeric: from 15k to 137k)
5. spending score (1-100) - customer's spending score (numeric: from 1 to 99)

## Methodology

1. Data Preparation
2. Data Preprocessing
3. Exploratory Data Analysis
4. Tuning the Model (optimizing hyperparameter i.e   "Elbow Method")
5. Training the Model
6. Predicting the cluster


