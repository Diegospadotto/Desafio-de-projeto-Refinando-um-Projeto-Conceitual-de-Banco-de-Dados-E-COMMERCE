Ótimo desafio! Aqui está a estrutura completa do projeto para você implementar no GitHub.


---

Desafio de Projeto: Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE

Descrição

Este projeto tem como objetivo desenvolver e refinar um modelo conceitual de banco de dados para um sistema de E-Commerce. O banco de dados deve contemplar funcionalidades essenciais para o gerenciamento de produtos, pedidos, clientes, pagamentos e logística.

Requisitos do Sistema

O sistema deve permitir:

Cadastro de clientes

Cadastro de produtos e categorias

Gestão de pedidos e itens do pedido

Processamento de pagamentos

Acompanhamento da entrega dos pedidos


Modelo Conceitual

Entidades e Relacionamentos

1. Cliente

ID (PK)

Nome

CPF/CNPJ

E-mail

Telefone

Endereço



2. Produto

ID (PK)

Nome

Descrição

Preço

Quantidade em Estoque

Categoria (FK)



3. Categoria

ID (PK)

Nome



4. Pedido

ID (PK)

Cliente (FK)

Data do Pedido

Status do Pedido

Valor Total



5. Item do Pedido

ID (PK)

Pedido (FK)

Produto (FK)

Quantidade

Preço Unitário

Subtotal



6. Pagamento

ID (PK)

Pedido (FK)

Tipo de Pagamento (Cartão, Boleto, PIX)

Status do Pagamento

Data do Pagamento



7. Entrega

ID (PK)

Pedido (FK)

Transportadora

Código de Rastreio

Data de Envio

Status da Entrega


