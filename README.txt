Final report: Disease Gene Association Project [link](https://github.com/mamoonkh/disase_gene_association_project/blob/main/Disease%20Gene%20Association%20with%20Adversarial%20Graph%20Frameworks.pdf)
is included.

For the Disease-Gene Prediction Project all the code to run and visualize the metrics is provided in the Jupyter Notebook: [Deep_Learning_Project_Code.ipynb](https://github.com/mamoonkh/disase_gene_association_project/blob/main/Deep_Learning_Project_Code.ipynb).

All instructions are provided in the Jupyter Notebook.

1. Pytorch and important data science libraries (Numpy and Pandas) must be already installed

2. Install the following packages: 
	pip install torch-scatter -f https://data.pyg.org/whl/torch-1.10.0+cu113.html
	pip install torch-sparse -f https://data.pyg.org/whl/torch-1.10.0+cu113.html
	pip install torch-geometric

Note: The same installation code above is also provided in the Jupyter Notebook

3. The dataset is included as well but can be downloaded within the Notebook.

4. Optionally towards the end, I have provide code to run Node2Vec Algorithm that will generate embeddings for every node that can be used as features to the input.

Note: Prior to running Node2Vec we must install torch scatter which in general takes a lot of time. Also, running the Node2Vec algorithm may require a GPU to train.

