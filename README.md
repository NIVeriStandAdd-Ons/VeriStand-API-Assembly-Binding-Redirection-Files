# VeriStand-API-Assembly-Binding-Redirection-Files

This repository contains configuration files used to force the LabVIEW Development Environment to load a specific version of the VeriStand .NET Assemblies. This can be required to successfully build and/or run LabVIEW code using the VS .NET API if multiple versions of VeriStand are installed.

Configuration files for LabVIEW 2015, 2016, 2017, and 2018 are installed via VI Package to *<Public Documents>\National Instruments\VeriStand LabVIEW .NET API Configuration files*. The specific year-version configuration file must be placed next to the LabVIEW.exe executable.

These configuration files can also be used to configure specific LabVIEW projects (.lvproj) or executables. To do so, rename the file to *your-labview-project.lvproj.config* and place the file next to the project.

To create configuration files for other versions of VeriStand use a text editor to replace the '20XX.X.X' string in any of included files to match the version and service pack number of the version you need to use.

For reference, the version strings for each VeriStand version are as follows:

2013: 2013.0.0<br>
2013 SP1: 2013.1.0<br>
2014: 2014.0.0<br>
2015: 2015.0.0<br>
2015 SP1: 2015.1.0<br>
2016: 2016.0.0<br>
2017: 2017.0.0.0<br>
2018: 2018.0.0.0<br>
2018 SP1: 2018.0.0.1<br>

<b>License Information</b><br>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.