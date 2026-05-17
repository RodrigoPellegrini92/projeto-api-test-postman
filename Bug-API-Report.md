# 🐛 Relatório de Bug: API de Usuários (Back-end)

**Título:** [POST] Criação de usuário aceitando campo "email" em branco ou nulo.
**Ambiente:** API de Produção (https://jsonplaceholder.typicode.com)
**Data:** 13/05/2026

## 📝 Descrição
Ao realizar uma requisição POST para o endpoint `/users` omitindo a chave `email` no corpo da requisição (Body), a API está retornando o status `201 Created` e salvando o registro com o dado nulo, em vez de validar a obrigatoriedade do campo e retornar um erro `400 Bad Request`.

## 🛠️ Passos para Reproduzir

1. Abrir o Postman.
2. Configurar uma nova requisição com o método **POST** para a URL: `https://jsonplaceholder.typicode.com/users`
3. Na aba **Body**, selecionar `raw` e `JSON`.
4. Enviar o seguinte payload (sem o campo email):
```json
{
    "name": "Usuário Teste Falha",
    "username": "teste.falha"
}
