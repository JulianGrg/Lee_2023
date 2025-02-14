# PLP_directRNA_design
Package used to create padlock probes that target RNA directly. It can be used for any gene and species.

## Installation

Installation should be done on a Linux system. You can do this either by using a Linux emulator, or a VM if you use other OS.

* First, install cutadapt:
    `sudo apt install clustalw`
* Create an environment using conda:

    `conda create --name probedesign python==3.9`

* Activate env:

    `conda activate probedesign`

* Install cutadapt

    `pip install cutadapt`

* Install the package: 

    `python setup.py install`

* Install further required libraries:

    ```
    conda install -c conda-forge jupyterlab
    conda install -c conda-forge biopython=1.80
    conda install -c conda-forge pandas=1.5.3
    conda install -c conda-forge matplotlib
    ```