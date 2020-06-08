# pokeemerald-vscode
These are files to add to your pokemerald project folder if you are using vscode. I decided to focus these files towards pokeemerad but the concepts should work for other GBA projects. As time goes on I will add improvements, instructions, etc. Pull requests are welcome!

# Windows

Please note that you will have to edit the folder location for mGBA in the tasks.json file. Simply find and replace the below.

```
"/mnt/c/DrivePrograms/mGBA/mGBA.exe"
```

For source level debugging, you will also need the arm-none-eabi-gdb.exe file from DevkitARM. Edit the below in launch.json to match your location.

```
"gdbpath": "C:/DrivePrograms/arm-none-eabi-gdb/arm-none-eabi-gdb.exe"
```
