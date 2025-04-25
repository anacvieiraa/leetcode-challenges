## Tabela: Produtos

| Nome da Coluna           | Tipo  |
|--------------------------|-------|
| `product_id`             | int   |
| `baixo_teor_de_gordura`  | enum  |
| `reciclável`             | enum  |

- `product_id` é a **chave primária** (coluna com valores únicos) para esta tabela.  
- `baixo_teor_de_gordura` é um **ENUM** do tipo `('Y', 'N')`, onde `'Y'` significa que este produto tem baixo teor de gordura e `'N'` significa que não tem.  
- `reciclável` é um **ENUM** do tipo `('Y', 'N')`, onde `'Y'` significa que este produto é reciclável e `'N'` significa que não é.

---

## Objetivo

Escreva uma solução para encontrar os IDs de produtos **com baixo teor de gordura** e **recicláveis**.

Retorne a tabela de resultados em qualquer ordem.

---

## Exemplo 1

### Entrada  
Tabela `Produtos`:

| id_do_produto | baixo_teor_de_gordura | reciclável |
|---------------|------------------------|------------|
| 0             | Y                      | N          |
| 1             | Y                      | Y          |
| 2             | N                      | Y          |
| 3             | Y                      | Y          |
| 4             | N                      | N          |

### Saída

| id_do_produto |
|---------------|
| 1             |
| 3             |

### Explicação

Somente os produtos `1` e `3` são **de baixo teor de gordura** e **recicláveis**.
