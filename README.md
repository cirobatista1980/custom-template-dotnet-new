# custom-template-dotnet-new
> Projeto para criar templates personalizadas para o **dotnet new**


Este projeto visa exemplificar a criação de templates personalizadas para serem utilizadas na ferramenta cli do dotnet, mais especificamente no comando dotnet new.

## Instalação
**1** - No diretório principal do projeto executar o comando 
            `dotnet pack -o .\nuspec`
        Onde `.\nuspec` é o caminho em que será gerado o pacote Nuget com a template

**2** - Executar o comando 
            `dotnet new -i .\nuspec\Custom.Template.1.0.0.nupkg`

## Utilização
> `dotnet new CustomTemplate --name Custom.Template -o ./NovaPasta`
        `--name` será o nome que a template ira assumir incluindo todos os namespaces
        `-o` local que o projeto será criado 
