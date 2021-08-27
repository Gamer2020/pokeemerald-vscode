# pokeemerald-vscode
These are files to add to your pokemerald project folder if you are using vscode. I decided to focus these files towards pokeemerad but the concepts should work for other GBA projects. The intention for this project is to help people starting out with Pokeemerald and VScosde. As time goes on I will add improvements, instructions, etc. Pull requests are welcome!

# Installation

Installation is simple. All you need to do is copy the ".vscode" folder for your OS to the root of your project.

# WSL

Please note that you will have to edit the folder location for mGBA to reflect your location. Please update the below line in the settings.json file.


```
"mgba_file": "\"/mnt/c/Program Files/mGBA/mGBA.exe\"",
```

For source level debugging, you will also need the arm-none-eabi-gdb.exe file from DevkitARM. Edit the below line in settings.json to match your location.

```
"gdb_file": "C:/Tools/arm-none-eabi-gdb/arm-none-eabi-gdb.exe",
```

# Linux

<div class="text-red">
Please note that somethings in these files are still a work in progress when it comes to linux. These are not expected to be working or done!
</div>
