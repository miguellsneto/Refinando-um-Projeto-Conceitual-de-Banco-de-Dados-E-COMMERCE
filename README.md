# **Refinando um Projeto Conceitual de Banco de Dados E-COMMERCE**


## _Projeto Conceitual:_
### Narrativa - Cliente:
- O Cliente pode se cadastrar no site com CPF ou CNPJ
- O endereço do cliente vai determinar o valor do frete
- Um cliente pode comprar mais de um pedido
### Narrativa - Pedido:
- Os pedidos são criados por clientes e possuem informações de compra, endereço e status de entrega
- Um ou mais produtos compõem o pedido
- O pedido pode ser cancelado
### Narrativa - Produto:
- Os produtos são vendidos por uma única plataforma online. Contudo, estes produtos podem ter vendedores distintos(terceiros)
- Cada produto possui um fornecedor
- Um ou mais produtos podem compor um pedido


## _Refinamento do Projeto:_
- Cliente PF e PF - uma conta pode ser Pessoa Jurídica ou Pessoa Física, mas não pode ter as duas informações
- Pagamento - Pode ter cadastrado mais de uma forma de pagamento
- Entrega - Possui status e código de rastreio
