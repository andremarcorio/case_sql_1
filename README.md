# case_sql_1
### Enunciado
Imagine uma base de dados de uma universidade que contenha as seguintes tabelas e seus respectivos campos organizados da seguinte forma:

tabela_alunos → colunas = (ra, nome, endereco, cidade);

tabela_disciplinas → colunas = (cod_disc, nome_disc, carga_hor)

tabela_professores → colunas = (cod_prof, nome, endereco, cidade)

tabela_turma → colunas = (cod_disc, cod_turma, cod_prof, ano, semestre)

tabela_historico, colunas = (ra, cod_disc, cod_turma, cod_prof, ano, semestre, frequencia, nota)

a) Monte uma consulta que informe quantos alunos cursaram a disciplina de Banco de Dados em 2019 e 2020;

b) Monte uma consulta que exiba os nomes dos alunos que não foram reprovados em nenhuma disciplina (considere nota mínima igual a 6 para aprovação).
