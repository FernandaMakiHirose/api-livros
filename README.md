# Como criar uma API em C# que retorne produtos de um e-commerce de livros
Iniciei o desenvolvimento de um e-commerce de livros, estruturando o projeto back-end e criando uma API de listagem de produtos.

## Requisitos
- Visual Studio
- Conhecimento em C# e .NET

## Licença
Distribuido sob a licença MIT License. Veja `LICENSE` para mais informações.

## Pacotes instalados no Visual Studio pelo NuGet 
- Basta clicar com o botão direito no projeto e adicionar pacotes pelo NuGet
- Pacotes usados: EntityFramework, Microsoft.EntityFrameworkCore, System.Linq, Microsoft.EntityFrameworkCore.InMemory (cria um banco de dados em memória no arquivo `Startup.cs`)

## Guia
- No arquivo `launchSettings.json` no `"launchUrl"` defina o nome da rota do projeto

Build:
>dotnet build

Executar o projeto:
>dotnet run
