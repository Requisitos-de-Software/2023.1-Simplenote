# NFR framework

## Introdução
NFR é um framework conceitual que utiliza o modelo Softgoal Interdependency Graph (SIG). Ele tem como foco os requisitos Não-Funcionais do aplicativo. 
O Framework utiliza de softgoals, um objetivo que não possui uma clara definição nem critérios de satisfação precisos. São utilizados para representar Requisitos 
Não-Funcionais e podem estar inter-relacionados, expressando a influência de uma softgoal em outro. [¹](#ancora1)

### Requisitos Não Funcionais Elicitados

| ID | Requisito | Fonte |
|----|-----------|-------|
|RN01| bla       | [link](nome)|

### Softgoals

Os softgoals são separados em 3 tipos: [¹](#ancora1)

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

Esse refinamento são especificações dos softgoals e são contribuições e existe 10 tipos. Esses são: [¹](#ancora1)

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
 
## Participantes 

|Nome | Cargo | Técnica | 
|-----|-------|---------|
|Beatriz| Equipe de modelagem| Modelagem |
|Leonardo | Equipe de priorização| Entrevistas da elicitação|
|Mylena | Equipe de elicitação| Público alvo: questionário|
|Paulo | Product Owner | Membro do grupo 4 |
 
## Legendas

### Softgoals

<div align="center">
  
<img src="../img/legenda.png">
  
</div>

<div align="center">
 Figura 1: Legenda Softgoals
</div>


### Rótulos

<div align="center">
  
<img src="../img/RótulosNFR.png">
  
</div>

<div align="center">
 Figura 2: Legenda Rótulos, Fonte: NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados.¹
</div>

<p></p>

Descrição: [¹](#ancora1)

<p></p>

- Satisfeito: Reflete que um requisito não funcional contribui de maneira positiva para a realização de outro requisito, resultando em satisfação.
- Fracamente satisfeito: ndica uma relação de impacto positiva, mas menos forte do que a notação satisfeito.
- Negado: Demonstrando que um requisito não funcional afeta adversamente outro requisito, anulando ou contradizendo sua concretização.
- Fracamente negado: Similar à notação negado, mas com uma relação de negação mais fraca.
- Conflitante: Indica uma relação de conflito entre requisitos não funcionais. Isso implica que os requisitos possuem características tanto positivas quanto negativas.
- Indeterminado: Refere-se a uma relação incerta ou desconhecida entre requisitos não funcionais. Isso ocorre quando há informações insuficientes para determinar o impacto de um requisito em outro.

## NFR
 Foram feitos 4 tipos de NFR: usabilidade (figura 2), disponibilidade (figura 3), portabilidade (figura 4) e performance (figura 5).

## NFR-1 Usabilidade

### Sem Propagação

<div align="center">
<img src="../img/NFR_USABILIDADEV2.png">
</div>

<div align="center">
Figura 3: NFR-1 Usabilidade Sem Propagação, Autor(a): Beatriz 
</div>

### Com Propagação

 <div align="center">
<img src="../img/Propag_USABILIDADE.png">
</div>

<div align="center">
Figura 4: NFR-1 Usabilidade com Propagação, Autor(a): Beatriz
</div>

### Requisitos

| ID | Requisito |
|----|-----------|
|RN01|           |

### Cartões de Especificação

| Classificação         |  | 
| ----------------------|--|
| Descrição             |  |
| Justificativa         |  |
| Origem do requisito   |  |
| Critério de aceitação |  |
| Prioridade            |  |
| Conflito              |  |
| Historia              |  |



## NFR-2 Disponibilidade

### Sem Propagação
<div align="center">
 
<img src="../img/disponibilidade.png">
<figcaption>Figura 5: NFR-2 Disponibilidade, Autor(a): Mylena </figcaption>
 
</div>

### Com Propagação

 <div align="center">
 
<img src="../img/PropDisponibilidade.png">
<figcaption>Figura 6: NFR-1 Disponibilidade com Propagação, Autor(a): Beatriz </figcaption>
 
</div>

## NFR-3 Portabilidade

### Sem Propagação
<div align="center">
<img src="../img/portabilidade.png">
</div>

<div align="center">
Figura 7: NFR-3 Portabilidade, Autor(a): Beatriz  </figcaption>
</div>

 ### Com Propagação

 <div align="center">
<img src="../img/PropagPortabilidade.png">
 </div>
 
 <div align="center">
Figura 8: NFR-1 Portabilidade com Propagação, Autor(a): Beatriz 
</div>

## NFR-4 Performance

### Sem Propagação

 <div align="center"> 
  <img src="../img/performance.png">
  </div>
 
  <div align="center">
 Figura 9: NFR-4 Performance, Autor(a): Leonardo 
 </div>

  ### Com Propagação

 <div align="center">
<img src="../img/PropagPerformance.png">
</div>

<div align="center">
Figura 10: NFR-1 Performance com Propagação, Autor(a): Beatriz </figcaption>
</div>

## Referências

> [1] SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 26/06/2023
> 

## Histórico de versão

| Versão | Data | Descrição| Autor(es) | Revisor(es)
|--|--|--|--|--|
|`1.0` | 14/05/2023 | Criação da documentação| Mylena, Beatriz e Leonardo |Ana Beatriz|
|`2.0` | 26/06/2023 | Adicionando Propagação, RNF elicitados e Cartões de Especificação| Beatriz |Ana Beatriz|
