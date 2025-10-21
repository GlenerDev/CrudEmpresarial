# CrudEmpresarial
![Status do Projeto](https://img.shields.io/badge/Windows%20forms-yellow)
![Linguagem Principal](https://img.shields.io/badge/Linguagem-C%23-blue)

## 💻 Descrição do Projeto

O **CrudEmpresarial** é uma aplicação robusta e eficiente desenvolvida em C# com foco em **operações de gerenciamento de dados (CRUD)** para o ambiente corporativo.

Este projeto visa demonstrar e fornecer uma base sólida para a construção de sistemas que necessitam manipular informações empresariais de maneira segura e organizada, como registro de funcionários, gestão de produtos ou controle de departamentos.

## ✨ Funcionalidades Principais

* **Criação (Create):** Inserção de novos registros no banco de dados.
* **Leitura (Read):** Visualização e listagem de todos os dados empresariais.
* **Atualização (Update):** Modificação de registros existentes.
* **Exclusão (Delete):** Remoção permanente de registros.
* **Interface Intuitiva:** Design focado na experiência do usuário para facilitar as operações.
* **Estrutura Escalável:** Utilização de boas práticas de programação para um código limpo e de fácil manutenção.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias e frameworks:

* **C#** - Linguagem de programação principal.
* **.NET Core** - Plataforma de desenvolvimento.

## 🚀 Como Executar o Projeto

Para configurar e rodar este projeto em sua máquina local, siga os passos abaixo:

### Pré-requisitos

Certifique-se de ter instalado:

* [**SDK do .NET**](https://dotnet.microsoft.com/download) (versão compatível com o projeto).
* Um IDE de desenvolvimento (ex: **Visual Studio** ou **VS Code**).
* O SGBD utilizado (**SQL Server**, etc.) configurado.

### Configuração

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/GlenerDev/CrudEmpresarial.git](https://github.com/GlenerDev/CrudEmpresarial.git)
    ```
2.  **Acesse o Diretório do Projeto:**
    ```bash
    cd CrudEmpresarial
    ```
3.  **Configuração do Banco de Dados:**
    * Crie um banco de dados vazio em seu SGBD local.
    * Atualize a string de conexão no arquivo de configuração (`appsettings.json` ou similar) dentro do projeto principal `CrudEmpresarial` para apontar para o seu banco de dados local.
4.  **Restaure as Dependências (pacotes NuGet):**
    ```bash
    dotnet restore
    ```
5.  **Aplique as Migrações (Se estiver usando EF Core):**
    ```bash
    dotnet ef database update
    ```

### Iniciar a Aplicação

Execute a aplicação a partir da linha de comando:

```bash
dotnet run --project CrudEmpresarial/CrudEmpresarial.csproj
