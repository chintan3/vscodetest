# VScode terminal as node.js cmd
>it can work only 1.2.0 or higher and assume that vscode and node.js is installed 

1. create bat file   ` C:\Program Files\nodejs\npm-cmd.bat ` *(node installation folder)*
2. add text into bat file [for copy](https://raw.githubusercontent.com/chintan3/vscodetest/master/npm-cmd.bat) or `C:\Windows\System32\cmd.exe /k "C:\Program Files\nodejs\nodevars.bat"`
3.  goto `File > Preferences > workspace settings` select `settings.json` add given code  


`{
    // The path of the shell that the terminal uses on Windows.
    "terminal.integrated.shell.windows": "C:\\Program Files\\nodejs\\npm-cmd.bat"
}`

### Screenshot
![screenshot](https://raw.githubusercontent.com/chintan3/vscodetest/master/Capture.PNG) 
