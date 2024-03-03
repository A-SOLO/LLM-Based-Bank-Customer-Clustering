# LLM-Based-Bank-Customer-Clustering
In the realm of customer clustering projects, the combination of LLM with the robust K-Means algorithm stands out as the crown jewel. This powerful approach not only incorporates the strength of traditional K-Means clustering but also harnesses the unique capabilities of LLM, promising impeccable results in customer segmentation. 

Applying dimensionality reduction techniques (PCA, t-SNE, MCA) and proficient K-means, K-Prototype, and LLM methodologies for clustering can enhance model interpretability.

# Data
The original data used in this project is from a public Kaggle dataset called ["Banking Dataset - Marketing Targets"](https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets/data). Each row in this dataset contains information about a company's customers, including both numerical and categorical fields. This diversity in data types opens up various approaches to the problem.

For this project, we will focus on the first 8 columns of the dataset, which include:

* age (numeric)
* job: type of job (categorical)
* marital: marital status (categorical)
* education: education level (categorical)
* default: has credit in default? (binary)
* balance: average yearly balance(numeric)
* housing: has a housing loan? (binary)
* loan: has a personal loan? (binary)
The project uses the training dataset from Kaggle, which can be found in the "data" folder of the project repository as a compressed file. Inside the compressed file, you'll find two CSV files: train.csv (the original training dataset) and embedding_train.csv (the dataset after performing an embedding).

# Getting Started:
## Installation:

```pip install -r requirements.txt```

## Methodologies:
### K-Means:
The complete procedure can be found in the Jupyter notebook titled ```kmeans.ipynb```.
### K-Prototype:
To create clusters when you have a mix of features (categorical and numerical), steps can be found in Jupyter notebook titled ```kprototypes.ipynb```.
### LLM + K-Means:
To apply llm in cluttering projects, steps can be found in file titled embedding.ipynb.

