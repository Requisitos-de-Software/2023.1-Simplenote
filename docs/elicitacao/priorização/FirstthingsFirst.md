# First things First (FTF)

## Definição

First things First ou FTF é uma tecnica de priorização que busca entender os riscos, custos e o valor de cada requisito para um produto, avaliando-os através de pesos e afim de chegar em uma lista de prioridade.

## Passo a passo

1. Listar todos os requisitos, se um requisito A se liga com um requisito B, deve-se levar em conta apenas o A.
2. Estime o valor de cada requisito para o cliente com uma escala de 1 a 9, em que 1 é pouco valorozo e 9 é muito valorozo, é importante a participação do cliente.
3. Estime uma penalidade que o négocio sofreria na falta daquele requisito seguindo a mesma escala anterior.
4. Crie uma coluna valor total, na qual Vtotal = (Beneficio relativo * Peso relativo) + (Penalidade relativa * Peso relativo).
5. Estime o custo relativo de implementação seguindo a escala já conhecida, este custo deve levar em conta: a complexidade de implementação, UI necessária, reuso de telas, etc
6. Estime o quão dificil é a implementação de um requisito.
7. Calcule a prioridade dos requisitos com: prioridade = valor % / (custo % * peso_custo + risco % * peso_risco)
8. Ordene a lista de forma decrescente de prioridade. Os requisitos do topo tem maior prioridade de implementação. Os stakeholders devem ter acesso a mesma.

## Resultados

A tabela a seguir mostra os resultados alcançados após a priorização dos requisitos:



## Bibliografia

[1] https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf

## Histórico de versão
| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 28/04/2023 | Inicialização do docimento | Kauã e João | Mylena |

