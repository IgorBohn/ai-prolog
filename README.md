# Trabalho de Implementação com Prolog para a matéria de Inteligência Artificial.
Base de Conhecimento (Grade Curricular dos cursos de CC e SI)
O objetivo desta atividade é desenvolver uma base de conhecimento em prolog que represente as informações básicas dos currículos dos cursos de CC e SI (Disciplinas, semestres, códigos, carga-horária etc...).

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
