# DESAFIO | MegaApiDotnetCore

> Este projeto é parte do Desafio de Projeto do Bootcamp DIO.ME sobre "Documentação e Versionamento de Projetos com IAs". Baseado no projeto original [MegaApiDotnetCore](https://github.com/FelipeAguiarCode/MegaApiDotnetCore) desenvolvido por [Felipe Aguiar](https://github.com/FelipeAguiarCode).

<div align="center">
  <img src="MegaApiDotnetCore/_docs/assets/icon_megaman.png" alt="Mega Man Robot IA" width="150">
</div>

<div align="center">
  <img src="https://img.shields.io/badge/.NET%20Core-6.0-blue" alt="NET Core Version">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow" alt="Status">
</div>

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Pré-requisitos](#-pré-requisitos)
- [Como Executar](#-como-executar)
- [Endpoints da API](#-endpoints-da-api)
- [Contribuição](#-contribuição)
- [Licença](#-licença)

## 📄 Sobre o Projeto

O Projeto faz parte do LAB-Desafio da DIO.ME "Documentando Projetos Automáticos Utilizando IA".
O MegaApiDotnetCore é uma API RESTful desenvolvida em .NET Core, que implementa um sistema robusto e escalável utilizando as melhores práticas de desenvolvimento. O projeto segue uma arquitetura limpa e modular, facilitando a manutenção e expansão do código.

## 🚀 Tecnologias Utilizadas

- **.NET Core 6.0**
- **ASP.NET Core**
- **Entity Framework Core**
- **Swagger/OpenAPI**
- **SQL Server**

## 📁 Estrutura do Projeto

```
src/
├── Controllers/     # Controladores da API
├── Models/         # Modelos de dados
├── Services/       # Lógica de negócios
├── Database/       # Configurações do banco de dados
├── Middlewares/    # Middlewares personalizados
└── Properties/     # Configurações do projeto
```

## 📋 Pré-requisitos

- .NET Core SDK 6.0 ou superior
- SQL Server (local ou remoto)
- Visual Studio 2022 ou VS Code

## ⚙️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/MegaApiDotnetCore.git
```

2. Navegue até o diretório do projeto:
```bash
cd MegaApiDotnetCore/src
```

3. Restaure os pacotes:
```bash
dotnet restore
```

4. Execute o projeto:
```bash
dotnet run
```

A API estará disponível em `https://localhost:5001` ou `http://localhost:5000`

## 🔗 Endpoints da API

A documentação completa dos endpoints está disponível através do Swagger UI após a execução do projeto em:

```
https://localhost:5001/swagger
```

## 🤝 Contribuição

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3. Adicione suas mudanças (`git add .`)
4. Comite suas mudanças (`git commit -m 'Adicionando uma Feature incrível!'`)
5. Faça o Push da Branch (`git push origin feature/AmazingFeature`)
6. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença [MIT]. 
👨‍💻 Wander Coelho
[Github](https://github.com/wandercoelho)


---

