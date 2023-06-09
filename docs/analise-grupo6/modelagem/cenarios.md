# Verificação - Cenários

## Introdução
Este documento é destinado para a revisão do artefato de [cenários](<https://github.com/Requisitos-de-Software/2023.1-Letterboxd/blob/master/docs/Modelagem/cenarios.md>) 
do grupo 6 - [Letterbox](https://github.com/Requisitos-de-Software/2023.1-Letterboxd), vale ressaltar que a avaliação é feita de maneira imparcial,
sem a intenção de atacar ninguém.

## Metodologia

A verificação foi feita por meio da insperção, utilizando uma checklist com base em [repositórios antigos](https://github.com/Requisitos-de-Software)
e no plano de ensino da disciplina de requisitos de software. Foi usado como base o artigo "Enhancing a Requirements Baseline with Scenarios" e a apresentação de slides "Requisitos - Aula 10" para a verificação do conteúdo.
A principio, foram criadas duas tabelas nas quais, temos 3 campos, "Questão": pergunta que será respondida, "Resposta" na qual como resultados válidos, podemos ter: 

- Sim : caso um critério for atendido.
- Não : caso um critério não for atendido.
- Incompleto : caso um critério for parcialmente atendido.

Também temos o campo "Observação", um campo no qual pode ser feito algum comentário a respeito da questão em específico. Posteriormente, neste mesmo documento, pode-se encontrar uma sessão na qual serão sumarizados todos os problemas do artefacto em estudo e outra nos quais se encontram as sugestões de soluções dos mesmos.

## Checklist de documento
|ID|Questão|Resposta|Observação|
|-|-------|--------|----------|
|01|O artefato possui Introdução?                                                                                |    Sim    |          |
|02|O artefato artefato possui uma Bibliografia/Referência Bibliográfica?                                        |    Sim    |          |
|03|O artefato possui um Histórico de Versões com o id e descrição das versões, data, autores e revisores?       |    Sim    |          |
|04|Todos os textos estão na norma padrão?                                                                       |    Sim    |          |
|05|Os revisores são pessoas diferentes dos autores?                                                             |    Sim    |          |

Tabela 1 - Checklist do documento - (Fonte: Autor,2023)

## Checklist do conteúdo
|ID|Questão|Resposta|Observação|
|-|-------|--------|----------|
|06| Existem especificações dos cenários para o projeto?    | Incompleto | Não há descrição dos elementos de um cenário |
|07| Os cenários possuem título? | Sim |  |
|08| Os cenários possuem metas/objetivo? | Sim |  |
|09| Os cenários possuem contexto coerente? | Não | Houve uma interpretação diferente da elaboração de contexto |
|10| Os cenários possuem atores? | Sim |  |
|11| Os cenários possuem exceções? | Sim |  |
|12| Os cenários possuem episódios coerentes com as metas/objetivos? | Sim |  |
|13| Os cenários possuem recursos? | Sim |  |


Tabela 2 - Checklist do conteúdo

## Problemas encontrados

### ID 06, 09

Antes de apresentar os cenários elaborados, deveria ter uma explicação sobre quais componentes fazem parte de um cenário, e a descrição de tais componentes.

Segundo as fontes usadas para essa revisão, o Local e o Tempo do contexto se referem respectivamente ao local onde o usuário se encontra no momento em que usa a aplicação, e qual a data ou horário do dia essa aplicação está sendo usada. No documento analisado, esses termos foram interpretados como em qual janela da aplicação o usuário está, e quanto tempo o cenário dura.

## Sugestões

Recomenda-se consultar as referências [2] e [3] da bibliografia. Elas apresentam definições completas para construções de cenários, além de exemplos. Os cenários do grupo avaliador (Grupo 05 - [Simplenote](https://github.com/Requisitos-de-Software/2023.1-Simplenote)) foram baseados pricipalmente no modelo apresentado em [3].

## Bibliografia
[1] SALES, ANDRÉ B. [Plano de ensino da disciplina de Requisitos de Software](https://aprender3.unb.br/pluginfile.php/2523005/mod_resource/content/28/Plano_de_Ensino%20RE%20202301%20Turma%202.pdf). Universidade de Brasília. 2023

[2] LEITE, J. C. S. P. et al. Enhancing a requirements baseline with scenarios. In:
PROC. OF THE THIRD IEEE INTERNATIONAL SYMPOSIUM ON
REQUIREMENTS ENGINEERING (RE’97), IEEE Computer Society Press,
1997. p. 193-195

[3] SERRANO, M. SERRANO, M. Requisitos - Aula 10, Modelagem de Requisitos. p. 8-11 

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)       |
| ------ | ------------- | ---------------------------------- | ------------- | ------------------ |
| `1.0`  | 09/06/2023    | Criação do documento.              |  Leonardo         | Beatriz |
