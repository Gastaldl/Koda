# Koda API

> **Tema:** O Futuro do Trabalho - Upskilling & Reskilling para 2030+

## Descrição do Projeto

A **Koda** é uma API RESTful desenvolvida para gerenciar uma plataforma de educação continuada. No contexto de transformação digital impulsionada por IA e automação, nossa solução visa facilitar o **Reskilling** (requalificação) e **Upskilling** (aperfeiçoamento) de profissionais.

A API permite o gerenciamento de **Trilhas de Aprendizagem** focadas em competências do futuro (como IA Generativa, ESG e Soft Skills) e o cadastro de **Usuários** que buscam se preparar para o mercado de trabalho de 2030.

**Destaques da Solução:**

* Alinhamento com ODS 4 (Educação de Qualidade) e 8 (Trabalho Decente).
* Arquitetura desacoplada e escalável.
* Controle de versionamento de API.

---

## ☁️ Deploy e Acesso Público

A API foi publicada no Microsoft Azure e está pronta para testes.

### 🔗 Links de Acesso
* **Base URL:** `https://api-koda-fiap-hehyffhvcdgvbxdf.brazilsouth-01.azurewebsites.net`
* **Swagger UI (Documentação Interativa):** [Clique aqui para testar (Swagger)](https://api-koda-fiap-hehyffhvcdgvbxdf.brazilsouth-01.azurewebsites.net/swagger)
* **Endpoint de Exemplo (GET Trilhas):** [Visualizar JSON de resposta](https://api-koda-fiap-hehyffhvcdgvbxdf.brazilsouth-01.azurewebsites.net/api/v1/Trilhas)

> **Nota:** A API conecta-se a uma instância Oracle Database (Cloud FIAP). As credenciais de acesso ao banco de dados são gerenciadas de forma segura através das Variáveis de Ambiente do Azure.

---

## Tecnologias Utilizadas

* **Linguagem:** C# (Platforma .NET 9)
* **Framework:** ASP.NET Core Web API
* **Banco de Dados:** Oracle Database
* **ORM:** Entity Framework Core 9.0
* **Documentação:** Swagger (Swashbuckle)
* **Versionamento:** Asp.Versioning.Mvc
* **Arquitetura:** Camadas (DDD Simplificado: Controller, Service, Repository)

---

## Configuração e Execução Local

Caso deseje rodar o projeto localmente em vez de acessar o deploy:

### 1. Pré-requisitos

* [.NET SDK 9.0](https://dotnet.microsoft.com/download) instalado.
* Acesso a um banco de dados Oracle.
* Visual Studio 2022 ou VS Code.

### 2. Clonar e Restaurar Dependências

Abra o terminal na pasta raiz do projeto e execute:

```bash
# Restaura os pacotes NuGet definidos no projeto
dotnet restore
