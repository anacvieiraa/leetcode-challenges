## 💡 Lógica da Solução

Para resolver esse problema, precisamos encontrar os produtos que **possuem baixo teor de gordura** e que também são **recicláveis**.

A tabela `Products` possui as seguintes colunas relevantes para essa verificação:

- `low_fats`: indica se o produto tem baixo teor de gordura (`'Y'` ou `'N'`)
- `recyclable`: indica se o produto é reciclável (`'Y'` ou `'N'`)

A lógica da consulta é simples:
- Filtrar todos os registros onde `low_fats = 'Y'` **e** `recyclable = 'Y'`

Ou seja, apenas os produtos que atendem às **duas condições ao mesmo tempo** devem ser retornados.

