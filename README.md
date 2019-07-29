
<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# Variable Rename Module
The Cortex Variable Rename module focuses on the updating of variable names within a flow or subtask, both when the variables are declared in the variable store and when they are referred to in block properties. After performing the rename the flow or subtask should function in the exact same manner as it did beforehand.

For example, the module could be used by a flow author who wishes to update a flow with ambiguously or vaguely named variables to have names that may be more meaningful to another author. Another common use may be to follow Cortex Best Practices by adding a subtask’s acronym to the front of each variable it uses.



## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other)
2) [Installation](#installation)
3) [How to use](#how-to-use)
4) [How you can contribute](#how-you-can-contribute)
5) [Versioning](#versioning)
6) [Licensing](#licensing)


## Dependencies
### Cortex Version
This version of the Variable Rename module was developed in Cortex version 6.5. Some functionality may not be available on different versions of Cortex.

### OCIs
The  module requires the following Cortex OCIs:
* PowerShell
* HTTP

### Files
The Variable Rename module requires the following files:
* [CTX-Variable-Rename.studiopkg](https://github.com/CortexIntelligentAutomation/CTX-Variable-Rename/releases/download/v1.0/CTX-Variable-Rename.studiopkg)

### Other
None

## Installation
Details of the installation can be found in the [Variable Rename Deployment Plan](https://github.com/CortexIntelligentAutomation/CTX-Variable-Rename/blob/master/CTX-Variable-Rename%20Deployment%20Plan.pdf).
## How to use
A detailed User Guide has been provided with instructions on how to use the flows, available [here](https://github.com/CortexIntelligentAutomation/CTX-Variable-Rename/blob/master/CTX-Variable-Rename%20User%20Guide.pdf). Configuration of subtask inputs and outputs are detailed in notes on the subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
Variable Rename has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.0 | 21/05/2019 | CVR-Rename-Variables | Created
v1.0 | 21/05/2019 | CVR-Select-Variables-To-Update | Created


## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2019 Cortex Ltd

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
