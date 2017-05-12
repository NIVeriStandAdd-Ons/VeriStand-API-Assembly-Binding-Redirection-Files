# VeriStand-API-Assembly-Binding-Redirection-Files

This repository contains configuration files used to redirect .NET assembly version bindings at compile time or at run-time. Assembly version bindings can be scoped to an exectuable, a LabVIEW project, or the LabVIEW.exe executable itself.

To create configuration files for other versions of VeriStand use a text editor to replace the '20XX.X.X' string in any of included files to match the version and service pack number of the version you need to use.

For reference, the version strings for each VeriStand version are as follows:

2013 : 2013.0.0<br>
2013 SP1 : 2013.1.0<br>
2014 : 2014.0.0<br>
2015 : 2015.0.0<br>
2015 SP1 : 2015.1.0<br>
2016 : 2016.0.0<br>

The included configuration files must be renamed and placed in the same directory as the application or project being redirected.

For example, <b>LabVIEW.exe.config_Veristand_2015_0</b> should be renamed to <b>LabVIEW.exe.config</b> and placed alongside the LabVIEW.exe application to redirect assemblies in all projects opened by that version of LabVIEW.

In order to force a particular project to use assemblies for VeriStand 2015, for example, rename <b>LabVIEW.exe.config_Veristand_2015_0</b> to <b><i>MyVeristandProject</i>.lvproj.config</b> and place the renamed file in the same directory as the project file. 

<b>License Information</b><br>
Copyright 2017 National Instruments

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.