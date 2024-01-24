# Desafio Oficina 

## Construindo um Esquema Conceitual para Banco De dados

Projeto proposto no Bootcamp [SQL Database Analyst](https://www.dio.me/bootcamp/formacao-sql-db-specialist) na plataforma [DIO](https://www.dio.me/) com o intuíto de exercitar o desenvolvimento do modelo conceitual e modelo lógico, antes da implementação do Banco de dados.

Narrativa do desafio para o **Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica**

  + Clientes levam veículos para conserto ou revisão periódica;
  + Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega;
  + A partir da OS, calcula-se o valor do serviço, consultando uma tabela de referência de mão-de-obra;
  + O valor de cada peça também irá compor a OS;
  + O cliente autoriza a execução dos serviços;
  + A mesma equipe avalia e executa os serviços;
  + Os mecânicos possuem código, nome, endereço e especialidade;
  + Casa OS possui nº, data de emissão, um valor, status e uma data para conclusão dos trabalhos;
  + Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS;
  + Uma OS pode ter vários tipos de peça e uma peça pode estar presente em mais de uma OS;
  + Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega;
  + Não é especificado se essa equipe de mecânicos já é pré-formada ou se pode variar a depender do caso, foi levado em conta que é pré-formada;
  + A partir da OS, calcula-se o valor do serviço.
 
 Entidades identificadas: Cliente, Veículo, Equipe, Mecânico, Serviço, Peças, Ordem de Serviço

 # Resultado

 ![Modelo conceitual de uma Oficina](https://github.com/monyzeweber/Projetos-SQL/assets/81835859/d9abf42f-c4de-47d2-8273-fb30eecd4ca2)

 
