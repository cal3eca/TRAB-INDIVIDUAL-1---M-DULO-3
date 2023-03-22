ALUNO: MATHEUS BARBOSA FURTADO
SENAC BOTAFOGO - RESILIA

# TRAB-INDIVIDUAL-1---MÓDULO-3
Repositório referente ao trabalho individual 1 do módulo 3.

###1) Existem outras entidades além dessas?

As entidades, servem .. No meu projeto, há três entidades, sendo que poderiam haver mais.
Uma para definir a empresa, outra para cadastrar as tecnologias e uma terceira que cadastraria a empresa
com suas tecnologias dentro de uma entidade principal (RESILIADATA)

###2) Quais são os principais campos e tipos?

Cada uma das entidades, tem atributos sendo alguns principais, sendo esses denominados como id (identificadores), pois são únicos. e outros, que são para cadastro de outras informações.
os tipos desses atributos variam, entre (VARCHAR, INTEGER, e DATE).

###3) Como essas entidades estão relacionadas?

Essas entidades se relacionam através das suas cardinalidades, e nesse sentido há uma entidade (EMPRESA), que necessariamente
tem de haver no mínimo uma, e no máximo uma (1,1), se conectando à entidade (TECNOLOGIAS), em que a empresa conectada no caso, teria no mínimo nenhuma tecnologia, ou quantas tiverem (0,N), essas informações ficariam contidas na entidade (TECNOLOGIAS_EMPRESA), onde haveria no mínimo zero e no máximo uma empresa por vez (0,1) mais um registro de suas tecnologias, somalizadas. Seguiria para o final do banco de dados, onde seriam registradas as informações da empresa somadas as tecnologias que a mesma cadastrou, saindo de (tecnologias_empresa) sendo no mínimo nenhuma, e no máximo quantas tiverem. Para o banco (RESILIADATA), onde cadastriam ou nenhuma empresa e no máximo uma (0,1)
CARDINALIDADES
