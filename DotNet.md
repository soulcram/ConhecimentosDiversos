Dica para listar todos os templates disponíveis:

dotnet new --list

com filtro, ex:

dotnet new --list web

|Tipo	| Comando (template)	| Descrição |
|-----------|---------|-----------------|
|Aplicativo de Console	| dotnet new console	| Cria uma aplicação básica de linha de comando. |
|Biblioteca de Classes	| dotnet new classlib	| Cria uma DLL (.NET class library). |
|Aplicação Web (MVC)	| dotnet new mvc	| Cria uma aplicação ASP.NET Core MVC. |
|Web API	| dotnet new webapi	| Cria uma API REST com ASP.NET Core. |
|Aplicação Web vazia	| dotnet new web	| Cria uma aplicação web ASP.NET Core sem MVC. |
|Aplicação Razor	| dotnet new razor	| Cria um site com Razor Pages. |
|Aplicação Blazor (Server)	| dotnet new blazorserver	| Blazor com renderização no servidor. |
|Aplicação Blazor (WASM)	| dotnet new blazorwasm	| Aplicação SPA (WebAssembly) com C#. |
|Aplicação MAUI	| dotnet new maui	| Aplicação multiplataforma (Android/iOS/Desktop). Requer .NET MAUI configurado. |
|Projeto de Testes	| dotnet new xunit	| Projeto de testes com xUnit. |
|Solução (.sln)	| dotnet new sln	| Cria um arquivo de solução (como no Visual Studio). |

exemplo de uso -> dotnet new console -n AprendendoDotNet
