# mqi_csharp
Early work of a C# adaptation of the [Machine Query Interface Python client](https://github.com/SWI-Prolog/packages-mqi/tree/master/python) to interface a C# (including Unity) application with a SWI-Prolog engine.

The code functions for my specific use case, but please note that it is not optimized and comes without any guarantees or warranties

## Requirements
- [.NET](https://dotnet.microsoft.com/en-us/download)
- [Swi-Prolog](https://www.swi-prolog.org/download/stable)
- [The MQI SWI-Prolog package](https://github.com/SWI-Prolog/packages-mqi)

Has been tested with:
- Windows 11 Pro + SWI-Prolog 9.0.4 + .NET Version 6/7
- MacOS Sillicon Sonoma + SWI-Prolog 9.0.4 + .NET Version 6/7

But should also work on Linux and with some earlier and more recent versions of .NET and SWI-Prolog.

## Getting started with command line
```
git clone https://github.com/sylvainlapeyrade/mqi_csharp.git
cd mqi_csharp
dotnet run
```

To use a .NET version other than 7, modify the "TargetFramework" field in the [PrologMachineQueryInterface.csproj](PrologMachineQueryInterface.csproj) file to match your .NET runtime version.
