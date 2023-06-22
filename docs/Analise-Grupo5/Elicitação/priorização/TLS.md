# Verificação - Three Level Scale ou TLS

## Introdução

Este documento é destinado para a revisão do documento [Three Level Scale ou TLS](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Prioriza%C3%A7%C3%A3o/ThreeLevelScale/) do grupo 5 - [Simplenote](https://github.com/Requisitos-de-Software/2023.1-Simplenote), vale ressaltar que a avaliação é feita de maneira imparcial, sem a intenção de atacar ninguém. Foi avaliado a versão 1.3 do documento no dia 20/06/2023.

## Metodologia

A verificação foi feita por meio da insperção, utilizando um checklist criado com base no plano de ensino da disciplina de requisitos de software e nas obras que estão citadas na bibliografia. A principio, foram criadas duas tabelas nas quais, temos 3 campos, "Questão": pergunta que será respondida, "Resposta" na qual como resultados válidos, podemos ter:

- Sim : caso um critério for atendido.
- Não : caso um critério não for atendido.
- Incompleto : caso um critério for parcialmente atendido.

Também temos o campo "Observação", um campo no qual pode ser feito algum comentário a respeito da questão em específico. Posteriormente, neste mesmo documento, pode-se encontrar uma sessão na qual serão sumarizados todos os problemas do artefacto em estudo e outra nos quais se encontram as sugestões de soluções dos mesmos.

## Checklist de documento
Para avaliação do documento em aspectos formais e tecnicos, foi criado a tabela 1. Segue:

|ID|Questão|Resposta|Observação|
|--|-------|--------|----------|
|1|O artefato possui Introdução?                                                                                |   sim     |          |
|2|O artefato artefato possui uma Bibliografia/Referência Bibliográfica?                                        |   sim     | Poderia melhorar a forma que esta sendo feito a referencia         |
|3|O artefato possui um Histórico de Versões com o id e descrição das versões, data, autores e revisores?       |   sim     |          |
|4|Todos os textos estão na norma padrão?                                                                       |   sim     |          |
|5|As tabelas são chamadas no texto?                                                                            |   sim     |          |
|6|Os revisores são pessoas diferentes dos autores?                                                             |   sim     |          |

<p align="center"> Tabela 1 - Checklist do documento <br> Fonte: autores </p>

## Checklist do conteúdo

| ID  | Questão | Resposta | Observação | Referência |
| --- | ------- | -------- | ---------- | ------------ |
| 7   | A técnica que foi utilizada para priorização é descrita?                                    | sim 	  |                      | [1](#ancora1)  |
| 8   | Os requisitos são identificados em funcionais e não funcionais?                             | sim 	  |                      | [1](#ancora1)  |
| 9   | Os níveis de priorização foram divididos em 3 na tecnica TLE? ('Alta', 'Média' e 'Baixa')   | sim 	  |                      | [1](#ancora1)  |
| 10   | Foi utilizado um modelo de quadrante para enquadrar os requistitos entre prioridade 'Alta' (primeiro quadrante), 'Média' (segundo quadrante), 'Baixa (terceiro quadrante)' e requistos propostos com nenhum valor para o projeto (quarto quadrante)?               | sim 	  |                      | [1](#ancora1) |
| 11   | As dependências de requisitos foram levadas em consideração no processo de ranqueamento?   | não 	  | Explicação abaixo    | [1](#ancora1) |
| 12   | Os requisitos funcionais descrevem as funções que o software deve executar?                | sim 	  |                      | [2](#ancora2) |
| 13   | Os requisitos não funcionais são restrições ou requisitos de qualidade?                    | sim 	  |                      | [2](#ancora2) |
| 14   | Os requisitos são unicos e não se repetem?                                                 | não 	  | Existem requisitos repetidos. | |

<p align="center"> Tabela 2 - Checklist dos pontos relativos ao conteúdo <br> Fonte: autores </p>

## Observações e Problemas encontrados

### ID11

Não é explicitado as dependências dos requisitos.

## Sugestão

- Tirar os requisitos repetidos
- Desmostrar que as depedências foram levadas em consideração

## Bibliografia

> [1] Wiegers, Karl; Beatty, Joy. Software Requiriments. Disponível em [aprender3](https://aprender3.unb.br/pluginfile.php/2523072/mod_resource/content/2/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf). Acesso em 20 de jun de 2023.
>
> [2] BOURQUE, Pierre; FAIRLEY, Richard.E ; Guide to the Software Engineering Body of Knowledge. Disponível em: [Aprender3](https://aprender3.unb.br/pluginfile.php/2523020/mod_resource/content/1/SWEBOKv3.pdf). Acesso em: 20 de junho de 2023.

## Histórico de Versão

| Versão | Data       | Descrição             | Autor(es) | Revisor(es)        |
| ------ | ---------- | --------------------- | --------- | ------------------ |
| `1.0`  | 20/06/2023 | Criação do documento. | Beatriz   | Ana Beatriz            |
