# MOSAIC5G Ecosystem 
M5G is an ecosystem of opensource platforms and use-cases for 4G-5G R&D to build a service delivery platform across reusable software components. 

Mosaic-5G is composed of the following submodules:

* The network Store 
* The JOX juju orchestrator
* The LL-MEC low latency MEC platform
* The FlexRAN and FlexCN real-time master controller
* The FlexRAN agent-r for monolitic and disaggregated RAN
* The FlexCN agent-c for  monolitic and disaggregated CN

This repository is designed to serve as a meta repository from where each 
submodules can be pulled. To get the code, 
* Create account at (gitlab.eurecom.fr)[http://gitlab.eurecom.fr]
* Subscribe to [**Mosaic5G**](mailto:mosaic5g@lists.eurecom.fr) by clicking [subscribe](mailto:mailto:mosaic5g@lists.eurecom.fr?subject=subscribe mosaic5g YourGitAccount YourFirstName YourLastName)
* Clone this repository: 

```
git clone http://gitlab.eurecom.fr/mosaic5g/mosaic5g.git
```

* Run

```
git submodule init
```

Then choose to load the appropriate submodule depending on the deployment node 
(agent or controller). For more information about submodules, have a look at https://subfictional.com/fun-with-git-submodules/

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
For the FlexRAN agent-r simply run:
```
git submodule update agent-r
```
The source code of the agent will be cloned and can be found in the 
**agent-r** directory.

## FlexCN agent
For the FlexCN agent-c simply run:
```
git submodule update agent-c
```
The source code of the agent will be cloned and can be found in the 
**agent-c** directory.
