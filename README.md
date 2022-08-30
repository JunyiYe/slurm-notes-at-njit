# Slurm Tutorial at NJIT

## Project Description
The repo introduces you to how to use Slurm for data science at NJIT cluster Lochness. NJIT has already published a [wiki](https://wiki.hpc.arcs.njit.edu/index.php/HPC_and_BD). However, it was not well documented. This repo includes more detailed examples for data science, especially for creating your Python scientific environments, GPU training, using Jupyter Lab, etc. **Feel free to star this project if you find it helpful!**


## Table of Contents
1. [Project Description](## Project Description)
2. [Assumputio](### Assumpution)
3. [Slurm Basics](## Slurm Basics)
4. [Log in](#### Log in)

### Assumpution
We assume the username of your account is **jy666** all across the project. (You can replace **jy666** with your username.)

## Slurm Basics
### Log in
Open a terminal (Command Prompt on Windows; terminal on Mac or Linux) and connect the cluster with the **ssh** command. Then typing the password of your account.
```
ssh jy666@lochness.njit.edu
```

### Log out
You can type "logout" ("lo") or "exit" to close the connection with the cluster.
```
lo
```
or
```
logout
```
or
```
exit
```


## Reference
1. [NJIT High Performance Computing (HPC) and Big Data (BD) Wiki](https://wiki.hpc.arcs.njit.edu/index.php/HPC_and_BD)
2. [HPC-UiT Services User Documentation](https://hpc-uit.readthedocs.io/en/latest/index.html)
