# Verificação - Casos de Uso

## Introdução

Este documento é destinado para a revisão do [documento Casos de Uso](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/) do grupo 5 - [Simplenote](https://github.com/Requisitos-de-Software/2023.1-Simplenote), vale ressaltar que a avaliação é feita de maneira imparcial, sem a intenção de atacar ninguém.Foi avaliado a versão 1.1 do documento no dia 20/06/2023.

## Metodologia

A verificação foi feita por meio da insperção, utilizando um checklist criado com base no plano de ensino da disciplina de requisitos de software e nas obras que estão citadas na bibliografia. A principio, foram criadas duas tabelas nas quais, temos 3 campos, "Questão": pergunta que será respondida, "Resposta" na qual como resultados válidos, podemos ter:

- Sim : caso um critério for atendido.
- Não : caso um critério não for atendido.
- Incompleto : caso um critério for parcialmente atendido.

Foi utilizada a *checklist* de verificação elaborada pelo Grupo 4 ([Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/Verificacao/Grupo5/Entrega1/Entrega1/)) para definir parte dos itens da *checklist* deste artefato. Os itens do Grupo 4 que foram acatados estão referenciados para o documento de verificação elaborado e também possuem respaldo em algum documento da bibliografia usada na elaboração do *checklist* 

## Checklist de documento
Para avaliação do documento em aspectos formais e tecnicos, foi criado a tabela 1. Segue:

|ID|Questão|Resposta|Observação|
|--|-------|--------|----------|
|1|O artefato possui Introdução?                                                                                |   sim     |          |
|2|O artefato artefato possui uma Bibliografia/Referência Bibliográfica?                                        |   sim     | Poderia melhorar a formatação da bibliografia |
|3|O artefato possui um Histórico de Versões com o id e descrição das versões, data, autores e revisores?       |   sim     |          |
|4|Todos os textos estão na norma padrão?                                                                       |   sim     |          |
|5|As tabelas são chamadas no texto?                                                                            |   não     |          |
|6|Os revisores são pessoas diferentes dos autores?                                                             |   sim     |          |

<p align="center"> Tabela 1 - Checklist do documento <br> Fonte: autores </p>

## Checklist do conteúdo

| ID   | Questão | Resposta | Observação | Referências |
| ---- | ------- | -------- | ---------- |-------------|
|  7   | É citada qual técnica/metodologia foi utilizada para desenvolver o diagrama de casos de Uso?        | sim     |            | [2](#ancora2)     |
|  8   | O diagrama de caso de uso possui atores?                                                            | sim     |            | [1](#ancora1)     |
|  9   | O ator principal está do lado esquerdo do sistema?                                                  | sim     |            | [1](#ancora1) e [2](#ancora2)    |
|  10  | Os atores estão fora da fronteira do sistema?                                                       | sim     |            | [1](#ancora1) e [2](#ancora2)     |
|  11  | Os atores interagem com os Casos de Uso corretamente?                                               | sim     |            | [1](#ancora1) e [2](#ancora2)     |
|  12  | Existe multiplicidade entre ator e Caso de Uso?                                                     | sim         |            | [1](#ancora1)     |
|  13  | Há algum nome associado ao(s) usuário(s) do sistema?                                                | sim         |            | [1](#ancora1)     |
|  14  | Existe limite do sistema?                                                                           | sim         |            | [1](#ancora1)     |
|  15  | Os casos de uso possuem especificações?                                                             | Incompleto  | Obs. abaixo           | [1](#ancora1)     |
|  16  | Os casos de uso possuem rastreabilidade?                                                            | Incompleto  | Obs. abaixo          | [1](#ancora1)     |
|  17  | Os fluxos alternativos representam possibilidades de cenários alternativos para o fluxo principal?  | Incompleto  | Obs. abaixo          | [1](#ancora1)     |
|  18  | Ator é uma pessoa, organização ou sistema externo que interage com seu aplicativo ou sistema?       |  Não        | Obs. abaixo        | [2](#ancora2)     |



<p align="center"> Tabela 2 - Checklist dos pontos relativos ao conteúdo <br> Fonte: autores </p>

## Observações e Problemas encontrados

### ID15,ID16,ID17

Falta a do caso de uso de fazer login ou fazer Cadastro ou acessar as notas.

### ID18

O sistema backend não deveria ser ator, pois ele não é uma pessoa, organização ou sistema externo.[2](#ancora2)

## Sugestões

## Bibliografia

> [1] Serrano, Milene; Serrano, Maurício. Requisitos aula 13. Disponivel em [aprender3](https://aprender3.unb.br/pluginfile.php/2523100/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em 20/06/2023. 
>
> [2] Diagrama de caso de uso UML: O que é, como fazer e exemplos. Disponivel em [lucidchart](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml). Acesso em 20/06/2023.

## Histórico de Versão

| Versão | Data       | Descrição             | Autor(es)    | Revisor(es)        |
| ------ | ---------- | --------------------- | ------------ | ------------------ |
| `1.0`  | 20/06/2023 | Criação do documento. | Beatriz      | Ana Beatriz            |
