# Projeto Faculdade

## Projeto de Banco de Ddos para Gerenciamento de uma Faculdade

Esse projeto teve como intuíto fazer passo a passo da modelagem de dados, passando pelo Levantamento de Requisitos, Identificação de Entidades e Relacionamentos, Modelo E-R e Diagrama E-R.

**1°** Levantamente dos requisitos e entendimento das regras de negócio.

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

**2°** Identificando as possíveis entidades:

Aluno, Professor, Disciplina, Departamento, Professor, Curso

**3°** Relacionar atributos ás entidades definidas até o momento: 

| First Header  | Second Header | First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
