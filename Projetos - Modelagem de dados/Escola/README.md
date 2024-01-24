# Projeto Faculdade

## Projeto de Banco de Ddos para Gerenciamento de uma Faculdade

Esse projeto teve como intuíto fazer passo a passo da modelagem de dados, passando pelo Levantamento de Requisitos, Identificação de Entidades e Relacionamentos, Modelo E-R e Diagrama E-R.

### Levantamente dos requisitos e entendimento das regras de negócio.

+ Um aluno só pode estar matriculado em um curso por vez;
+ Alunos possuem um código de identificação;
+ Cursos são compostos por disciplinas;
+ Cada disciplina terá no máximo 30 alunos por turma;
+ As disciplinas podem ser obrigatórias ou optativas, dependendo do curso;
+ As disciplinas pertencem a departamentos específicos;
+ Cada disciplina possui um código de identificação;
+ Alunos podem trancar matrícula, não estando então matrículados em nenhuma disciplina no semestre;
+ Em cada semestre, cada aluno pode se matricular no máximo em 9 disciplinas
+ A faculdade terá no máximo 3 mil alunos matrículados simultâneamente em 10 cursos distintos;
+ Entram 300 alunos novos por ano;
+ Existem 90 disciplinas no total disponíveis;
+ Um histórico escolhar traz todas as disciplinas cursadas por um aluno, incluindo nota final, frequência e período do curso realizado;
+ Professores podem ser cadastrados mesmo sem lecionar disciplinas;
+ Existem 40 professores trabalhando na escola;
+ Cada professor pode lecionar no máximo 4 disciplinas diferentes;
+ Cada professor é vinculado a um departamento;
+ Os professores são identificados por um código de professor

### Identificando as possíveis entidades:

Aluno, Professor, Disciplina, Departamento, Professor, Curso

### Relacionar atributos ás entidades definidas até o momento: 

Professor (código do curso, nome do curso, código do departamento)
Departamento (código do departamento, nome do departamento)
Curso (código do curso, nome do curso, código do departamento)
Aluno (RA, nome, sobrenome, endereço, telefone, status, filianção código do curso)
Disciplina (código da disciplina, nome, descrição, código do departamento, número de alunos, carga horária)

A partir dessas entidades foi definida a necessidade de mais duas: Turma e Histórico para normalização:

Turma (código da turma, período, código do curso, número de alunos, data de início e data do fim)
Histórico (código do histórico, notas, média, frequência, período de realização, RA, código da disciplina)

DIAGRAMA ENTIDADE RELACIONAMENTO (com atributos):
Obs: as carnalidades ainda não foram definidas nessa momento.

![DIAGRAMA ENTIDADE RELACIONAMENTO](https://github.com/monyzeweber/SQL-Database-EER/assets/81835859/35e86c80-48e3-453d-9c7d-167359df2851)

Ao aplicar as carnalidades de cada relacionamento, foi notado que alguns relacionamento seriam de muitos para muitos, ocasionando na necessidade de criar uma tabela associativa, permitindo mapear duas ou mais tabelas, fazendo referência às chaves primárias de cada uma. Futuramente as chaves primárias de cada vão se tornar chaves estrangeiras para facilitar o relacionamento entre elas. 

Sendo assim, criei: Curso_disciplina (relação entre as entidades Curso e Disciplina), Disiplina_histórico (relação entre as entidades Disciplina e Histórico), professora_disciplina (relação entre as entidades Professor e Disciplina) e alunos_disciplina (relação entre as entidades Alunos e Disciplinas) resultando em:

DIAGRAMA ENTIDADE RELACIONAMENTO com os atributos, entidades associativas e as carnalidades definidas: 

![DIAGRAMA ENTIDADE RELACIONAMENTO FINAL](https://github.com/monyzeweber/SQL-Database-EER/assets/81835859/f45c61c8-d1e8-4c62-90be-8f65b56425e9)

### FINAL

