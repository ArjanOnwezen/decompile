# Win-PS2EXE

https://github.com/MScholtes/PS2EXE
Program to convert Powershell script to EXE.

Version(s) tested:
- 1.0.1.1

## Detect

Strings found
```

```

## Decompile

Tools required
 - [ILSpy](https://github.com/icsharpcode/ILSpy/releases)

Steps
 - Open executable (EXE) with ILSpy
 - In Assemblies pane go to `<executable name> \ Resources \ <executable name>.resources \ Scripts.zip`
 - Save Scripts.zip  
 - Extract Scripts.zip with 7-Zip or similar program to recover original powershell file
 
 ![Image](./win-ps2exe-1.png)
 
 NOTE: There's an option to add a password (to the zip file). In this case you need to crack the password, since it's not stored.
 


