# MOSAIC-5G
A platform for Software-Defined Radio Access Networks

Mosaic-5G is composed of the following modules:

* The JOX juju orchestrator
* The FlexRAN real-time master controller
* The FlexRAN agent running at the eNodeB
* The LL-MEC low latency MEC platform

This repository is designed to serve as a meta repository from where each 
submodules can be pulled. To get the code, simply clone this repository and 
from its main directory run

```
git submodule init
```

Then choose to load the appropriate submodule depending on the deployment node 
(agent or controller).

## Jox juju orchestrator

For the jox directory, simply run:
```
git submodule update jox
```
The source code of the jox  will be cloned from the appropriate repository
and can be found in the **jox** directory.

## FlexRAN real-time controller

For the FlexRAN controller simply run:
```
git submodule update controller
```
The source code of the controller will be cloned from the appropriate repository
and can be found in the **controller** directory.

## FlexRAN agent
For the FlexRAN agent simply run:
```
git submodule update agent
```
The source code of the agent will be cloned and can be found in the 
**agent** directory.

## LL-MEC low latency MEC 

For the ll-mec, simply run:
```
git submodule update ll-mec
```
The source code of the ll-mec will be cloned and can be found in the 
**ll-mec** directory.
