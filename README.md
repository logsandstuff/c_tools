# C# and C++ tools
Compilation of both original and previously built C# and C++ tools for host recon, persistence, and exfiltration. All the code was optimized using Visual Studio 2019.

## Why use C#/C++?
Significantly lower detection rate by anti virus software. Windows Defender was able to detect a powershell script to obtain a reverse tcp shell even when encoded multiple times with various encryption methods. The unencrypted .exe file on the C# folder was not detected.

## HID deployment
In this folder you'll find standard payload to use with your favorite human interface device (HID), like rubber ducky, digispark boards programmed with arduino, Cactus WHID, etc. 

## Read more
*https://medium.com/@Bank_Security/undetectable-c-c-reverse-shells-fab4c0ec4f15
*https://gist.github.com/BankSecurity
*http://sh3llc0d3r.com/windows-reverse-shell-shellcode-i/


## Other fun tips

### Host a simple HTTP on your Linux machine 
This is great to easily download executable from here when you're troubleshooting locally. See examples below, just choose an unused port. Access file from http://xx.xx.xx.xx/1584/Documents/rev_c.exe
     
     python3 -m http.server 1584
     python2 -m SimpleHTTPServer 1584


### Guide to compile C# programs on Kali using mono
You know, just in case.
https://blog.didierstevens.com/2017/09/06/compiling-a-windows-service-with-mono-on-kali/



