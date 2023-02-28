# PowerGUI Script Editor 

Program to convert PowerShell script to EXE.

### Version(s) tested
- 3.8.0.129

## Detect

Strings found
```
Quest.PowerGUI.ScriptRunner
```

## Decompile

Tools required
 - [ILSpy](https://github.com/icsharpcode/ILSpy/releases)

Steps
 - Open executable (EXE) with ILSpy
 - In Assemblies pane go to `<executable name> \ Resources \ <executable name>.resources \ Scripts.zip`
 - Save Scripts.zip  
 - Extract Scripts.zip with 7-Zip or similar program to recover original powershell file
 
 ![Image](./powergui-script-editor-1.png)
 
 NOTE: There's an option to add a password (to the zip file). In this case you need to crack the password, since it's not stored.
 
