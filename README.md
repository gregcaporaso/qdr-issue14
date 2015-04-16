[![DOI](https://zenodo.org/badge/11339/gregcaporaso/qdr-issue14.svg)](http://dx.doi.org/10.5281/zenodo.16901)

# Greengenes 85% OTU PyNAST alignment appears to be a suitable replacement for the Greengenes Core Set template alignment for use with PyNAST.

This analysis and discussion arises from notes I put together while working on biocore/qiime-default-reference#14.

This repository contains python code and IPython Notebooks designed to run on the QIIME 1.9.0 AWS instance. You can find
that AMI on the [QIIME resources page](http://qiime.org/home_static/dataFiles.html).

## Setup and install

The analyses presented in our paper were run on an m3.2xlarge instance (some of the steps are run in parallel on four processors). 

The notebooks can be installed as follows on the 1.9.0 AWS instance.

```
cd $HOME
git clone https://github.com/gregcaporaso/qdr-issue14.git
```
## Using the IPython Notebooks included in this repository

To view and interact with an [IPython Notebook](http://ipython.org/notebook.html), change into the ``qdr-issue14`` directory and [start the IPython Notebook server in a screen session](http://qiime.org/tutorials/working_with_aws.html#connecting-to-your-qiime-ec2-instance-using-the-ipython-notebook).

## Citing

If you use any of the data or code included in this repository, please cite as: *Greengenes 85% OTU PyNAST alignment appears to be a suitable replacement for the Greengenes Core Set template alignment for use with PyNAST. J Gregory Caporaso (2015, DOI: ``include DOI listed above``).*
