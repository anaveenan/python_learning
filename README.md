# Python Learning  

## 1)Managing Packages 

Once you have Anaconda installed, managing packages is fairly straightforward.To install a package, type conda install package_name in your terminal. For example, to install numpy, type conda install numpy.
```
conda install numpy scipy pandas #will install all those packages simultaneously
conda install numpy=1.10
conda remove package_name #To unistall
conda update package_name #To update a package
conda update --all #To update all packages
conda list #To list installed packages
```

## 2)Managaging Environment 

To create an environment, use conda create -n env_name list of packages in your terminal. Here -n env_name sets the name of your environment (-n for name) and list of packages is the list of packages you want installed in the environment. For example, to create an environment named my_env and install numpy in it, type conda create -n my_env numpy

```
conda create -n py python=3.3
conda create -n py2 python=2
source activate my_env
source deactivate 
conda env export > environment.yaml
conda env create -f environment.yaml
conda env list  #to list out all the environments you've created
conda env remove -n env_name
```
## 3)Setting Up Sublime Editor

Setting up virtual environment for sublime text editor is done by following the instruction [in] (https://inkdroid.org/2015/05/05/virtualenv-builds-in-sublime-text-3/)

/Users/narjunan/anaconda3/envs/py3
