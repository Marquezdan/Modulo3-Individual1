# Projeto 1 Módulo 3: Sistema RESILIADATA
## Primeiro trabalho individual do módulo 3 da Resilia | Senac
# Aluno: Daniel Marques

#Perguntas:
1. Existem outras entidades além dessas?
Sim, a relação entre empresa e tecnologia se torna uma nova entidade.
2. Quais são os principais campos e tipos?
Os principais campos são ID e tipo INT.

3. Como essas entidades estão relacionadas?

Estão relacionadas de uma forma que a empresa parceira pode possuir várias tecnologias, assim como uma tecnologia pode estar presente em várias empresas.

# Exemplo de registro:

INSERT INTO empresa_parceira (id_empresa, Nome, Endereco, Cursos)
VALUES  (1, 'Senac', 'Rua Cel. Carlos Matos, 86, Nova Iguaçu-RJ', 'Analise de dados'),
        (2, 'TrustBank','Rua Ipanema, 102, Rio de Janeiro-RJ', ' Formação em Python e R' )

INSERT INTO tecnologia (id_tecnologia, nome, area)
VALUES (1, 'Python', 'Analise de dados'),
       (2, 'JavaScript', 'webdev');

