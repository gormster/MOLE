
**MOLE** is being designed as an **OpenSource**  editor for **Super Mario World** with the intent to bring many of the features from existing SMW ROMHacking tools/patches such as **Lunar Magic**, **Asar**, **Pixi**, **YYCHR**, **GPS**, **UberASM**,  **SA-1**, and many others into a single easy-to-use [**multi-platform**](#how-to-run) tool localized/translated by volunteers to [some common languages](#localizationtranslation)
___
### How to Run
At the moment MOLE is still in a very early stage and therefore no public releases have been setup, however in the near future you will be able to use MOLE on their specific platform trough one of the following methods:
- Windows Users can download and run one of our WinForms Releases
- ...
- MOLE Is also available [online]() as a WebApp (Read [this]() for how to run locally)

If you still insist on running MOLE in its current very early stages, read the following section on how to build it yourself.
___
### How to Build
	(SECTION WIP)

    #### macOS

    WIP. For now, this is just going to be instructions for building the Back executable.

    ##### Dependencies
    1. Install [mono](https://www.mono-project.com/download/stable/)
    2. Run `nuget install -OutputDirectory packages` in the src/Back directory.
    3. Download and build [ASAR](https://github.com/RPGHacker/asar).
    4. Copy libasar.dylib to the src/Back/packages directory. (TODO: is there a better way to do this?)

    ##### Build
    Just run `msbuild` in the src/Back directory. Then you can run `./bin/Debug/Back`.
___
### Localization/Translation
	(SECTION WIP)
___
### Contribute
Please read [these guidlines](/CONTRIBUTING.md) if you want to contribute to MOLE.
___
### Project Structure
```
•─ azure/
	•─ Azure Pipelines.
•─ res/
	•─ Icons, Images, Text KeyTables (for localization/translation), etc...
•─ src/
	•─ Source Files
	•─ Back/
		•─ .NET Framework 4.8 Backend DLL containing most of the important MOLE editing code.
	•─ Win/
		•─ .NET Framework 4.8 Winforms UI Frontend.
```
___
### More information on SMW ROMHacking and MOLE
You can find a lot of useful information about MOLE, Lunar Magic, SMW Romhacking, and SNES development in general, in the [Useful Links](/wiki/useful-links) Section of the [MOLE Wiki](/wiki)
___
### License
This software is licensed under the [GNU General Public License v3.0](/LICENSE.md)
