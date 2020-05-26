# Cobol-Project  Este projeto ajuda novos alunos da Cobol a criar um sistema simples, mas muito didático.
1. um arquivo inicial com nomes e sobrenomes é fornecido como base.isto é feito pelo programa MAKESTUD.CBL
2.um programa cobol lê os dados com os nomes que estão no arquivo JCL (JMKSTUD) e ao mesmo tempo cria números de código fictícios para cada aluno.
3. os registros de saída são gravados em outro data-set (STDLIST) com registros fixos de 170 bytes.
4.a idéia é construir os novos dados pouco a pouco a fim de tornar o aprendizado  didático.
5.Um novo desafio é sugerido.O Objetivo é ler os registros que estão em (STDLIST) CODE, NAME,LAST NAME  e criar um novo campo com telefones ficticios gerados automaticamente pelo programa cobol.
Os novos campos são código (DDD , NUMERO DE TELEFONE)
Os novos  registros são gravados em outro data set ( STDAUX) pelo codigo JCL (JMKFONE)
