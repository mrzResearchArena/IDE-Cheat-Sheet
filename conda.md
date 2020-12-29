#### 0. Download Anaconda:
- ##### Step 1: Go to the [website](https://www.anaconda.com/products/individual), and download
- ##### Step 2: Verify the `anyName.bash` file
  ```console
  user@machine:~$ sha256sum anyName.bash
- ##### Step 3: Install
  ```console
  user@machine:~$ bash anyName.bash
  ```
Help: [Installing on Linux](https://docs.anaconda.com/anaconda/install/linux/)

&nbsp;

#### 1. Conda activate and deactivate

```console
user@machine:~$ conda activate                 -->    ### activate
(base) mrz@rafsanjani:~$ conda deactivate      -->    ### deactivate
```

&nbsp;

#### 2. View all environment
```console
user@machine:~$ conda env list
user@machine:~$ conda info --envs

# conda environments:
#
base                  *  /home/user/anaconda3
deep                     /home/user/anaconda3/envs/deep
deepPro                  /home/user/anaconda3/envs/deepPro
learning                 /home/user/anaconda3/envs/learning
```

&nbsp;

#### 3. How to handle an anaconda virtual environment?

##### Step 1: Create a virtual environment ####
```console
user@machine:~$ conda create -n anyName python=3.x anaconda   # x={6,7,8}
```

##### Step 2: Entering the virtual environment ####
```console
user@machine:~$ conda activate anyName
```

##### Step 3: Detach from the virtual environment ####
```console
user@machine:~$ conda deactivate
```

##### Step 4: Remove an user from virtual environment ####
```console
user@machine:~$ conda env remove --name anyName
```


##### Step 5: Rename anaconda virtual environment ####
```console
user@machine:~$ conda create --name newName --clone oldName
user@machine:~$ conda remove --name oldName --all
```

&nbsp;


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
