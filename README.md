# Clean Architecture Essencial - ASP .NET Core com C#
Principais conceitos relacionados com a Clean Architecture.

Boas práticas que aplicadas permitem criar aplicações ASP .NET Core com uma arquitetura limpa.  Os fundamentos apresentados baseiam-se na Clean Architecture que refere-se à organização do projeto de forma que seja fácil de entender e fácil de mudar conforme o projeto cresce. Isso não acontece por acaso. É preciso um planejamento intencional para que isso ocorra.

A solução do projeto ficou dividido da seguinte forma:

- Domain: Onde ficam as regras de negócio;
- Application: Onde ficam regras de serviços.
- Infra.Data: Onde ficam a lógica para acessos a dados;
- Infra.IoC: Realiza a injeção de dependência. Permitindo o baixo acomplamento entre as camadas.
- WebUI: Representando a camada da aplicação.

![image](https://user-images.githubusercontent.com/5721182/116815990-8f8e8d80-ab36-11eb-8a9b-1e3c5840d9e5.png)

- Aplicado alguns dos conceitos DDD;
- Criado projeto para testes unitários - XUnit;
- Aplicado CQRS - Separando comandos (insert, update e delete) de consultas;
- Aplicado EF Core - Code-First.

Requisitos para o ambiente:
.NET Core 5.0;
Microsoft SQL Server 2019 Express - Edição gratuita do SQL Server;
Visual Studio 2019 - Utilizado a versão 16.9.3.
