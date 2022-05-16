# vcvarsForPS

Run this script to export all Visual Studio's environment variables into PowerShell.

Usage
------------
 
``` sh
.\vcvars.ps1 -vcvarsbat "Path to visual studio /2022\Community\VC\Auxiliary\Build//vcvarsall.bat" -arch x64_arm64 
.\vcvars.ps1 -vcvarsbat "Path to visual studio /2022\Community\VC\Auxiliary\Build//vcvarsall.bat" -arch x64 -platform_type store -winsdk_version  10.0.22000.0  

```
