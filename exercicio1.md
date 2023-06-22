# Exercício 1
Agora que sabemos como implementar relações do tipo 1:m e 1:1, vamos refatorar a estrutura do Labecommerce!<br>
Por ora não precisaremos editar as tabelas já existentes (users e products). Nosso objetivo hoje é criar a tabela de pedidos (purchases).<br>
Na próxima aula veremos como criar a lógica para adicionar produtos em uma ordem de pedido.

## Criação da tabela de **pedidos**
- nome da tabela: **purchases**
- colunas da tabela:
  - id (TEXT, PK, único e obrigatório)
  - buyer (TEXT, obrigatório e FK = referencia a coluna id da tabela users)
  - total_price (REAL e obrigatório)
  - created_at (TEXT e opcional)
