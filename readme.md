# ☁️ Projeto Computação em Nuvem

<div align="center">

Aplicação desenvolvida com **Node.js** e **Express** para demonstrar os principais conceitos de **Computação em Nuvem**, incluindo deploy no **Azure Web Apps**, utilização de **GitHub Actions** e configuração de **variáveis de ambiente**.

![Node.js](https://img.shields.io/badge/Node.js-22-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-4-black?style=for-the-badge&logo=express)
![Azure](https://img.shields.io/badge/Azure-Web%20Apps-0078D4?style=for-the-badge&logo=microsoftazure)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI/CD-2088FF?style=for-the-badge&logo=github-actions)

</div>

---

# 📖 Sobre o projeto

Este projeto demonstra como publicar uma aplicação Node.js em um ambiente de Computação em Nuvem utilizando o **Azure Web Apps**.

A aplicação foi desenvolvida com **Express** e possui endpoints simples para ilustrar o funcionamento de uma API REST. O foco principal está na configuração do ambiente em nuvem, gerenciamento de variáveis de ambiente e automação do processo de deploy utilizando **GitHub Actions**.

---

# 🎓 Contexto acadêmico

Este projeto foi desenvolvido como material de apoio para um webinar da disciplina de **Computação em Nuvem**, do curso de **Análise e Desenvolvimento de Sistemas**.

Durante o webinar, os alunos acompanharam todo o processo de publicação de uma aplicação Node.js em um serviço de nuvem, compreendendo conceitos como infraestrutura em nuvem, configuração de aplicações, deploy automatizado e gerenciamento de variáveis de ambiente utilizando o Azure Web Apps.

Além do projeto, o repositório disponibiliza materiais de apoio com o passo a passo para criação de contas na **Microsoft Azure** e na **Amazon Web Services (AWS)**.

---

# 🎯 Objetivos de aprendizagem

Ao longo do webinar foram abordados os seguintes conhecimentos:

## Desenvolvimento

- criação de APIs utilizando Node.js e Express;
- definição de rotas HTTP;
- utilização de variáveis de ambiente;
- organização de aplicações backend.

## Computação em Nuvem

- conceitos fundamentais de Cloud Computing;
- deploy de aplicações no Azure Web Apps;
- utilização do GitHub Actions para automação do deploy;
- configuração de ambientes de execução;
- gerenciamento de secrets e variáveis de ambiente;
- integração entre GitHub e Azure.

---

# ✨ Funcionalidades

- API REST desenvolvida com Express;
- endpoint inicial para verificação da aplicação;
- listagem de alunos;
- listagem de professores;
- listagem de cursos;
- utilização de variáveis de ambiente;
- deploy automatizado no Azure.

---

# 🏗️ Arquitetura

```text
Cliente
      │
      ▼
 Azure Web App
      │
      ▼
 Aplicação Node.js
      │
      ▼
 Express
      │
      ▼
 Endpoints REST
```

---

# 📂 Estrutura do projeto

```text
projeto-computacao-nuvem/

├── .github/
│   └── workflows/
│       └── main_api-cloud.yml
│
├── documentos/
│   ├── passo-a-passo-nova-conta-aws.pdf
│   └── passo-a-passo-nova-conta-azure.pdf
│
├── server.js
├── package.json
├── package-lock.json
└── README.md
```

---

# ☁️ Fluxo de implantação

```text
Desenvolvedor
      │
      ▼
GitHub
      │
      ▼
GitHub Actions
      │
      ▼
Azure Web Apps
      │
      ▼
Aplicação em Produção
```

---

# 🚀 Tecnologias utilizadas

## Backend

- Node.js
- Express
- JavaScript

## Computação em Nuvem

- Microsoft Azure Web Apps
- GitHub Actions

## Ferramentas

- Git
- GitHub
- dotenv

---

# ⚙️ Como executar

## Pré-requisitos

- Node.js
- npm

---

## Clone o repositório

```bash
git clone https://github.com/leticia-gomes/projeto-computacao-nuvem.git
```

Entre na pasta:

```bash
cd projeto-computacao-nuvem
```

---

## Instale as dependências

```bash
npm install
```

---

## Configure as variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto.

Exemplo:

```env
PORT=3000
API_KEY=sua_chave
```

---

## Execute a aplicação

```bash
npm start
```

A API ficará disponível em:

```
http://localhost:3000
```

---

# 📡 Endpoints

| Método | Endpoint | Descrição |
|--------|----------|-----------|
| GET | `/` | Verifica se a API está em execução |
| GET | `/alunos` | Lista de alunos |
| GET | `/professores` | Lista de professores |
| GET | `/cursos` | Lista de cursos |

---

# 📚 Materiais de apoio

O repositório inclui documentos utilizados durante o webinar:

- Guia para criação de conta na Microsoft Azure;
- Guia para criação de conta na Amazon Web Services (AWS).

Esses materiais auxiliam os alunos na preparação do ambiente para acompanhar as atividades práticas.

---

# 📚 Conceitos abordados

Durante o desenvolvimento deste projeto são explorados os seguintes conceitos:

- Computação em Nuvem
- Azure Web Apps
- Deploy de aplicações
- GitHub Actions
- Integração Contínua
- Entrega Contínua
- Variáveis de ambiente
- Express
- Node.js
- APIs REST
- Git e GitHub

---

# 🔮 Melhorias futuras

- adicionar autenticação JWT;
- integrar um banco de dados em nuvem;
- implementar testes automatizados;
- criar documentação com Swagger;
- adicionar monitoramento da aplicação;
- configurar logs centralizados;
- utilizar Azure Application Insights;
- realizar deploy também na AWS.

---

# 👩‍🏫 Sobre o webinar

Este projeto foi desenvolvido como material de apoio para um webinar da disciplina de **Computação em Nuvem**.

Utilizando uma aplicação Node.js como exemplo, os alunos acompanharam todas as etapas necessárias para publicar uma aplicação em ambiente de nuvem, desde a configuração do projeto e das variáveis de ambiente até a automação do deploy utilizando GitHub Actions e Azure Web Apps. O objetivo foi apresentar, de forma prática, os principais conceitos de infraestrutura em nuvem e implantação de aplicações modernas.

---

# 👩‍💻 Autora

**Letícia Gomes Ribeiro**

Desenvolvedora Full Stack • Professora Universitária

### Tecnologias

- C#
- ASP.NET Core
- Node.js
- React
- Angular
- FastAPI
- SQL Server
- PostgreSQL

GitHub: https://github.com/leticia-gomes

---

# 📄 Licença

Este projeto está disponível para fins educacionais.

Caso deseje disponibilizá-lo como projeto open source, recomenda-se adicionar uma licença, como a MIT License.

---

# ⭐ Apoie este projeto

Se este projeto foi útil para você, considere deixar uma ⭐ no repositório.
