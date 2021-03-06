# LinkerGenerator [![openupm](https://img.shields.io/npm/v/com.kuraiandras.linkergenerator?label=openupm&registry_uri=https://package.openupm.com)](https://openupm.com/packages/com.kuraiandras.linkergenerator/)

An editor utility which will generate a link.xml file with the press of a button

![Window Menu](/.github/images/WindowMenu.png)

The plugin can find all added dlls and compiled scripting assemblies and generate a link.xml file which will preserve all of them.

.RSP files will also be scanned, and assemblies preceded by the "-r:" mark can be found.

You can customize the generation in the project settings

![Project Settings](/.github/images/ProjectSettings.png)

The settings are saved in the Assets folder, and should be checked in to source control.

# Installation

The recommended way of installation is through open upm.

```pwsh
openupm add com.kuraiandras.linkergenerator
```

You also can manually install with UPM through git.

You can also install manually with a .unitypackage which can be found under releases
