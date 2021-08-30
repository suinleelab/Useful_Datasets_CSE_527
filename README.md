# The "Useful Datasets" Repo

Recently I've found myself spending as much (or more!) of my
time looking for datasets and preprocessing them than I have
been actually testing out new algorithmic ideas. As a result,
I've decided to organize the datasets that I've been working with
into this repository both so that I have a central place to grab
copies of stuff I've worked with before and so that other people
don't have to duplicate the work I've done.

The repository is organized as follows: each top-level folder
represents a data modality, with each subfolder corresponding to
a specific dataset. Each dataset folder contains a single Jupyter
notebook. This notebook provides a high level description of the
dataset, and then walks through the process of downloading the
dataset and performing any necessary preprocessing. Ideally, the
notebooks are meant to encapsulate the _whole_ process of
obtaining/cleaning the dataset (i.e., the notebook should download
any files rather than forcing the use to do it externally).
