# INIFile.cs
Provides basic functions for working with INI files in Visual C#.

## Quick Start

First, download the file INIFile.cs and add it to your Visual Studio solution.
Make sure, you can access the INIFile namespace by adding following code:
```
using Nocksoft.IO.ConfigFiles;
```

Then, you can create a new instance and pass the path to the INI file as a parameter:
```
INIFile iniFile = new INIFile("file.ini");
```

To save a value in the INI file, call the following method and pass three parameters:
```
iniFile.SetValue("section", "key", "value");
```

To read a value from the INI file, call the following method and pass two parameters:
```
string value = iniFile.GetValue("section", "key");
```

Please note that sections and keys are not case-sensitive.

## Need more information?
For more information see the official documentation (german): https://nocksoft.de/tutorials/visual-c-sharp-arbeiten-mit-ini-dateien/
