# Banco de dados resilia


Esse repositório foi criado como um exercício para o curso de "Desenvolvedor fullstack" oferecido pela resilia em conjunto a prefeitura do rio.
A proposta é modelar um banco de dados para um novo sistema de acompanhamento de matrículas.

As entidades propostas inicialmente são: Cursos, Turmas e Alunos.

### Existem outras entidades além dessas três?

Sim, nos podemos ter uma entidade só para representar o relacionamento entre turmas e alunos, podemos também ter uma entidade para relacionar Turmas e Cursos a decisão de criar ou não essas entidades vai depender critérios como possibilidade de aceitarmos campos nulos para alguns dados ou repetição de informações.

### Quais são os principais campos e tipos?

Os principais campos são os campos de chave primaria e estrangeira definidos nas tabelas que foram propostas, os campos de data e horário também são fundamentais.
Os principais tipos são: INT, VARCHAR, DATETIME

### Como essas entidades estão relacionadas?

Um curso possui varias turmas de que fazem parte vários alunos.
Um aluno faz parte de uma ou mais turmas e cada uma dessas turmas por sua vez pertence a um único curso.
