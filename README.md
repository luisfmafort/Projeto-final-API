# 🎮 API Genshin Impact - Trabalho Final (Node.js + SQLite)

**Aluno:** Luis Felipe Mafort  
**Instituição:** Centro Universitário Filadélfia (UniFil)  
**Professor:** Tiago Dutra Galvão  

---

## 🚀 Sobre o Projeto
Esta é uma API REST desenvolvida para o trabalho final da disciplina. O sistema gerencia um banco de dados de personagens e artefatos de Genshin Impact, aplicando conceitos de segurança, relacionamentos SQL e boas práticas de desenvolvimento.

## 🛠️ Tecnologias e Requisitos Atendidos
* **Node.js + Express:** Estrutura base da API.
* **SQLite:** Banco de dados relacional com 20 registros iniciais automáticos.
* **Relacionamentos (JOINs):** Tabela de `personagens` vinculada com a tabela de `artefatos` (1:N).
* **Filtros e Paginação:** Implementação de `limit`, `page` e filtros por `elemento`.
* **Autenticação (JWT):** Rotas de criação protegidas por token de acesso.
* **Status Codes:** Uso correto de 200, 201, 400, 401 e 404.

## 📦 Como rodar o projeto localmente
1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.
2. Clone ou baixe este repositório.
3. No terminal, dentro da pasta, digite:
   ```bash
   npm install