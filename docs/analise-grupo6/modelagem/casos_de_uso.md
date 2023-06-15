# Verificação - Casos de Uso

## Introdução
Este documento é destinado para a revisão do artefato de [casos de uso](https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/) 
do grupo 6 - [Letterbox](https://github.com/Requisitos-de-Software/2023.1-Letterboxd), vale ressaltar que a avaliação é feita de maneira imparcial,
sem a intenção de atacar ninguém.
<br> Foi analisado a versão 1.1 do documento, no dia 13/06/2023.

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
|04|Todos os textos estão na norma padrão?                                                                       |    Não    | No parágrafo do tópico 3 encontra-se a palavra "digrama" que deveria ser "diagrama"         |
|05|Os revisores são pessoas diferentes dos autores?                                                             |    Sim    |          |

Tabela 1 - Checklist do documento - (Fonte: Autor,2023)

## Checklist do conteúdo
|ID|Questão|Resposta|Observação|
|-|-------|--------|----------|
|06| É citada qual técnica/metodologia foi utilizada para desenvolver o diagrama de casos de Uso? | Não | Não é citada a técnica utilizada para o desenvolvimento. |
|07| O diagrama de caso de uso possui atores?   | Sim | |
|08| O ator principal está do lado esquerdo do sistema? | Sim |  |
|09| Os atores estão fora da fronteira do sistema? | Sim |  |
|10| Os atores interagem com os Casos de Uso? | Sim |  |
|11| Existe multiplicidade entre ator e Caso de Uso? | Não | Não foi encontrado relação de multiplicidade entre os atores e os casos de uso. |
|12| Possui relação de extend ou include? | Sim | Muito bem utilizado. Pontuando até mesmo se a relação ocorre dependendo da interação do usuário no sistema. |
|13| Há algum nome associado ao(s) usuário(s) do sistema | Sim |  |
|14| Há tag << system >> quando o ator é representa um software ou hardware? | Não | Não foi encontrada a tag system no Servidor. |
|15| Os casos de uso representam o usuário e suas diferentes interações com o sistema? | Sim |  |
|16| Existe limite do sistema? | Sim |  |
|17| Os fluxos principais representam como a aplicação seria utilizada pelo usuário de forma esperada? | Sim |  |
|18| Os fluxos alternativos representam possibilidades de cenários alternativos para o fluxo principal? | Incompleto | Existem fluxos alternativos que deviam compor o fluxo principal. |
|19| Os fluxos de exceção demonstram a resposta do sistema diante de situações inesperadas?| Não | Não foi apresentado nenhum fluxo de exceção |
|20| Os casos de uso possuem rastreabilidade? | Sim |  |
|21| Os casos de uso possuem especificações? | Sim |  |


Tabela 2 - Checklist do conteúdo

## Problemas encontrados e sugestões
### ID 06
Citar a técnica utilizada para o desenvolvimento do diagrama de casos de uso.
### ID 11
Adicionar relações de multiplidade para as interações.
### ID 14
Adicionar a tag <<System>> para o Servidor que está incluído no diagrama.
### ID 18
O fluxo alternativo do UC05 compõe o fluxo principal ou até mesmo outro caso de uso.
### ID 19
Adicionar possíveis fluxos de exceção que podem ser encontrados nos casos de uso.


## Bibliografia
[1] SALES, ANDRÉ B. [Plano de ensino da disciplina de Requisitos de Software](https://aprender3.unb.br/pluginfile.php/2523005/mod_resource/content/28/Plano_de_Ensino%20RE%20202301%20Turma%202.pdf). Universidade de Brasília. 2023
[1] “Requisitos – Aula 11” dos professores Milene Serrano e Maurício Serrano. Disponível em: https://aprender3.unb.br/pluginfile.php/2523100/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Univerdade de Brasilia. Acesso em 2023.



## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)       |
| ------ | ------------- | ---------------------------------- | ------------- | ------------------ |
| `1.0`  | 13/06/2023    | Criação do documento.              |  Ian         | - |
| `1.1`  | 13/06/2023    | Adicionando novas verificações e corrigindo antigas. |  Ian         | - |
