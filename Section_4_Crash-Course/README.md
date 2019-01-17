# Notes for Section 4 Crash Course

## Managing virtual environments using Anaconda
http://conda.pydata.org/docs/using/envs.html 

The [virtualenv](https://virtualenv.pypa.io/en/latest/)  library can also accomplish this.

### Create Virtual Environment

Command: conda create --name

Arguments:
* Name you want to give to virtual environment 
* Package to initiate environment with **without a package to initiate with there could be an error**

conda create --name snowflakes biopython

To active / de-activate environment on a Mac use:
* source activate [environment name]
* source deactivate [environment name]

### List All Virtual Environments

* conda --info envs



 
