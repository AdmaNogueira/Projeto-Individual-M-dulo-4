# Projeto-Individual-M-dulo-4

A Resilia está pensando em lançar um novo sistema de acompanhamento e para isso precisa de ajuda para modelar um banco de dados que vai armazenar seus cursos, turmas e alunos.

Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem e responder algumas perguntas com nosso modelo:

⇨ Existem outras entidades além dessas três?
Sim. Foram adicionadas as entidades: **Coordenadores** e **Facilitadores**.

⇨ Quais são os principais campos e tipos?
Foram definidos como campos primários: **CNPJ**, **Id_Curso**, **Id_Turma**, **Matrícula**, **Matrícula_Funcionário** e **Id_Contrato**. Estes trabalham como chaves primárias (**PK**) e chaves estrangeiras (**FK**).

⇨ Como essas entidades estão relacionadas?
Instituição (**1,N**) abre Curso; Curso (**1,N**) possui Coordenadores; Coordenadores (**N,N**) instruem Facilitadores; Facilitadores (**1,N**) comandam Turma; Curso (**1,N**) forma Turma; Turma (**1,N**) possui Aluno;

Segue modelo conceitual:

<IMG SRC = ""
