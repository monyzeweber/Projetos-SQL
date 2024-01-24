# Refinando um Projeto Conceitual de Banco de Dados E-COMMERCE:
 Projeto proposto no Bootcamp [SQL Database Analyst](https://www.dio.me/bootcamp/formacao-sql-db-specialist) na plataforma DIO com o intuíto de estabelecer uma base sólida na modelagem de dados, com mais clareza e compreensão aprofundada dos requisitos para criação de um banco de dados eficiente.

## Descrição
"Modelamos juntos um contexto reduzido de e-commerce. Agora é a sua vez, podes escolher a ferramenta de modelagem para realizar o desafio. Contudo, fique atento! Caso opte por uma variação do modelo entidade relacionamento, como nas ferramentas Mysql Workbench ou DBDesigner será preciso especificar as PK e FKs corretamente. Apesar desse conceito não ser utilizado na modelagem conceitual exploramos brevemente suas definições. Sendo assim, seu empregável será o esquema conceitual para o cenário de E-commerce."

Instrutora: Juliana Mascarenhas

### Objetivo

Criar um projeto conceitual com o seguinte escopo: 

+ Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos;
+ Cada produto possui um fornecedor;
+ Um ou mais produtos podem conter um pedido;
+ Um cliente pode se cadastrar no site com CPF ou CNPJ;
+ O endereço do cliente irá determinar o valor do frete;
+ Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto;
+ Os pedidos são criados por clientes e possuem informação de compra, endereço e status de entrega;
+ O pedido pode ser cancelado.

### Desafio

Refine o modelo apresentado acrescentando os seguintes pontos:

+ Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
+ Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
+ Entrega – Possui status e código de rastreio;

### Ferramentas utilizadas

+ [MySql WorkBench](https://www.mysql.com/)