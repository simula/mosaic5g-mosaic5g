# MOSAIC5G Ecosystem 
M5G is an ecosystem of opensource platforms and use-cases for 4G-5G R&D. 


A service delivery platform for 5G network across reusable software 

Mosaic-5G is composed of the following modules:

* The network Store 
* The JOX juju orchestrator
* The LL-MEC low latency MEC platform
* The FlexRAN and FlexCN real-time master controller
* The FlexRAN agent for monolitic and disaggregated RAN
* The FlexCN agent for  monolitic and disaggregated CN

This repository is designed to serve as a meta repository from where each 
submodules can be pulled. To get the code, simply clone this repository and 
from its main directory run

```
git submodule init
```

Then choose to load the appropriate submodule depending on the deployment node 
(agent or controller).

## Store 
For the jox directory, simply run:
```
git submodule update store
```
The source code of the jox  will be cloned from the appropriate repository
and can be found in the **store** directory.

## Jox juju orchestrator

For the jox directory, simply run:
```
git submodule update jox
```
The source code of the jox  will be cloned from the appropriate repository
and can be found in the **jox** directory.

## LL-MEC low latency MEC 

For the ll-mec, simply run:
```
git submodule update ll-mec
```
The source code of the ll-mec will be cloned and can be found in the 
**ll-mec** directory.

## FlexRAN and FlexCN real-time controller

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
**ran-agent** directory.

## FlexCN agent
For the FlexRAN agent simply run:
```
git submodule update agent
```
The source code of the agent will be cloned and can be found in the 
**cn-agent** directory.
