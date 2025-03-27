# Sistema de Consultas Médicas

![Banner do Sistema](https://img.shields.io/badge/Sistema-Consultas_Médicas-27ae60?style=for-the-badge)

## 📝 Sobre o Projeto

Esse projeto consiste em um sistema de consultas médicas, onde os pacientes podem pesquisar médicos por especialidade, visualizar horários disponíveis e agendar consultas, cadastro de usuários e tudo que engloba um sistema de consultas médicas.

Aproveitei a oportunidade para desenvolver em equipe, utilizando o git e github como ferramenta de colaboração, então gostaria de agradecer aos meu colega de equipe e irmão do coração [Danzokka](https://github.com/Danzokka).

## 🛠️ Tecnologias Utilizadas

![TypeScript](https://img.shields.io/badge/language-TypeScript-3178C6?style=flat&logo=typescript) ![Next.js](https://img.shields.io/badge/frontend-Next.js-000000?style=flat&logo=next.js) ![NestJS](https://img.shields.io/badge/backend-NestJS-E0234E?style=flat&logo=nestjs) ![PostgreSQL](https://img.shields.io/badge/database-PostgreSQL-336791?style=flat&logo=postgresql) ![Docker](https://img.shields.io/badge/container-Docker-2496ED?style=flat&logo=docker) ![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git) ![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github) ![Css](https://img.shields.io/badge/-Css-1572B6?style=flat&logo=css3) ![Html](https://img.shields.io/badge/-Html-E34F26?style=flat&logo=html5) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript)

## 🔍 Visão Geral

O Sistema de Consultas Médicas é uma plataforma completa para gerenciar agendamentos de consultas médicas. Os pacientes podem pesquisar médicos por especialidade, visualizar avaliações, agendar consultas e gerenciar seus agendamentos. Os médicos podem visualizar e gerenciar seus horários e consultas agendadas.

### Principais Funcionalidades

✅ Cadastro de usuários
✅ Pesquisa de médicos por especialidade
✅ Visualização de horários disponíveis
✅ Agendamento de consultas

## 📦 Requisitos

Node.js 18.x ou superior
PostgreSQL 14.x ou superior
Docker e Docker Compose

## 🚀 Configuração de Desenvolvimento

### Configuração com Docker

Para iniciar o sistema completo com Docker:

#### Clone o repositório

```bash
git clone https://github.com/Danzokka/projeto-consultas.git
```

#### Navegue até o diretório do projeto

```bash
# Entre na pasta raiz do projeto
cd projeto-consultas

# Inicie os containers
docker compose up -d --build

# Para visualizar os logs
docker compose logs -f
```

Após o Docker compose montar toda a infraestrutura, você poderá acessar:

* Frontend: <http://localhost:3000>

* Backend: <http://localhost:5000>