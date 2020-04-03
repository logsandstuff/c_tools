# C# and C++ tools
Compilation of both original and previously built C# and C++ tools for host recon, persistence, and exfiltration. All the code was optimized using Visual Studio 2019.

## Why use C#/C++?
Significantly lower detection rate by anti virus software. Windows Defender was able to detect a powershell script to obtain a reverse tcp shell even when encoded multiple times with various encryption methods. The unencrypted .exe file on the C# folder was not detected.

## HID deployment
In this folder you'll find standard payload to use with your favorite human interface device (HID), like rubber ducky, digispark boards programmed with arduino, Cactus WHID, etc. 
