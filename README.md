Material for the 2018 computing methods in particle physics (CMPP) course at the University of Oxford. 

## Getting started

1. Install [Anaconda](https://conda.io/docs/user-guide/install/index.html)
2. Create, set up, and activate the environment
~~~
conda env create -n CMPP
source activate CMPP
# get required packages
conda install -n CMPP mkl-service numpy scipy ipython ipython-notebook matplotlib pandas pytables nose setuptools sphinx mpi4py seaborn pymc
conda install -n CMPP -c conda-forge pymc3
~~~

3. Deactive environment after you are don
~~~
source deactivate CMPP
~~~

