# Prerequirement

Please have BepInEx installed in your Lethal Company game folder

[BepInExPack](https://thunderstore.io/c/lethal-company/p/BepInEx/BepInExPack/) -> Manual Download

To install BepInExPack, you only need to extract the contents of BepInExPack that is the `BepInEx` folder, `doorstop_config.ini`, and `winhttp.dll`
into your game folder which is at the same level of the executable.

# Modpack installation

- go to your game folder
- open command prompt/terminal
- run the following commands in powershell
- do these shortcuts to open powershell

```
focus address bar of the folder: "Ctrl + L"
type "pwsh"
```

Then do

```
git clone https://github.com/dickynasje/KambingCompany.git --depth=1
Copy-Item -Force -Recurse KambingCompany\* BepInEx
```

- this will automatically download the mods in the plugins folder inside BepInEx
- and you should be set.

# Updating

- go into BepInEx folder
- open terminal
- run `git pull`
