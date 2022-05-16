# vcvarsForPS

# Use the Microsoft C++ toolset from PowerShell
This repository contains one Powershell script file, containing a function.
Run this script to export all Visual Studio's environment variables into your PowerShell session.

Example
------------
 
``` sh
./vcvars.ps1 -vcvarsbat "Path to visual studio /2022\Community\VC\Auxiliary\Build//vcvarsall.bat" -arch x64_arm64 
./vcvars.ps1 -vcvarsbat "Path to visual studio /2022\Community\VC\Auxiliary\Build//vcvarsall.bat" -arch x64 -platform_type store -winsdk_version  10.0.22000.0  

```

More Info
------------
https://docs.microsoft.com/en-us/cpp/build/building-on-the-command-line?view=msvc-170
https://help.appveyor.com/discussions/questions/18777-how-to-use-vcvars64bat-from-powershell
