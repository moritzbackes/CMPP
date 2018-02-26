Material for the "**C**omputing **M**ethods in **P**article **P**hysics" (CMPP) course at the University of Oxford (Hilary term 2018). 

## Getting started

1. Install [Anaconda](https://conda.io/docs/user-guide/install/index.html)
~~~
# Make sure you have this in your ~/.bash_profile (or similar file)
PATH=$PATH:~/anaconda3/bin 

2. Create, set up, and activate the environment:
~~~
conda env create -n CMPP  # Do this only once for a given environment
source activate CMPP      # This needs to be done **every time** you open a new terminal
# get required packages (you only need to do this once unless you need new packages)
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
