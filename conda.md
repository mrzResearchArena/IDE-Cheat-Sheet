#### 1. Conda activate and deactivate

```console
user@machine:~$ conda activate                 -->    ### activate
(base) mrz@rafsanjani:~$ conda deactivate      -->    ### deactivate
```

#### 2. View all environment
```console
user@machine:~$ conda env list

# conda environments:
#
base                  *  /home/user/anaconda3
deep                     /home/user/anaconda3/envs/deep
deepPro                  /home/user/anaconda3/envs/deepPro
learning                 /home/user/anaconda3/envs/learning
```

#### 3. How to handle an anaconda virtual environment?

##### Step 1: Create a virtual environment ####
```console
rafsanjani@mrz:~$ conda create -n anyName python=3.x anaconda
```

##### Step 2: Entering the virtual environment ####
```console
rafsanjani@mrz:~$ source activate anyName
```

##### Step 3: Detach from the virtual environment ####
```console
rafsanjani@mrz:~$ source deactivate
```

##### Step 4: Remove an user from virtual environment ####
```console
rafsanjani@mrz:~$ conda env remove --name anyName
```

#### 4. Update / Remove:
```console
user@machine:~$ conda update conda
user@machine:~$ conda update anaconda
user@machine:~$ conda update spyder

user@machine:~$ conda update qt pyqt
user@machine:~$ conda install spyder=3.3.6

user@machine:~$ conda update --all
user@machine:~$ conda clean --yes --all
```
