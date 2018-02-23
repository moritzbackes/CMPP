Material for the "**C**omputing **M**ethods in **P**article **P**hysics" (CMPP) course at the University of Oxford (Hilary term 2018). 

## Getting started

1. Install [Anaconda](https://conda.io/docs/user-guide/install/index.html)

2. Create, set up, and activate the environment:
~~~
conda env create -n CMPP
source activate CMPP
# get required packages
conda install -n CMPP mkl-service numpy scipy ipython ipython-notebook matplotlib pandas pytables nose setuptools sphinx mpi4py seaborn pymc
conda install -n CMPP -c conda-forge pymc3
~~~

3. Clone the CMPP git repository
~~~
git clone https://github.com/moritzbackes/CMPP.git
~~~

4. Open a Jupyter notebook:
~~~
cd CMPP
jupyter notebook
~~~

5. Deactive environment after you are done:
~~~
source deactivate CMPP
~~~

Credits: The course material is based on a previous CMPP course given by [Matthew Bass](https://github.com/mibass/CMPP/)
