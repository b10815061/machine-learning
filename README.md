# to use windows terminal on anaconda
https://dev.to/azure/easily-add-anaconda-prompt-in-windows-terminal-to-make-life-better-3p6j
## open setting.json of windows terminal
click on the down arrow at the left side of the bar and select setting

find "cmd.exe"
in list , create on for anaconda and type in :

"guid": "{0caa0dad-35be-5f56-a8ff-afceee452369}",
"name": "Anaconda",
"icon": "%USERPROFILE%\Anaconda3\Menu\anaconda-navigator.ico",
"commandline": "cmd.exe /K C:\Users\USERNAME\Anaconda3\Scripts\activate.bat",
"hidden": false
