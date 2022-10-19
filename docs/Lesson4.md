## Lesson 4: Visualization in OpenCascade
* Whereas in Lesson 2, VTK was used for display (OpenCascade was installed in a way that allowed it to have a "bridged" connection to VTK), in this lesson, we are using AIS for display.
* Going through this now in Windows 10 using Visual Studio, this tutorial teaches the details of configuring using the Visual Studio properties interface.

```
Configuration for Lesson4
(lines are joined into one line using semicolon ';' separators)

C/C++
	General
		Addditional Include directories:

C:\Users\doug\occ\opencascade-install\inc
%(AdditionalIncludeDirectories)



Linker
	General
		Additional Library Directories:

C:\Users\doug\occ\opencascade-install\win64\vc14\libd
%(AdditionalLibraryDirectories)



Linker
	Input
		Additional Dependencies:

TKernel.lib
TKMath.lib
TKTopAlgo.lib
TKBRep.lib
TKPrim.lib
TKOpenGL.lib
TKV3d.lib
TKService.lib
kernel32.lib
user32.lib
gdi32.lib
winspool.lib
%(AdditionalDependencies)


Debugging
	environment:

PATH=C:\Users\doug\occ\opencascade-install\win64\vc14\bind
C:\Users\doug\occ\products\freetype-2.5.5-vc14-64\bin
%PATH%$(LocalDebuggerEnvironment)
```


