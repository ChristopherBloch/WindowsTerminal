# Settings.json commandline I can use

SSH via CMD:
-----------------------------------------------
"commandline": "cmd.exe /c ssh -p 22 guest@192.168.1.1",

SSH:
-----------------------------------------------
"commandline": "ssh -p 22 guest@192.168.1.1 sh run.sh",

WSL custom:
-----------------------------------------------
{

    "name": "MyUbuntu",
    
    "commandline" : "wsl -d MyUbuntu",
    
    "startingDirectory" : "//wsl$/Ubuntu/home/ubuntu"
    
},

WSL:
-----------------------------------------------
{

    "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
    
    "hidden": false,
    
    "name": "Ubuntu",
    
    "source": "Windows.Terminal.Wsl"
    
}
