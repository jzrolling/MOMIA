## Introduction

MOMIA (or Mycobacteria Optimized Microscopy Image Analysis) is a python based image analysis toolkit optimized for dealing with mycobacterial cells. Given a single or a set of fluorescent microscopic image(s), MOMIA renders accurate object segmentation and graphical representation of fluroescent or morphological profiles at both the single cell level and the populational level. MOMIA was developed to analyze a *M. smegmatis* fluorsecent protein tagging library (Mycobacterial Systems Resource, Dendra, or MSR-Dendra) which accounts for over 1,000 highly conserved mycobacterial genes. You may find the MSR-Dendra dataset (along with many other amazing mycobacterial resources) on this [website](http://msrdb.org/). 

A light-weight, Non-negative matrix factorization (NMF) based post-segmentation data analysis tool, GEMATRIA (Graph Embedded, Multi-Attribute Temporal Reconstruction of Intracellular protein Allocation) is also included in this deposit. GEMATRIA seeks to infer visually intuitive features from high-throughput fluorescent-protein imaging datasets. These protein localization features, in combination with a cell length based binning approach, enables the users to approximate and quantitate the spatio-temporal dynamics of proteins of interest. 

## MOMIA is still under development, please use with caution. ##

## Installation

To install MOMIA and GEMATRIA from the Python Package index (PyPi) , make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/), then run:

    $ pip install momia


Users can import MOMIA and GEMATRIA just like other python packages in any IDE by running

    import MOMIA as mo
    
or:

    import GEMATRIA as gem

Tutorials for [MOMIA](https://github.com/jzrolling/MOMIA/blob/master/notebooks/MOMIA_workbench.ipynb) and [GEMATRIA](https://github.com/jzrolling/MOMIA/blob/master/notebooks/GEMATRIA_workbench.ipynb) are included in the folder [/notebooks](https://github.com/jzrolling/MOMIA/tree/master/notebooks) 

Please feel free to contact [me](juzhu@hsph.harvard.edu) if you have any issues (almost guaranteed) using MOMIA or GEMATRIA.

