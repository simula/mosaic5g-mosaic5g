# Subscribe and Get the MOSAIC5G Ecosystem  
M5G is an ecosystem of opensource platforms and use-cases for 4G-5G R&D to build a light-weight 5G service delivery platform across reusable software components. 

Mosaic-5G is composed of the following submodules:

* The network Store 
* The JOX juju orchestrator
* The LL-MEC low latency MEC platform
* The FlexRAN for real-time master controller
* The OAI-RAN for monolitic and disaggregated RAN
* The OAI-CN  for monolitic and disaggregated CN

This repository is designed to serve as a meta repository from where each 
submodules can be pulled. Follow the instructions below to get the modules and build your platform.


1. Read, sign, and send the [terms of use]()

1. Create a gitlab account at [gitlab.eurecom.fr](http://gitlab.eurecom.fr) page, and follow the instructions to create a user acount.

1. Subscribe to [**Mosaic5G**](mailto:mosaic5g_users@lists.eurecom.fr) by clicking at [subscribe](mailto:mailto:mosaic5g_users@lists.eurecom.fr?subject=subscribe mosaic5g_users YourGitAccount YourFirstName YourLastName) and replace the following placeholders "YourGitAccount" "YourFirstName" "YourLastName"

1. Clone this repository:  `git clone http://gitlab.eurecom.fr/mosaic5g/mosaic5g.git`

1. Build all the platforms 
    * From Source: `./build_m5g -m `
1. Buil specific platform
    * FlexRAN: `./build_m5g -f `
    * LL-MEC: `./build_m5g -l `
    * JOX: `./build_m5g -j `
    * STORE: `./build_m5g -s `
    * OAI-RAN: `./build_m5g -r `
    * OAI-CN: `./build_m5g -c `
1. Check the help of build_m5g:
    * `./build_m5g -h `


For manual operation, please have a look at the build_m5g script.
