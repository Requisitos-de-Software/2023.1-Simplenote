# NFR framework

## Introdução
NFR é um framework conceitual que utiliza o modelo Softgoal Interdependency Graph (SIG). Ele tem como foco os requisitos Não-Funcionais do aplicativo. 
O Framework utiliza de softgoals, um objetivo que não possui uma clara definição nem critérios de satisfação precisos. São utilizados para representar Requisitos 
Não-Funcionais e podem estar inter-relacionados, expressando a influência de uma softgoal em outro.

Os softgoals são separados em 3 tipos:
- NFR Softgoal: É um requisito não-funcional que é considerado durante a análise, a fim de determinar se ele será ou não implementado. 
Esses requisitos são vistos como atributos de qualidade e são avaliados para garantir que o produto final atenda aos padrões desejados. Em outras palavras, eles são critérios usados para avaliar a qualidade do produto.
- Softgoal de Operacionalização: São funcionalidades que permitem viabilizar ou não as características abstratas. Ou seja, elas são responsáveis por transformar os requisitos não-funcionais em funcionalidades tangíveis, que podem ser implementadas no sistema. 
Em resumo, as funcionalidades são a materialização das características abstratas em algo concreto e mensurável
- Claim Softgoal (Argumentation): É a notação que pode ser adicionada ao modelo para argumentar um ponto específico da modelagem e é escrita em linguagem natural. 
Essa notação é uma forma de expressar ideias ou justificativas sobre o modelo e pode ajudar a explicar o raciocínio por trás de certas escolhas.

Além dessa separação, cada um desses softgoals podem ser especificados, serem descritos em formade sub-requisitos:
- Decomposição de Softgoal NFR: Essa técnica que permite uma melhor organização e compreensão dos softgoals NFR.
- Decomposição de Operacionalização: Essa técnica possibilita a definição de uma solução geral e a criação de casos mais especificos.
- Decomposição de Afirmação (Claims): Essa técnica permite reafirmar ou negar as justificativas específicas do projeto.
- Priorização: Essa é um tipo especial de separação, na qual um softgoal é refinado em outro softgoal com o mesmo tipo e tópicos, mas com uma prioridade associada.

Esse refinamento são especificações dos softgoals e são contribuições e existe 10 tipos. Esses são:

| Contribuição       | Descrição  | Notação    |  
| ------------------ | ---------- | ---------- |
| *MAKE*  | FILHO com contribuição tão positiva a ponto de satisfazer o PAI sob a perspectiva dos envolvidos. | ++     | 
| *HELP*  | FILHO com contribuição positiva parcial, que sozinho não chega a satisfazer o PAI sob a perspectiva dos envolvidos. | +     |  
| *UNKNOWN*  | FILHO não afeta o PAI. | ?    |
| *HURT*   | FILHO com contribuição negativa parcial, que sozinho não chega a negar o PAI sob a perspectiva dos envolvidos. | -| 
| *BREAK*    | FILHO com contribuição tão negativa a ponto de negar o PAI sob a perspectiva dos envolvidos| --| 
| *SOME +*   | FILHO com contribuição positiva, cuja intensidade não se pode determinar. | SOME + | 
| *SOME -*   | FILHO com contribuição negativa, cuja intensidade não se pode determinar | SOME - | 
| *AND*    | “Pai” é satisfeito se_somente_se todos os “filhos” forem satisfeitos sob a perspectiva dos envolvidos| AND|
| *OR* | “Pai” é satisfeito se_somente_se um dos “filhos” é satisfeito sob a perspectiva dos envolvidos |OR|    
| *EQUAL* | Ambos compartilham o mesmo label| =| 
  
  
## Referências

[1] Repositório de disciplina do semestre passado- Lichess

[2] Slides da aula da professora Milene.

## Histórico de versão

| Versão | Data | Descrição| Autor(es) | Revisor(es)
|--|--|--|--|--|
|`1.0` | 14/05/2023 | Criação da documentação| Mylena, Beatriz e Leonardo |Ana Beatriz|
