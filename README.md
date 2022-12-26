# Desafio-DIO-Refinando-um-Projeto-Conceitual-de-Banco-de-Dados-E-COMMERCE
## Refine o modelo apresentado acrescentando os seguintes pontos:

Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
Entrega – Possui status e código de rastreio;

O Projeto Conceitual foi desenvolvido segundo os parâmetros do desafio proposto.

Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações: O idClinte se relaciona com uma das duas tabelas Pessoa Física ou Pessoa Jurídica, nunca as duas informações estão juntas com o mesmo cliente.

Pagamento – Pode ter cadastrado mais de uma forma de pagamento: Há mais de uma forma de pagamento cadastrada, porém apenas uma pode ser escolhida pelo cliente.

Entrega – Possui status e código de rastreio: A tabela Pedido Finalizado, após ser identificado o pagamento do pedido com a forma de pagamento, recebe um código de rastreio e um status da entrega.
