# Subscribe and Get the MOSAIC5G Ecosystem  
M5G is an ecosystem of opensource platforms and use-cases for 4G-5G R&D to build a service delivery platform across reusable software components. 

Mosaic-5G is composed of the following submodules:

* The network Store 
* The JOX juju orchestrator
* The LL-MEC low latency MEC platform
* The FlexRAN and FlexCN real-time master controller
* The FlexRAN agent-r for monolitic and disaggregated RAN
* The FlexCN agent-c for  monolitic and disaggregated CN

This repository is designed to serve as a meta repository from where each 
submodules can be pulled. Follow the instructions below to get the modules and build your platform.


1. Create a gitlab account at [gitlab.eurecom.fr](http://gitlab.eurecom.fr) page, and follow the instructions to create a user acount.

1. Subscribe to [**Mosaic5G**](mailto:mosaic5g@lists.eurecom.fr) by clicking at [subscribe](mailto:mailto:mosaic5g@lists.eurecom.fr?subject=subscribe mosaic5g YourGitAccount YourFirstName YourLastName) and replace the following placeholders "YourGitAccount" "YourFirstName" "YourLastName"

1. Clone this repository:  `git clone http://gitlab.eurecom.fr/mosaic5g/mosaic5g.git`

1. Build your service delivery platform
    * From Snap: `./build_m5g `
    * From Source: `./build_m5g `



    The above modules can be also manually updated as explaing below. You may also check the build_m5g script 

    1. Inititialize all the Mosaic5G modules:  ```git submodule init``` 
    1. Load manually the appropriate submodule depending on the deployment node (e.g. ll-mec, agent-r, controller). The source code of each  submodule will be cloned from the appropriate repository and can be found in its respective directory. For more information about git submodules, have a look at https://subfictional.com/fun-with-git-submodules/
        
        * **Network store**:        ```git submodule update store; ```
        * **JoX Juju Orchestrator** : ```git submodule update jox ```
        * **LowLatency MEC**:  ```git submodule update ll-mec```
        * **FlexRAN Realtime Controller**: ```git submodule update controller```
        * **FlexRAN RAN Agent**: ```git submodule update agent-r```
        * **FlexRAN CN Agent**: ```git submodule update agent-c```
