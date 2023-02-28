# PowerGUI Script Editor 3.8.0.129

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
 - In assemblies pane go to <executable name> \ Resources \ <executable name>.resources \ Scripts.zip
 - Save Script.zip file 
 - Extract file with 7-zip or similar program to recover original powershell file
 
 ![Image](./powergui-script-editor-1.png)
 
 NOTE: There's an option to add a password (to the zip file). In this case you need to crack the password, since it's not stored.
 
