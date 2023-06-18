# First things First (FTF)

## Definição

First things First ou FTF é uma técnica de priorização que busca entender os riscos, custos e o valor de cada requisito para um produto, avaliando-os através de pesos para chegar em uma lista de prioridade.


## Passo a passo

1. Listar todos os requisitos, se um requisito A se liga com um requisito B, deve-se levar em conta apenas o A.
2. Estimar o valor de cada requisito para o cliente com uma escala de 1 a 9, em que 1 é pouco valoroso e 9 é muito valoroso, é importante a participação do cliente.
3. Estimar uma penalidade que o negócio sofreria na falta daquele requisito seguindo a mesma escala anterior.
4. Criar uma coluna valor total, na qual Vtotal = (Beneficio relativo * Peso relativo) + (Penalidade relativa * Peso relativo).
5. Estimar o custo relativo de implementação seguindo a escala já conhecida, este custo deve levar em conta: a complexidade de implementação, UI necessária, reúso de telas, etc
6. Estimar o risco da implementação de um requisito.
7. Calcular a prioridade dos requisitos com: prioridade = valor % / (custo % * peso_custo + risco % * peso_risco)
8. Ordenar a lista de forma decrescente de prioridade. Os requisitos do topo tem maior prioridade de implementação. Os stakeholders devem ter acesso a mesma.

## Métodos

Para realizar a análise de priorização, foram utilizados os seguintes métodos: Introspecção, Brainstorming, Entrevista, Glossário, Questionário e Storytelling. A participação do usuário ([personas](../personas.md)) foi essencial nos passos 2 e 3, contribuindo para a definição do valor e da penalidade de cada requisito.

- Data: 28 de abril de 2023 e 29 de abril de 2023
- Horário: 10:00 e 20:30
- Local: Campus FGA - UnB e Discord

Após a discusão do grupo, chegou-se ao concenso de que os custos relativos a desenvolvimento seria do valor 1, agora, para os de usuário, foi atribuído 1 para o maleficio de perda e 2 para o benefício.

## Resultados

A planilha 1 mostra os resultados alcançados após a priorização dos requisitos: </br>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSmDdYYUuEdBZfqWU2-2GBiffaU2Fhas8h2KMDUmtkTYc6B99i9V0BVxO0w4nTVIxdlap1tYpi52Y-_/pubhtml?gid=1831982803&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

<p align="center"> Planilha 1: Planilha de priorização FTF <br> Fonte: autores <br> Autores: João e Kauã </p>

### Legenda:
- INT: Introspecção
- B: Brainstorming
- ENT: Entrevista
- GLO: Glossário
- QUE: Questionário
- ST: Storytelling


## Bibliografia

Slides Requisitos - aula 15. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise.

## Histórico de versão

| Versão |    Data    |                         Descrição                          |    Autor    | Revisor |
| :----: | :--------: | :--------------------------------------------------------: | :---------: | :-----: |
|  `1.0` | 28/04/2023 |                 Inicialização do documento                 | Kauã e João | Mylena  |
|  `1.1` | 29/04/2023 | Confecção da tabela e preenchimento inicial dos requisitos | João e Kauã | Mylena  |
|  `1.2` | 01/05/2023 |   Finalizando o documento e adicionando tabela ordenada    | Kauã e João | Mylena  |
|  `1.3` | 15/05/2023 |                Ajustes Feedbacks entrega 2                 | Ana Beatriz | Mylena  |
