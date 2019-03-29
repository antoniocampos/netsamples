# Multi-Targeting and Porting a .NET Library to .NET Core 2.0
This solution has 3 projects
[LibExemplo](https://github.com/antoniocampos/dotnetsamples/tree/master/MultiTarget/LibExemplo) -> Compiles both to .net Full Framework 4.0 and .net Standard 2
[ConsoleApp1CORE](https://github.com/antoniocampos/dotnetsamples/tree/master/MultiTarget/ConsoleApp1CORE) -> References LibExemplo and consumes it as Net Standard
[ConsoleApp1NET40](https://github.com/antoniocampos/dotnetsamples/tree/master/MultiTarget/ConsoleApp1NET40) -> References LibExemplo and consumes it as Full Framework