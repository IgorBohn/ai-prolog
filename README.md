# Trabalho de Implementação com Prolog para a matéria de Inteligência Artificial.
Utilizando como base de conhecimento a Grade Curricular dos Cursos de CC e SI.
O objetivo da atividade foi desenvolver uma base de conhecimento em prolog que represente as informações básicas dos currículos dos cursos de CC e SI (Disciplinas, semestres, códigos, carga-horária etc...).

# Comandos para rodar no vscode:
    ~$ swipl
    ~$ consult("ia.pl").
    ~$ disciplina(curso, semestre, codigo_inicio, codigo, nome, carga_horaria_teoria, carga_horaria_pratica, pre_requisito, materia_comum).
    ~$ disciplinasPorSemestreECurso(X, 1, 'CC').
    ~$ curriculoDoCurso(X, 'CC').
    ~$ disciplinaFazParteDoCurso('Trabalho Final de Graduacao em SI', 'CC').
    ~$ disciplinaCCSI(X).
    ~$ temPreRequisito('Linguagem de Programacao II').
    ~$ disciplinasComPR(X).
    ~$ disciplinaComuns(X).
    ~$ temCargaHorariaPratica(X).
    ~$ disciplinasDeOutrasAreas(X).
