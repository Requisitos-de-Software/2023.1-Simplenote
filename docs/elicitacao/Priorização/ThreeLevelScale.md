# Three Level Scale ou TLS
## Introdução

Este é o documento de Three Level Scale do projeto de requisitos do grupo 5 referente ao Simplenote. A princípio, o documento tem a finalidade de definir quais requisitos serão priorizados pela equipe de desenvolvimento através das tabelas dos requisitos.

## Introdução
Este artefacto é referente ao documento da tecnica de priorização First things first relativo aos requisitos elicitados pelo [grupo 5](https://github.com/Requisitos-de-Software/2023.1-Simplenote) da turma de requisitos de software da Universidade de Brasília 2023/1.

## Definição

**Three Level Scale** ou TLS é uma tecnica de priorização que separa os requisitos em 3 quadrantes que são: baixa, média e alta prioridade. É importante salientar que esta tecnica gera uma priorização subjetiva e imprecisa[1](#ancora1), isto ocorre devido às politicas das empresas e metas do negócio. Nesta tecnica, as palavras principais são: "importância" e "urgencia" já que ambas são os principais parâmetros para decidir em qual quadrante o requisito de encaixa. De acordo com Karl E. Wiegers, temos a seguinte definição de cada quadrante:

- **Alta prioridade**: São tanto importantes quanto urgentes, estes requisitos devem ser implementados o mais rápido o possível. </br>
- **Média prioridade**: Requisitos que são importantes, entretanto, não são urgentes.</br>
- **Baixa prioridade**: Não são nem importantes, e nem urgentes.</br>

Em grandes projetos, queremos realizar a priorização de forma interativa, então, caso seja observado que a quantidade de requisitos classificados em "alta prioridade" são muitos, pode-se fazer uma sub-priorização dos mesmos classificando-os em: Altissímo, Muito alto e Alto. Vale lembrar que para esta tecnica funcionar, é importânte que a interdependência entre os requisitos sejam respeitadas.

## Metodologia
Para realizar a etapa de priorização, foi reunido todos os requisitos elicitados pelo projeto atavés das etapas de:

- [Brainstorming](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/)
- [Entrevista](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/)
- [Glossário](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/)
- [Instrospecção](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/)
- [Storytelling](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/)

Em seguida, foi feito uma filtragem dos requisitos obtidos afim de que possa ter uma amostragem de dados mais consistênte e menos repetitiva. Por fim durantes os dias 28/04 e 29/04, ocorreu a elaboração da documentação, que ocorreu de forma síncrona e assíncrona pelos desenvolvedores do projeto.

- Data: 28 de abril de 2023 e 29 de abril de 2023
- Horário: 10:00 e 20:30
- Local: Campus FGA - UnB e Discord

Com a quantidade de requisitos classificados como altos na priorização final, foi feita uma segunda reunião, afim de reclassificar os requisitos na categoria "alta".

## Resultados

A tabela 1 revela os resultados da priorização dos requisitos funcionais, e a tabela 2 mostra os dos requisitos não funcionais.

#### Requisitos funcionais:

| Identificador| Requisito | Quadrante|
|---------------|-----------|-----------|
| INT01/B01  |O aplicativo deve permitir ao usuário criar uma nova nota com título e conteúdo.|Altíssima prioridade|
|INT06 | O usúario deve poder vizualizar Anotação|Altíssima prioridade|
|INT13 /B02 | O usuário deve ser capaz de editar o título e o conteúdo de uma nota existente.|Altíssima prioridade|
|B03/ INT02 | O aplicativo deve permitir ao usuário excluir notas existentes.|Altíssima prioridade|
|ENT09 | O aplicativo deve permitir o login com diferentes opções, como e-mail, Google ou Facebook, para facilitar o acesso ao aplicativo após formatação ou troca de dispositivo|Altíssima prioridade|
|INT03 | O usúario deve poder recuperar anotação excluída|Altíssima prioridade|
|INT10/ST07 | O usúario deveria poder fazer notas sem internet|Muito alta prioridade|
|INT 11 | O usuario poderia separar suas notas em pastas|Muito alta prioridade|
|ENT07/GLO05/B19 | O aplicativo deve permitir a criação de backups automáticos ou manuais das notas para evitar perda de informação|Muito alta prioridade|
|ST06/GLO06 | Poder baixar uma cópia da nota no dispositivo|Muito alta prioridadee|
|INT16 | O usuario poderia ver informações sobre sua nota|Alta prioridade|
|B09/GLO03 | O aplicativo deve permitir ao usuário formatar o texto das notas, como fonte, tamanho, cor, estilo e alinhamento.|Alta prioridade|
|B08/B22 | O aplicativo deve fornecer opções de segurança, como senha ou autenticação biométrica, para proteger as notas do usuário.|Alta prioridade|
|B04 | O usuário deve ser capaz de organizar suas notas em ordem data de criação, alfabética, etc.|Alta prioridade|
|B11 | O aplicativo deve fornecer uma opção de modo escuro para reduzir o cansaço visual em ambientes com pouca iluminação.|Alta prioridade|
|ENT03/B05 | O aplicativo deve permitir a adição de etiquetas nas notas para facilitar a organização|Média prioridade|
|GLO01 | Possibilidade de usar marcação de texto (negrito, itálico, etc)|Média prioridade|
|INT05/GLO04/ST2/ENT04 | O usúario deve poder usar Markdown|Média prioridade|
|INT14 | O usúario deve poder buscar notas por palavras-chave|Média prioridade|
|INT15 |O usúario deveria poder pesquisar por suas anotações|Média prioridade|
|INT04/ENT05 | O usuário poderá compartilhar suas anotações com outras pessoas atraves de um link|Média prioridade|
|INT08 | Para o primeiro acesso do usuário, deve ter uma breve explicação sobre o aplicativo e as suas funcionalidades|Média prioridade|
|INT12/INT17 |O usuario poderia definir templates para suas notas|Média prioridade|
|B15/ST01 | O aplicativo deve permitir que os usuários trabalhem em notas simultaneamente, com alterações sendo exibidas em tempo real.|Média prioridade|
|B12 | Os usuários devem poder exportar suas notas em diferentes formatos, como PDF ou Word, para uso posterior fora do aplicativo.|Média prioridade|
|B10 | O usuário deve ser capaz de anexar arquivos, imagens, áudios ou vídeos às notas.|Média prioridade|
|B18 | O aplicativo deve manter um histórico de versão de notas, permitindo que os usuários voltem para versões anteriores de suas notas.|Média prioridade|
|B16/B17/B13 | O aplicativo deve permitir que os usuários criem notas com lembretes de data e hora para ajudá-los a acompanhar compromissos ou tarefas importantes.|Baixa prioridade|
|B07/ST03 | O usuário deve ser capaz de compartilhar notas com outras pessoas por meio de diferentes plataformas.|Baixa prioridade|
|ST04 | Desenhar nas notas|Baixa prioridade|
|B14 |O aplicativo deve ser capaz de reconhecer e transcrever a voz dos usuários em notas.|Baixa prioridade|


<p align="center"> Tabela 1: Tabela de priorização TLE para os requisitos funcionais <br> Fonte: autores</p>


#### Requisitos não funcionais:

| Identificador| Requisito | Quadrante|
|---------------|-----------|-----------|
|B25/ENT08 | O aplicativo deve estar disponível para uso sempre que o usuário precisar, sem interrupções ou indisponibilidades não planejadas.|Alta prioridade|
|INT07 | O aplicativo salvará a nota em até 1 segundo|Alta prioridade|
|INT09 | O aplicativo abrirá em um tempo limite de até 2 segundos|Alta prioridade|
|B20/ENT08/INT18/QUE01/B21 | O aplicativo deve ser intuitivo ,rápido ,e fácil de usar, com uma interface clara e simples.|Alta prioridade|
|B26 | O aplicativo deve ser otimizado para usar recursos do dispositivo de forma eficiente, como CPU, memória e bateria.|Alta prioridade|
|B21/GLO02/ST05/B24/ENT02/B06/ENT06 | Estar disponível em diversos dispositivos (celulares, laptops, tablets, etc) e sistemas operacionais|Alta prioridade|
|B27| O aplicativo deve ser facilmente mantido e atualizado, com um código limpo e bem documentado.|Média prioridade|
|B23| O aplicativo deve ser acessível para usuários com deficiências visuais ou motoras, com recursos como suporte a leitores de tela e opções de zoom.|Média prioridade|

<p align="center"> Tabela 2: Tabela de priorização TLE para os requisitos não funcionais <br> Fonte: autores <br> Autor:Kauã </p>

### Legenda:

- INT: Introspecção
- B: Brainstorming
- ENT: Entrevista
- GLO: Glossário
- ST: Storytelling

## Bibliografia

> [1] First Things First: Prioritizing Requirements Karl E. Wiegers
>
> [2] K. Wiegers, “Five Requirements Prioritization Methods - Analyst’s corner - Medium,” Medium, Jun. 03, 2020. https://medium.com/analysts-corner/five-requirements-prioritization-methods-86f4c5e0433e (acessado Jun. 26, 2023).
‌

## Histórico de versão

| Versão |    Data    |                 Descrição                 | Autor       | Revisor |
| :----: | :--------: | :---------------------------------------: | :---------: | :-----: |
|  `1.0` | 28/04/2023 |        Inicialização do documento         | Kauã        | Mylena  |
|  `1.1` | 28/04/2023 | Adicionando requisitos e suas prioridades | Kauã        | Mylena  |
|  `1.2` | 01/05/2023 |          Finalizando o documento          | Kauã        | Mylena  |
|  `1.3` | 15/05/2023 |       Ajustes Feedbacks entrega 2         | Ana Beatriz | Mylena  |
|  `1.4` | 26/06/2023 |         Correção da entrega 5.1           | Kauã        | Mylena  |
