# Cultural Algebra

This is an attemp to apply some algebra concepts to cultural studies.

This project uses the [Murdock Ethnographic Atlas Data set](https://d-place.org/contributions/EA) as a description of each cultures and turn to create a algebraic multi-dimensional space, where is culture is represented a as vector of all their political, economic, kinship, etc. to calculate similarity among cultures as teh cosine distance between vectors.

To see the whole analysis in detail, please click on [Full Cultural Algebra analysis](https://nbviewer.jupyter.org/github/anankeman/Cultural-Algebra/blob/master/cultural%20similarity.ipynb)


## TDLR

- Load an clean datasets
- Apply `one hot encoding` to categorical variables
- Merge with ordinal and numeric variables
- Normalize values
- Create a sparce matrix of Cosine distance values between ethnic groups
- Use the matrix to get the most similar cultures
- Use the matrix to build a graph model, where close cultures create links between them
- Apply dimensionality reduction to visualy map the cultural space usin `Tsne` and `PCA`
- Use clustering algorithms to try to group ethnic groups
- Compare cluster with family and geographical relations

Sample of dimensional space and cluster strategies

![Clusters](output.png)

## Author

@[Pippo Ramos](https://github.com/pippo-sci)


## Tech Stack

![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

- Python 3.8
- Jupyter notebook
- Pandas
- Numpy
- Scklearn
- NetworkX
