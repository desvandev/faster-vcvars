# faster-vcvars
Batch script to setup environmental variables for Visual Studio compiler regardless of version<sub>[1](#uno)</sub> without having to use the infamous Developer Console

**Disclaimer:** This script can be rewritten to be 0.05ms faster ⚡. It has some unnecesary variable declarations to be more noob friendly.

## Usage
```cmd
::Inside cmd.exe
> faster-vcvars.bat 64
```
Change 64 to 32 if you need to compile to x86

## Example usage in VS Code

In tasks.json

![alt text](example.png "Logo Title Text 1")

###### Notes
<sub><a name="uno">1.</a> Until 2030</sub>

<sub>PS: Batch script is fun, you should try it!</sub> 🤙
