# mqi_csharp
Early work of a C# adaptation of the [Machine Query Interface Python client](https://github.com/SWI-Prolog/packages-mqi/tree/master/python).

## Requirements
- Prolog with [MQI installed](https://github.com/SWI-Prolog/packages-mqi)
- Dotnet

Has been tested with:
- Windows 11 Pro 64 bit + SWI Prolog 8.4.3 + .net Version 6
- MacOS Monterey (Silicon) + SWI Prolog 8.4.3 + .net Version 6

But should also work with previous recent versions and on Linux.

## Getting started with command line
```
git clone https://github.com/sylvainlapeyrade/mqi_csharp.git
cd mqi_csharp
dotnet run
```

To use a dotnet version other than version 6, edit the "TargetFramework" field in the .csproj file with your dotnet runtime version. 
