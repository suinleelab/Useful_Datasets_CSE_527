# CSE 527 Data Portal

Welcome to [CSE 527 (Computational Biology)](https://sites.google.com/cs.washington.edu/cse527/home)! To help everyone
brainstorm final project ideas, we've provided some sample
datasets that have previously been used in high impact
computational biology publications.

The repository is organized as follows: 

*gene_expression
In this folder, each top-level folder represents a data modality (e.g. gene expression data), with each
subfolder corresponding to a specific dataset. Each dataset folder 
contains a single Jupyter notebook. Jupyter is an interactive computing
environment that allows you to run Python code in your browser and interact
with the output of or code. See [here](https://jupyter.org/install.html) for
instructions on how to install Jupyter and [here](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html)
for instructions on how to run Jupyter after installation.

For each dataset, the corresponding notebook provides a high
level description of the dataset, and then walks through the process
of downloading the dataset and performing any necessary preprocessing.
Ideally, the notebooks are meant to encapsulate the _whole_ process of
obtaining/cleaning the dataset (i.e., the notebook should download
any files rather than forcing the use to do it externally). However, due to
restrictions on data sharing for some datasets, you may need to download the
files yourself from another source.

*mimic-code
This folder contains example script of how to use MIMIC-III, a freely-available electornic health record database comprising deidentified health-related data associated with over 40,000 patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012. It will take few steps to obtain data access [here](https://mimic.mit.edu/docs/gettingstarted/) which will only take few days. 


*eICU-code
eICU is another publicly available EHR dataset. Same as MIMIC, uses would need to requesting access to the eICU Collaborative Research Database through [here](https://eicu-crd.mit.edu/gettingstarted/access/)

*mimic-cxr 
This folder contains example code for Chest x-ray images [https://physionet.org/content/mimic-cxr/2.0.0/]

Please reach out to the TAs with any questions! The initial datasets in the repository
are datasets that the TAs are familiar with from previous research projects, and we'll
be adding more over the next few days. If you're looking for a specific kind of data
but can't find it here, please get in touch; we're more than happy to point you in the
right direction.

## Contributing

If you already have data (e.g. from your own independent research) and are comfortable sharing
it, you can earn participation points for the class by contributing your dataset to the repository.
Please get in touch with the TAs for instructions on how to contribute.
