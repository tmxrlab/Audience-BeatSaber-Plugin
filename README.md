# Audience-BeatSaber-Plugin
*Plugin for [Beat Saber](http://beatsaber.com/)*

* Plugin made by TMXRLAB
* You can always find the latest Download in the [releases](https://github.com/tmxrlab/Audience-BeatSaber-Plugin/releases)


## Features
* Disable Camera Noise
* Disable global particle haze
* Configure note slash particle amount, lifetime and size

## Usage
You can either configure the plugin by editing `UserData\ParticleOverdrive.ini`, but the preferred method of configuration is using the in-game settings menu.  

## Thanks
* **SkyKiwi** // Creating ChromaToggle, the mod that inspired this mod. (I also used some of it's code as a starting point `<3`)

## Developers

### Contributing to ParticleOverdrive
In order to build this project, please add a `ParticleOverdrive.csproj.user` file in the project directory and specify where your game is located on your disk:

```xml
<?xml version="1.0" encoding="utf-8"?>
<Project xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
  <PropertyGroup>
    <!-- Change this path if necessary. Make sure it ends with a backslash. -->
    <GameDirPath>C:\Program Files\Steam\steamapps\common\Beat Saber\</GameDirPath>
  </PropertyGroup>
</Project>
```
