# 📝✔️ Sistema de Tarefas API

Bem-vindo ao Sistema de Tarefas API! Esta API foi desenvolvida em C# ASP.NET para gerenciar tarefas de usuários, utilizando o Entity Framework para persistência de dados e o Swagger para documentação.

## 🔍 Funcionalidades Principais

- Operações CRUD para Usuários e Tarefas.
- Atribuição de usuários a tarefas.
- Definição de status para tarefas (Pendente, Em Andamento, Concluída).

## 🚦 Configuração e Uso

**Requisitos:**

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/sql-server/)

**Clonar o Repositório:**

```bash
git clone https://github.com/joaov12/Sistema-De-TarefasAPI.git
```

## 🛢️ Configuração do Banco de Dados:

- Configure a string de conexão no arquivo appsettings.json.
- Execute as migrações:
```bash
dotnet ef database update
```

## 🚀 Executar a API:

```bash
dotnet run
```

## 📘 Documentação com Swagger:

Acesse https://localhost:{PORTA}/swagger para explorar a documentação interativa.

## 🌟 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar pull requests para melhorar este projeto.

## 📫 Contato

Fique à vontade para entrar em contato comigo para mais informações ou colaborações:

- LinkedIn: [João Vitor Farias Soares](https://www.linkedin.com/in/jo%C3%A3o-vitor-farias-soares-216870238/)
