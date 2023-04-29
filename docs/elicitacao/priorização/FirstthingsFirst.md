# First things First (FTF)

## Definição

First things First ou FTF é uma técnica de priorização que busca entender os riscos, custos e o valor de cada requisito para um produto, avaliando-os através de pesos para chegar em uma lista de prioridade.

## Passo a passo

1. Listar todos os requisitos, se um requisito A se liga com um requisito B, deve-se levar em conta apenas o A.
2. Estime o valor de cada requisito para o cliente com uma escala de 1 a 9, em que 1 é pouco valoroso e 9 é muito valoroso, é importante a participação do cliente.
3. Estime uma penalidade que o negócio sofreria na falta daquele requisito seguindo a mesma escala anterior.
4. Crie uma coluna valor total, na qual Vtotal = (Beneficio relativo * Peso relativo) + (Penalidade relativa * Peso relativo).
5. Estime o custo relativo de implementação seguindo a escala já conhecida, este custo deve levar em conta: a complexidade de implementação, UI necessária, reúso de telas, etc
6. Estime o risco da implementação de um requisito.
7. Calcule a prioridade dos requisitos com: prioridade = valor % / (custo % * peso_custo + risco % * peso_risco)
8. Ordene a lista de forma decrescente de prioridade. Os requisitos do topo tem maior prioridade de implementação. Os stakeholders devem ter acesso a mesma.

## Resultados

A tabela a seguir mostra os resultados alcançados após a priorização dos requisitos:

| Código | Requisito | Valor | Penalidade | Valor total | Valor total (%)| Custo relativo | Custo (%) | Risco |Risco (%) |Prioridade |
| :--------: | :----: | :----: | :-----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :----: | 
| INT01  | O usuário deve poder fazer anotação   | 9     | 9          | 27   | 8,06%     | 3  | 5,17%     | 2              | 4,44%   | 0,84       |
| INT02  | O usuário deve poder excluir anotação  | 9     | 8          | 26  | 7,76%     | 2    | 3,45%     | 1              | 2,22%   | 1,37       |
| INT03  | O usuário deve poder recuperar anotação excluida    | 6     | 3  | 15   | 4,48%     | 5   | 8,62%     | 4         | 8,89%   | 0,26       |
| INT04  | O usuário poderá compartilhar suas anotações com outras pessoas atraves de um link | 6 | 5  | 17 | 5,07%     | 2  | 3,45%     | 4   | 8,89%   | 0,41       |
| INT05  | O usuário deve poder usar Markdown  | 3     | 1          | 7   | 2,09%     | 6   | 10,34%    | 5              | 11,11%  | 0,10       |
| INT06  | O usuário deve poder vizualizar Anotação    | 9     | 9 | 27 | 8,06%     | 2     | 3,45%     | 1              | 2,22%   | 1,42       |
| INT07  | O aplicativo salvará a nota em até 1 segundo  | 8     | 9  | 25  | 7,46%     | 2    | 3,45%     | 1              | 2,22%   | 1,32       |
| INT08  | Para o primeiro acesso do usuário, deve ter uma breve explicação sobre o aplicativo e as suas funcionalidades | 3 | 1  | 7   | 2,09%     | 1   | 1,72%     | 2       | 4,44%   | 0,34       |
| INT09  | O aplicativo abrirá em um tempo limite de até 2 segundos   | 8     | 8  | 24 |  7,16%     | 3   | 5,17%     | 2       | 4,44%   | 0,74    |
| INT10  | O usuário deveria poder fazer notas sem internet  | 9 | 9   | 27   | 8,06%     | 5     | 8,62%     | 3              | 6,67%   | 0,53       |
| INT11  | O usuário poderia separar suas notas em pastas | 6 | 7   | 19          | 5,67%     | 1  | 1,72%     | 2               | 4,44%   | 0,92       |
| INT12  | O usuário poderia definir templates para suas notas  | 4     | 3          | 11   | 3,28%     | 5   | 8,62%     | 4   | 8,89%   | 0,19       |
| INT13 | O usuário deve poder editar Anotação               | 9     | 9     | 27   | 8,06% | 1|1,72%        | 1|2,22%        | 2,04    |
| INT14 | O usuário deve poder buscar notas por palavras-chave | 7     | 2     | 16   | 4,78% |2| 3,45%  |2      | 4,44%        | 0,61    |
| INT15 | O usuário deveria poder pesquisar por suas anotações | 7     | 2     | 16   | 4,78% | 2| 3,45%     |2   | 4,44%        | 0,61    |
| INT16 | O usuário poderia ver informações sobre sua nota   | 6     | 5     | 17   | 5,07% |4| 6,90% |2       | 4,44%        | 0,45    |
| INT17 | O usuário poderia importar ou exportar modelos de layout | 2     | 1     | 5    | 1,49% |7| 12,07%  |5     | 11,11%       | 0,06    |
| INT18 | A interface deve ser simples e intuitivo           | 7     | 8     | 22   | 6,57% |5| 8,62%     |2   | 4,44%        | 0,50    |


## Bibliografia

[1] https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf

## Histórico de versão
| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 28/04/2023 | Inicialização do documento | Kauã e João | Mylena |
| 1.1 | 29/04/2023 | Confecção da tabela e preenchimento inicial dos requisitos | João e Kauã | Mylena |
