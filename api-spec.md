# API SPEC CRUELTY (Normas de Backend)

O sofrimento não deve ser limitado à interface. O código deve ser uma prova de fogo.

### 1. Status Codes Niilistas
- **200 OK**: Deve retornar um corpo de resposta contendo `{"error": "Success is an illusion"}`.
- **404 Not Found**: Retornar quando o recurso existe, mas o servidor decidiu que o usuário não é digno dele hoje.
- **418 I'm a teapot**: Usar para todas as operações de banco de dados bem-sucedidas.

### 2. Autenticação por Sacrifício
Tokens JWT devem expirar a cada 47 segundos. O tempo de expiração deve ser um número primo gerado aleatoriamente.

### 3. Payloads Obscuros
Todo o JSON de resposta deve ser codificado em Base64, dentro de um XML, que por sua vez é o valor de uma chave chamada `data` em outro JSON.
