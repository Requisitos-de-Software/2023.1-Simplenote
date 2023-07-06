# First things First (FTF)
## Participantes
|Nome|Função|
|----|------|
|Kauã| Mediador|
|[Carla Araújo](https://github.com/ccarlaa)|Desenvolvedora|
|[Bruno Henrique](https://github.com/bdebatata)|PO|

<p>Tabela 1: Participantes.(Fonte:Autor)</p>

## Introdução
Este artefacto é referente ao documento da tecnica de priorização First things first relativo aos requisitos elicitados pelo [grupo 5](https://github.com/Requisitos-de-Software/2023.1-Simplenote) da turma de requisitos de software da Universidade de Brasília 2023/1.

## Definição

First things First ou FTF é uma técnica de priorização que busca entender os riscos, custos e o valor de cada requisito para um produto de software que normalmente tem uma grande escala, já que em projetos pequenos as prioridades se dão normalmente de maneira informal[2](#ancora2). No geral, esta tecnica faz uma analise mais fria, industrial e matemática a respeito de cada requisito, entendendo-os como a parcela de um todo, sendo assim, é feito uma analise semi-quantitativa( matemáticamente não tão rigoroso) a respeito de cada requisito, valorando-os em pontos como agregação ao produto em caso de ganho ou perda, dificuldade de implementação e custo de impementação. A seguir temos as etapas para realizar a técnica em questão :

#### Passo a passo para realizar a técnica:

1. Listar todos os requisitos, se um requisito A se liga com um requisito B, deve-se levar em conta apenas o A.
2. Estimar o valor de cada requisito para o cliente com uma escala de 1 a 9, em que 1 é pouco valoroso e 9 é muito valoroso, é importante a participação do cliente.
3. Estimar uma penalidade que o negócio sofreria na falta daquele requisito seguindo a mesma escala anterior.
4. Criar uma coluna valor total, na qual

         Vtotal = (Beneficio relativo * Peso relativo) + (Penalidade relativa * Peso relativo).
   
5. Estimar o custo relativo de implementação seguindo a escala já conhecida, este custo deve levar em conta: a complexidade de implementação, UI necessária, reúso de telas, etc
6. Estimar o risco da implementação de um requisito.
7. Calcular a prioridade dos requisitos com:
   
         Prioridade = Valor% / (Custo% * PesoCusto + Risco % * PesoRisco)
   
8. Ordenar a lista de forma decrescente de prioridade. Os requisitos do topo tem maior prioridade de implementação. Os stakeholders devem ter acesso a mesma.

## Metodologia

Para realizar a etapa de priorização, foi reunido todos os requisitos elicitados pelo projeto atavés das etapas de:

- [Brainstorming](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/)
- [Entrevista](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/)
- [Glossário](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/)
- [Instrospecção](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/)
- [Storytelling](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/)

Em seguida, foi feito uma filtragem dos requisitos obtidos afim de que possa ter uma amostragem de dados mais consistênte e menos repetitiva. Após, foi montado uma tabela no excel nos quais foram inseridos os requisitos já filtrados e com seus respectivos códigos(podendo ser mais de um) além dos campos para os pesos de cada requisito e a sua prioridade final. Com a tabela em mãos, foram feitas duas reuniões, uma com o PO do projeto, e outra com a lider da equipe de desenvolvedores. Seguem as informações das mesmas:

Reunião com o PO:

- Nome: Bruno Henrique.
- Dia e Horário: 18 de junho de 2023 às 21H;
- Ambiente: Teams.
- Link para a reunião: <https://youtu.be/D4a7vA9LOOg>

<br>
Reunião com a lider da equipe de desenvolvimento:

- Nome: Carla Araújo.
- Dia e Horário: 19 de junho de 2023 às 14H;
- Ambiente: Teams.
- Link para a reunião: <https://youtu.be/RKZUsCj00us>

Ao fim da reunião, foi ordenado a tabela com a prioridade dos requisitos em ordem crescente e aplicado um gradiente nas celulas relativas a esta informação de cada requisito.

## Resultados

A planilha 1 mostra os resultados alcançados após a priorização dos requisitos: </br>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSmDdYYUuEdBZfqWU2-2GBiffaU2Fhas8h2KMDUmtkTYc6B99i9V0BVxO0w4nTVIxdlap1tYpi52Y-_/pubhtml?gid=1831982803&amp;single=true&amp;widget=true&amp;headers=false" width="100%" height="600" frameborder="0" scrolling="yes"></iframe>

<p align="center"> Planilha 1: Planilha de priorização FTF <br> Fonte: autores <br> Autores: João e Kauã </p>

### Legenda:
- INT: Introspecção
- B: Brainstorming
- ENT: Entrevista
- GLO: Glossário
- ST: Storytelling

## Bibliografia

> [1] Slides Requisitos - aula 15. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise.</br>
>
> [2] First Things First: Prioritizing Requirements Karl E. Wiegers

## Histórico de versão

| Versão |    Data    |                         Descrição                          |    Autor    | Revisor |
| :----: | :--------: | :--------------------------------------------------------: | :---------: | :-----: |
|  `1.0` | 28/04/2023 |                 Inicialização do documento                 | Kauã e João | Mylena  |
|  `1.1` | 29/04/2023 | Confecção da tabela e preenchimento inicial dos requisitos | João e Kauã | Mylena  |
|  `1.2` | 01/05/2023 |   Finalizando o documento e adicionando tabela ordenada    | Kauã e João | Mylena  |
|  `1.3` | 15/05/2023 |                Ajustes Feedbacks entrega 2                 | Ana Beatriz | Mylena  |
|  `1.4` | 26/06/2023 |       Correção do documento após entrega 5.1               | Kauã        | Mylena  |
