# DER_FLORICULTURA

Uma floricultura está buscando informatizar suas operações. Aqui está um diagrama de entidade-relacionamento (DER) que representa as informações necessárias:

## Tabelas:

1. **Clientes (CUSTOMER)**:
   - **RG**: Número de identidade do cliente (chave primária).
   - **Nome**: Nome completo do cliente.
   - **Telefone**: Número de telefone do cliente.
   - **Endereço**: Endereço residencial do cliente.

2. **Produtos (PRODUCT)**:
   - **ProdutoID**: Identificador único do produto (chave primária).
   - **Nome**: Nome do produto (por exemplo, "Rosa Vermelha", "Vaso de Suculenta").
   - **Tipo**: Tipo de produto (flor, vaso, planta etc.).
   - **Preço**: Preço unitário do produto.
   - **QuantidadeEmEstoque**: Quantidade disponível em estoque.

3. **Compras (PURCHASE)**:
   - **CompraID**: Identificador único da compra (chave primária).
   - **DataDaCompra**: Data em que a compra foi realizada.
   - **ValorTotal**: Valor total da compra.
   - **ClienteID**: Chave estrangeira referenciando o cliente que fez a compra.
   - **ProdutoID**: Chave estrangeira referenciando os produtos comprados.

## Relacionamentos:

- Um cliente pode fazer várias compras (relação 1:N entre CLIENTE e COMPRA).
- Uma compra pode incluir vários produtos (relação N:M entre COMPRA e PRODUTO).

Espero que isso ajude a visualizar como as informações estão organizadas! Se precisar de mais detalhes ou tiver outras perguntas, estou à disposição. 😊
