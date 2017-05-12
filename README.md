# VeriStand-API-Assembly-Binding-Redirection-Files

This repository contains configuration files used to redirect .NET assembly version bindings at compile time or at run-time. Assembly version bindings can be scoped to an exectuable, a LabVIEW project, or the LabVIEW.exe executable itself.

The included configuration files must be renamed and placed in the same directory as the application or project being redirected.

For example, <b>LabVIEW.exe.config_Veristand_2015_0</b> should be renamed to <b>LabVIEW.exe.config</b> and placed alongside the LabVIEW.exe application to redirect assemblies in all projects opened by that version of LabVIEW.

In order to redirect the assemblies used in a specific project, rename <b>LabVIEW.exe.config_Veristand_2015_0</b> to <b><MyVeristandProject>.lvproj.config</b> and place the renamed file in the same directory as the project. 