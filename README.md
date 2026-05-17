# 🌐 Projeto de Testes de API - JSONPlaceholder (Postman)

Este repositório contém os artefatos de um projeto prático de **Testes de API (Back-end)** utilizando o **Postman**, realizado sobre a API pública [JSONPlaceholder](https://jsonplaceholder.typicode.com/).

O objetivo é demonstrar o entendimento de requisições HTTP, automação de testes de contrato/funcionais no back-end e documentação de falhas.

## 🛠️ Ferramentas e Tecnologias Utilizadas
- **Ferramenta de Testes:** Postman (Desktop/Web)
- **Linguagem dos Scripts de Teste:** JavaScript
- **Documentação:** Markdown, GitHub
- **Ambiente de Teste:** JSONPlaceholder API

## 🧪 Cenários de Teste Automatizados (CRUD)
A coleção criada cobre os quatro verbos principais da arquitetura REST:

- **`GET /users` (Read):** Validação de listagem de usuários com testes automáticos de Status Code (200 OK), tempo de resposta (performance) e validação se a resposta é um array preenchido.
- **`POST /users` (Create):** Simulação de cadastro de novo usuário enviando payload JSON. Testes automáticos de Status Code (201 Created), verificação de geração de ID e integridade dos dados retornados.
- **`PUT /users/1` (Update):** Atualização de dados de um usuário específico, validando o sucesso da alteração.
- **`DELETE /users/1` (Delete):** Exclusão de registro e validação do retorno do servidor.

## 📂 Estrutura do Repositório
- **`[Coloque_Aqui_o_Nome_Do_Seu_Arquivo].json`:** Arquivo contendo todas as requisições prontas e os scripts de teste em JavaScript salvos.
- **[Relatório de Bug de API](./Bug-API-Report.md):** Documentação técnica simulando o reporte de uma falha crítica de validação de dados no back-end.

## 🚀 Como Executar este Projeto
1. Faça o download do arquivo `.json` deste repositório.
2. Abra o seu **Postman**.
3. No canto superior esquerdo, clique em **Import**.
4. Arraste o arquivo `.json` baixado para dentro do Postman.
5. Abra a coleção importada, escolha qualquer requisição e clique em **Send**.
6. Verifique os resultados na aba **Test Results**.

## 👨‍💻 Autor
**Rodrigo Roberto Pellegrini Rufino de Souza**
*Técnico em Desenvolvimento de Sistemas | QA & Testes*
