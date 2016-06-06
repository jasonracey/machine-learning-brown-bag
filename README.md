# Machine Learning Lab
This repository contains the files and instructions required to get set up to participate in an interactive machine learning lab exercise.

### Getting Started (Linux and Mac OSX)
1. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
1. Download and install [Vagrant](https://www.vagrantup.com/downloads.html)
1. Create a Vagrant directory  
```=> mkdir ~/Vagrant```
1. Download [Vagrantfile](https://github.com/jasonracey/machine-learning-lab/blob/master/Vagrantfile) from this repository into your Vagrant directory
1. Start Vagrant (might take a few minutes the first time)  
```=> vagrant up --provider=virtualbox```
1. Download [machine-learning-lab.ipynb](https://github.com/jasonracey/machine-learning-lab/blob/master/machine_learning_lab.ipynb) from this repository to any local directory
1. Navigate to the [Jupyter Notebook](http://localhost:8001/) running in your VirtualBox VM
1. Click the Upload button (top right) and upload the machine-learning-lab.ipynb file you just downloaded
1. Click on the machine-learning-lab.ipynb link to run the notebook
