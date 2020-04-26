# C# and C++ tools
Compilation of both original and previously built C# and C++ tools for pentesting. The C# code was optimized and compiled using Visual Studio 2019.

## Why use C#/C++?
Significantly lower detection rate by anti virus software. Windows Defender was able to detect a powershell script to obtain a reverse tcp shell even when encoded multiple times with various encryption methods. The unencrypted .exe file on the C# folder was not detected.

## HID deployment
In this folder you'll find standard payload to use with your favorite human interface device (HID), like rubber ducky, OMG cable, digispark boards programmed with arduino, Cactus WHID, etc. 

## Read more

https://medium.com/@Bank_Security/undetectable-c-c-reverse-shells-fab4c0ec4f15

https://gist.github.com/BankSecurity


## Other fun tips

### Host a simple HTTP on your Linux machine 
This is great to easily download executables to your target machine when you're troubleshooting locally. See examples below, just choose an unused port (here I show it using the IP 10.0.0.20 and the port 1584 as an example). Access file from http://10.0.0.20/1584/Documents/rev_c.exe
     
     python3 -m http.server 1584
     python2 -m SimpleHTTPServer 1584


### Guide to compile C# programs on Kali using mono
You know, just in case.

https://blog.didierstevens.com/2017/09/06/compiling-a-windows-service-with-mono-on-kali/



