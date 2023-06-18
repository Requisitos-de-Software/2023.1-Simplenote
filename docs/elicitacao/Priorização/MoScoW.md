# MoScoW

## Introdução

O método de priorização de MoSCoW é uma técnica utilizada em gerenciamento de projetos para classificar os requisitos do projeto em ordem de prioridade. Os requisitos foram classificados de acordo com sua importância e relevância para o sucesso do projeto Simplenote. 

MoSCoW é um acrônimo que significa Must have (Deve ter) - [Tabela 1](../../elicitacao/Prioriza%C3%A7%C3%A3o/MoScoW.md#must-have) , Should have (Deveria ter) - [Tabela 2](../../elicitacao/Prioriza%C3%A7%C3%A3o/MoScoW.md#should-have), Could have (Poderia ter) - [Tabela 3](../../elicitacao/Prioriza%C3%A7%C3%A3o/MoScoW.md#could-have) e Won't have (Não terá) - [Tabela 4](../../elicitacao/Prioriza%C3%A7%C3%A3o/MoScoW.md#wont-have).

- **Must Have**: Os requisitos classificados como "Must Have" representam funcionalidades essenciais e fundamentais para o propósito principal do aplicativo Simplenote. São características indispensáveis para que os usuários possam criar, editar, visualizar e excluir suas anotações, além de recursos-chave como a busca por palavras-chave, uso de Markdown e a capacidade de sincronização das notas entre dispositivos.

- **Should Have**: Os requisitos classificados como "Should Have" representam funcionalidades desejáveis, que trazem benefícios adicionais aos usuários. Embora não sejam tão cruciais quanto os requisitos "Must Have", essas características aprimoram a experiência do usuário, como a possibilidade de recuperar anotações excluídas, pesquisar por notas específicas e a compatibilidade com dispositivos móveis.

- **Could Have**: Os requisitos classificados como "Could Have" são funcionalidades que podem agregar valor ao aplicativo Simplenote, mas que não são consideradas essenciais para sua funcionalidade básica. Essas características são opções que podem ser exploradas no desenvolvimento futuro do aplicativo, como a personalização de templates e pastas para notas.

- **Won't Have**: Os requisitos classificados como "Won't Have" representam funcionalidades que foram deliberadamente excluídas do escopo do projeto Simplenote. Esses requisitos podem não ser relevantes para as necessidades dos usuários-alvo ou podem ser considerados recursos secundários em relação aos demais requisitos prioritários.


Em geral, para a classificação de cada requisito foi baseada na importância da funcionalidade para o propósito do aplicativo, nas necessidades e expectativas dos usuários, bem como na viabilidade técnica e nos recursos disponíveis para o desenvolvimento do projeto Simplenote.


## Metodologia

A classificação dos requisitos utilizando a técnica MoSCoW, bem como a justificativa geral apresentada, foi embasada em conhecimentos e conceitos abordados em sala disponível na referência [[1]](../../elicitacao/Prioriza%C3%A7%C3%A3o/MoScoW.md#referencias-bibliograficas), especificamente na aula 07 sobre requisitos ministrada por Milene Serano. Essa referência serviu como base teórica para compreender a aplicação da técnica de priorização MoSCoW e sua relevância na definição das necessidades e prioridades do projeto Simplenote. Ao utilizar essa referência, buscamos garantir uma abordagem coerente e fundamentada na prática de gerenciamento de requisitos.

A equipe encarregada da atividade se reuniu tanto presencialmente quanto remotamente, através do Discord, para discutir o levantamento dos requisitos obtidos por meio das técnicas aplicadas. Durante a discussão, foi avaliada a importância de cada requisito e decidimos onde eles se encaixariam melhor no contexto do projeto. É válido ressaltar que a decisão foi baseada em personas, storytelling e introspecção, sem a influência de usuários reais.

- Data: 28 de abril de 2023 e 29 de abril de 2023
- Horário: 10:00 e 20:30
- Local: Campus FGA - UnB e Discord

<center>

## Must Have

| Tipo  |                         Requisito                          |  Elicitação  |
| :---: | :--------------------------------------------------------: | :----------: |
| RF01  |            O usúario deve poder fazer anotação             | Questionário |
| RF02  |            O usúario deve poder editar Anotação            | Introspecção |
| RF03  |          O usúario deve poder vizualizar Anotação          | Introspecção |
| RF04  |           O usúario deve poder excluir anotação            | Introspecção |
| RF05  |             O usúario deve poder usar Markdown             | Questionário |
| RF06  |    O usúario deve poder buscar notas por palavras-chave    | Questionário |
| RNF07 |           O sistema deve ser simples e intuitivo           | Questionário |
| RF08  |           O usuário deve poder sincronizar notas           |  Entrevista  |
| RF09  |     O usuário deve poder criar uma conta e fazer login     |  Entrevista  |
| RF10  | O sistema deve permitir a exportação e importação de notas |   Persona    |
| RF11  |        O usuário deve poder criar notas com imagens        |   Persona    |

<p align="center"> Tabela 1: Must have <br> Fonte: autoras <br> Autores: Ana e Beatriz </p>

## Should Have

| Tipo  |                           Requisito                           |  Elicitação  |
| :---: | :-----------------------------------------------------------: | :----------: |
| RF12  |      O usúario deveria poder recuperar anotação excluida      |  Entrevista  |
| RNF13 |         O sistema deveria salvar a anotação em até 1s         | Introspecção |
| RNF14 |       O usúario deveria poder fazer notas sem internet        | Introspecção |
| RF15  |     O usúario deveria poder pesquisar por suas anotações      | Questionário |
| RNF16 |  O aplicativo deveria ser compatível com dispositivos móveis  |  Entrevista  |
| RF17  |     O sistema deveria permitir a sincronização automática     |   Persona    |
| RF18  |     O usuário deveria poder definir cores para suas tags      |  Entrevista  |
| RNF19 |   O sistema deveria ser otimizado para dispositivos móveis    |   Persona    |
| RF20  | O usuário deveria poder compartilhar notas com outras pessoas |   Persona    |

<p align="center"> Tabela 2: Should have <br> Fonte: autoras <br> Autores: Ana e Beatriz </p>

## Could Have

| Tipo  |                         Requisito                          |  Elicitação  |
| :---: | :--------------------------------------------------------: | :----------: |
| RF21  |      O usuario poderia ver informações sobre sua nota      |      --      |
| RF22  |    O usuario poderia definir templates para suas notas     | Introspecção |
| RF23  |       O usuario poderia separar suas notas em pastas       | Introspecção |
| RF24  |  O usuario poderia importar ou exportar modelos de layout  |      --      |
| RNF25 | O aplicativo poderia ter integração com outros aplicativos |  Entrevista  |
| RF26  |   O usuário poderia definir um lembrete para suas notas    |      --      |
| RNF27 |   O sistema poderia fornecer estatísticas sobre as notas   |      --      |
| RNF28 | O sistema poderia oferecer sugestões de notas relacionadas |      --      |

<p align="center"> Tabela 3: Could have <br> Fonte: autoras <br> Autores: Ana e Beatriz </p>

## Won't Have

| Tipo |                                     Requisito                                     | Elicitação |
| :--: | :-------------------------------------------------------------------------------: | :--------: |
| RF29 |            O usuario não terá como criar espaços de anotação em equipe            |     --     |
| RF30 | O usuario não terá como mudar cor, fonte e tamanho da letra sem utilizar markdown |     --     |

<p align="center"> Tabela 4: Won't have <br> Fonte: autoras <br> Autores: Ana e Beatriz </p>

</center>

# Legenda

- RF: Requisito funcional
- RNF: Requisito não funcional

# Referências Bibliográficas

[1] SERANO, Milene. Requisitos - Aula 07. Disponível em: <https://aprender3.com>. Acesso em: 26 abr. 2023.

# Bibliografia

> SERANO, Milene. Requisitos - Aula 07. Disponível em: <https://aprender3.com>. Acesso em: 26 abr. 2023.

### Histórico de versão

| Versão | Data       | Descrição                     | Autor(es)             | Revisor(es) |
| ------ | ---------- | ----------------------------- | --------------------- | ----------- |
| `1.0`  | 26/04/2022 | Instrospecção                 | Beatriz e Ana Beatriz | Mylena      |
| `1.1`  | 28/04/2022 | Adicionando alguns requisitos | Beatriz e Ana Beatriz | Mylena      |
| `1.2`  | 29/04/2023 | Finalizando requisitos        | Beatriz e Ana Beatriz | Mylena      |
| `1.3`  | 15/05/2023 | Ajustes Feedbacks entrega 2   | Ana Beatriz           | Mylena      |
| `1.4`  | 18/06/2023 | Ajustes Verificação           | Ana Beatriz           | Beatriz     |
