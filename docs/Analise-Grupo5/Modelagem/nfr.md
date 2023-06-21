# Verificação - NFR Framework

## Introdução

Este documento é destinado para a revisão do artefato [NFR Framework](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/) do grupo 5 - [Simplenote](https://github.com/Requisitos-de-Software/2023.1-Simplenote), vale ressaltar que a avaliação é feita de maneira imparcial, sem a intenção de atacar ninguém.Foi avaliado a versão 1.0 do documento no dia 21/06/2023.

## Metodologia

A verificação foi feita por meio da insperção, utilizando um checklist criado com base nas obras que estão citadas na bibliografia. A principio, foram criadas duas tabelas nas quais, temos 3 campos, "Questão": pergunta que será respondida, "Resposta" na qual como resultados válidos, podemos ter:

- Sim : caso um critério for atendido.
- Não : caso um critério não for atendido.
- Incompleto : caso um critério for parcialmente atendido.

Também temos o campo "Observação", um campo no qual pode ser feito algum comentário a respeito da questão em específico. Posteriormente, neste mesmo documento, pode-se encontrar uma sessão na qual serão sumarizados todos os problemas do artefacto em estudo e outra nos quais se encontram as sugestões de soluções dos mesmos.

## Checklist de documento
Para avaliação do documento em aspectos formais e tecnicos, foi criado a tabela 1. Segue:

|ID|Questão|Resposta|Observação|
|--|-------|--------|----------|
|1|O artefato possui Introdução?                                                                                |   Sim     |          |
|2|O artefato artefato possui uma Bibliografia/Referência Bibliográfica?                                        |   Sim     |          |
|3|O artefato possui um Histórico de Versões com o id e descrição das versões, data, autores e revisores?       |    Sim    |          |
|4|Todos os textos estão na norma padrão?                                                                       |   Sim     |          |
|5|As tabelas são chamadas no texto?                                                                            |    Incompleto    |    Há NFRs que não são mencionados em texto      |
|6|Os revisores são pessoas diferentes dos autores?                                                             |     Sim   |          |
|7|As referências bibliográficas são utilizadas no texto do documento? | Não | |

<p align="center"> Tabela 1 - Checklist do documento <br> Fonte: autores </p>

## Checklist do conteúdo

| ID  | Questão | Resposta | Observação | Referências |
| --- | ------- | -------- | ---------- |     -       |
| 8 |No documento NFR possui uma legendas explicando os símbolos utilizados?                                        |    Sim    |          | [1] |
| 9 |Os NFR estão documentados de forma organizada, acessível e clara na modelagem?                                 |    Incompleto    |     Não é explicado a diferença entre os tipos de NFR     |[1]|
| 10 |Os NFR são identificados com atributos específicos, como desempenho, segurança, usabilidade, etc?              |    Sim    |          |[1]|
|11 |Os Softgoals NFR representam os Requisitos Não-Funcionais?                                                     |     Sim   |          |[1]|
|12 |Os Softgoals de Operacionalização representam soluções de implementação para satisfazer softgoals NFR ou outros softgoals de operacionalização? |    Sim    |  |[1]|
|13 |Os Softgoals de Afirmação permitem que as características do domínio (como prioridades e carga de trabalho) sejam consideradas e devidamente refletidas no processo de tomada de decisão?  |    Sim    |          |[1]|
|14 |O procedimento de avaliação determina o grau que os requisitos não funcionais são satisfeitos por um conjunto de decisões? | Não |  |[1]  |
|15| Os tipos de rótulos utilizados são: satisfeito, fracamente satisfeito, negado, fracamente negado, conflitante, indeterminado? | Sim | |[1]|

<p align="center"> Tabela 2 - Checklist dos pontos relativos ao conteúdo <br> Fonte: autores </p>

## Observações e Problemas encontrados

### ID5

Não há menção dos diagramas NFR de Usabilidade, Disponibilidade e Portabilidade em texto no documento.

## ID7 

As referências presentes na bibliografia não são citadas em outras partes do documento.

## ID9

Não é mencionado qual a fonte dos NFRs elaborados. Por exemplo, se foram extraídos de outros documentos de modelagem.

## ID14

A satisfação dos requisitos não funcinais é mostrada apenas no diagrama, porém não é esclarecida em texto.

## Sugestões

Mencionar os diagramas em texto, citar as referências bibliográficas usadas, informar a fonte dos NFRs, e escrever parágrafos abaixo de cada diagrama explicando como os NFRs foram satisfeitos.

## Bibliografia

[1] SILVA, R. A. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Universidade Federal de Pernambuco. Recife. 2019. p. 30-39.

## Histórico de Versão

| Versão | Data       | Descrição             | Autor(es) | Revisor(es)        |
| ------ | ---------- | --------------------- | --------- | ------------------ |
| `1.0`  | 18/06/2023 | Criação do documento. | Leonardo      | Beatriz            |
