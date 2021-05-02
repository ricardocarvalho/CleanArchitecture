# Clean Architecture Essencial - ASP .NET Core com C#
Principais conceitos relacionados com a Clean Architecture.

Boas práticas que aplicadas permitem criar aplicações ASP .NET Core com uma arquitetura limpa.  Os fundamentos apresentados baseiam-se na Clean Architecture que refere-se à organização do projeto de forma que seja fácil de entender e fácil de mudar conforme o projeto cresce. Isso não acontece por acaso. É preciso um planejamento intencional para que isso ocorra.

- Aplicado alguns dos conceitos DDD;
- Criado projeto para testes unitários - XUnit;
- Aplicado CQRS - Separando comandos (insert, update e delete) de consultas;
- Aplicado EF Core - Code-First.

A solução do projeto ficou dividido da seguinte forma:

- Domain: Onde ficam as regras de negócio;
- Application: Onde ficam regras de serviços.
- Infra.Data: Onde ficam a lógica para acessos a dados;
- Infra.IoC: Realiza a injeção de dependência. Permitindo o baixo acomplamento entre as camadas.
- WebUI: Representando a camada da aplicação.

![image](https://user-images.githubusercontent.com/5721182/116815990-8f8e8d80-ab36-11eb-8a9b-1e3c5840d9e5.png)

Fluxo de atendimento de uma solicitação da nossa aplicação. Uma visão global:

![image](https://user-images.githubusercontent.com/5721182/116816189-5571bb80-ab37-11eb-996f-1afb50b0d287.png)

Requisitos para o ambiente:
- .NET Core 5.0;
- Microsoft SQL Server 2019 Express - Edição gratuita do SQL Server;
- Visual Studio 2019 - Utilizado a versão 16.9.3.

![image](https://user-images.githubusercontent.com/5721182/116826155-02b0f780-ab69-11eb-9e44-e17140fac602.png)

![image](https://user-images.githubusercontent.com/5721182/116826172-14929a80-ab69-11eb-93ca-ba22e44efab8.png)

![image](https://user-images.githubusercontent.com/5721182/116826203-3b50d100-ab69-11eb-8f71-3308dc82de4a.png)


