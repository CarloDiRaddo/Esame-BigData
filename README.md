# Esame-BigData

This repository contains a Big Data project that explores and analyzes a dataset using Apache Spark. The repository is organized as follows:

# Notebook

The notebook/ directory contains the Jupyter notebook big_data_project.ipynb which contains the code and analysis of the project.

# Results

The results/ directory contains the output of the project's analysis. Specifically, there are two subdirectories for two separate jobs:

    job1/: contains the results for the first job
    job2/: contains the results for the second job

Each job directory contains two subdirectories:

    CSV/: contains the results in CSV format
    img/: contains the results in image format

# Usage

To use this project, you need to configure an AWS cluster with version 6.9.0 of EMR (Elastic MapReduce), Hive 3.1.3, JupyterEnterpriseGateway 2.6.0, Spark 3.3.0, and Livy 0.7.1.

After configuring the cluster, you can run the Jupyter Notebook big_data_project.ipynb and use the code to analyze the dataset. Make sure you have all the necessary dependencies installed on the cluster, including Apache Spark and Jupyter Notebook.

Once you have run the code and generated the results, you can view them using the instructions in the README file in the results folder.
# Dependencies

This project requires the following dependencies:

    Apache Spark (version  3.3.0)
    Jupyter Notebook (version X.X.X)

Please make sure to install these dependencies before running the project.
