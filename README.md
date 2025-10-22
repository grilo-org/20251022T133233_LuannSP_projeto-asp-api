# ASP.NET Core Web API

Este repositório contém um projeto de API RESTful desenvolvido com ASP.NET Core, utilizando o Visual Studio 2022. O projeto já vem configurado com autenticação via JWT e documentação interativa com Swagger.

## 🚀 Tecnologias Utilizadas

- **ASP.NET Core**
- **C#**
- **Entity Framework Core**
- **JWT (JSON Web Token) Authentication**
- **Swagger**
- **SQL Server**
- **Visual Studio 2022**

## ⚙️ Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/LuannSP/asp-api-project.git
   ```

2. **Abra a solução no Visual Studio 2022:**

   - Abra o arquivo `AspApiProject.sln`.

3. **Restaure os pacotes NuGet:**

   - No Visual Studio: `Ferramentas` > `Gerenciador de Pacotes NuGet` > `Console do Gerenciador de Pacotes`
   - Execute:

     ```powershell
     Update-Package -reinstall
     ```

4. **Configure o banco de dados:**

   - Verifique e edite a `ConnectionString` em `appsettings.json`.

5. **Execute a aplicação:**

   - Pressione `F5` ou clique em `Iniciar`.

## 📌 Funcionalidades

- Estrutura completa para APIs RESTful.
- Documentação automática com **Swagger** em `/swagger`.
- Autenticação com **JWT Bearer Token**.
- Integração com banco de dados via **Entity Framework Core**.
- Padrão de projeto limpo e escalável.

## 🛠️ Contribuindo

Contribuições são bem-vindas! Abra uma issue ou envie um pull request.

---

> Desenvolvido por [LuannSP](https://github.com/LuannSP)
