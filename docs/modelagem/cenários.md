# Cenários

## Introdução
Cenários são descrições evolutivas de situações em um ambiente composto por um conjunto ordenado de interações entre seus participantes, realizadas por usuários ou sistemas externos . Diante disso, os cenários são utilizados para descrever as situações de uso do sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos. Portanto, é uma estratégia para elicitar a parte comportamental do software.

## Modelo de Cenário

Escolhemos representar os cenários conforme o modelo abaixo, tabela 1. A forma escolhida utiliza a linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente.

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Título     | O que se refere o cenário                                                                    |
| Objetivo   | Finalidade do cenário                                                                        |
| Contexto   | Descrição de pré-condições, local (físico) e tempo                                           |
| Recursos   | Objetos passivos com os quais os atores interagem                                            |
| Ator       | Pessoa ou estrutura organizacional                                                           |
| Episódios  | Ação realizada por um ou vários atores com participação de outros atores utilizando recursos |
| Restrições | Imposição que restrinja um episódio de um cenário                                            |
| Exceção    | Tratamento para uma situação excepcional ou de erro                                          |

 <p align="center"> Tabela 1: Modelo de cenários <br> Autores: Mylena e Leonardo</p>

## Cenários identificados

Os cenários identificados foram determinados a partir de um compilado dos requisitos elicitados pelos métodos MoSCoW, FTF e 3 Levels documentado na [Priorização](docs/elicitacao/Priorização). 
A escolha dos cenários foram feitas com base no artefato [Requisitos prioritários](docs/elicitacao/Priorização/priorizacao_final.md). Devido a similaridade de alguns cenários, somente a forma mais abrangente foi modelada. 
A seguir, eles podem ser observados por meio das tabelas abaixo. 

### C01- Criar uma nota

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Criar uma nota        |
| Objetivo   | Escrever uma nota no sistema  |
| Contexto   | - Pré condição: ter o aplicativo instalado <br> - Local: Na escola <br> - Tempo: Semana de prova |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário quer escrever uma nota <br> - Usuário clica em "Nova nota" <br> - Usuário digita um texto |
| Restrições | - Usuário não encontrar o botão "Nova nota” |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando                                       |
<p > Tabela 2: Cenário 01 <br> Autora: Mylena</p>

### C02- Excluir uma nota

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Excluir uma nota       |
| Objetivo   | Apagar uma nota que já estava no sistema |
| Contexto   | - Pré condição: ter uma nota escrita <br> - Local: Na escola <br> - Tempo: Semana de prova |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário quer apagar uma nota <br> - Usuário clica na nota que deseja apagar <br> - Usuário clica no menu da nota (...) <br> - Usuário clica no botão "mover para a lixeira" |
| Restrições | - Usuário não encontrar a nota que deseja apagar <br> - Usuário não encontrar o menu da nota botão <br> - Usuário não achar o botão de apagar |
| Exceção    | Sem nota para apagar <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou|
<p> Tabela 3: Cenário 02 <br> Autora: Mylena</p>

### C03- Visualizar anotações

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Vizualizar uma nota    |
| Objetivo   | Ler o que está escrito em uma nota já feita |
| Contexto   | - Pré condição: ter uma nota escrita <br> - Local: Em casa <br> - Tempo: Semana de prova |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário quer ler uma nota <br> - Usuário procura pela nota  <br> - Usuário clica na nota que deseja ler |
| Restrições | - Usuário não encontrar a nota  |
| Exceção    | Não ter nota escrita <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou|
<p> Tabela 4: Cenário 03 <br> Autora: Mylena</p>

### C04- Editar título e conteúdo de nota existente

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Editar uma nota   |
| Objetivo   | Fazer alguma alteração em uma nota previamente escrita |
| Contexto   | - Pré condição: ter uma nota escrita <br> - Local: Na sala de aula <br> - Tempo: Semana de prova |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário querer editar uma nota <br> - Usuário procura pela nota  <br> - Usuário clica na nota que deseja editar <br> - Usuário começa a editar |
| Restrições | - Usuário não encontrar a nota <br>   |
| Exceção    | Não ter nota escrita <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou|
<p > Tabela 5: Cenário 04 <br> Autora: Mylena</p>

### C05- O usuário poderia separar suas notas por tags

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Separar notas por tag  |
| Objetivo   | Organizar as notas que escreve por meio de tags |
| Contexto   | - Pré condição: ter o aplicatico <br> - Local: Na sala de aula <br> - Tempo: Semana de prova |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário cria uma nova nota <br> - Usuário adiciona as "tags" na nota escritaprocura pela nota   |
| Restrições | - Usuário não criar uma nota <br>   |
| Exceção    | - Não ter criar uma tag <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou|
<p> Tabela 6: Cenário 05 <br> Autora: Mylena</p>

### C06- O usuário deve poder usar Markdown

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Utilizar markdown |
| Objetivo   | Usuário quer escrever uma nota em markdowm |
| Contexto   | - Pré condição: Saber markdowm <br> - Local: Em casa <br> - Tempo: Trabalhos |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário cria uma nova nota <br> - Usuário clica no menun da nota (...) <br> - Usuário clica no botão de acionar o markdown <br> - Usuário digita utilizando as formatações de markdowm <br> - Usuário arrasta a tela para o lado e observa a nota em markdown   |
| Restrições | - Usuário não criar uma nota <br>   |
| Exceção    | - Não ter criar uma tag <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou|
<p align="center"> Tabela 7: Cenário 06 <br> Autora: Mylena</p>

### C07- O usuário deve poder buscar notas por palavras-chave

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Busca de notas por palavras-chave |
| Objetivo   | Usuário quer encontrar uma nota específica |
| Contexto   | - Pré condição: Saber o nome da nota ou texto que ela contém <br> - Local: Escola <br> - Tempo: Aula de Língua Portuguesa |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário digita na barra de busca <br> - O aplicativo lista resultados a medida que o usuário escreve palavras-chaves <br> - Usuário clica na nota que está buscando  |
| Restrições | - Usuário não criar uma nota <br> - Usuário não saber o conteúdo ou título da nota  |
| Exceção    | - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou|
<p align="center"> Tabela 8: Cenário 07 <br> Autor: Leonardo</p>

### C08- O usuário deve poder criar uma conta e fazer login

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Criar uma conta e fazer login |
| Objetivo   | Usuário quer criar uma conta para ter acesso ao aplicativo |
| Contexto   | - Pré condição: Possuir um endereço de email <br> - Local: Em casa <br> - Tempo: Início do período aulas |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário realiza o download do aplicativo <br> - O usuário abre o aplicativo pela primeira vez <br> - Usuário clica no botão Sign Up <br> - Usuário informa o endereço de email que será associado à conta <br> - Usuário recebe um email do aplicativo com link para ativar a conta <br> - Usuário acessa o link no email enviado <br> - Usuário cria uma senha <br> - Usuário clica em criar conta <br> - Usuário realiza login na tela inicial |
| Restrições | - Usuário não receber email do aplicativo <br>   |
| Exceção    | - Usuário não possui endereço de email <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou|
<p align="center"> Tabela 9: Cenário 08 <br> Autor: Leonardo</p>


### C9- O usuário deveria poder recuperar anotação excluída

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Recuperar anotações |
| Objetivo   | Usuário quer recuperar uma nota excluída |
| Contexto   | - Pré condição: Deletar uma nota <br> - Local: Em casa <br> - Tempo: Revisão para uma prova |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário deleta uma nota <br> - Usuário clica na barra de tarefas <br> - Usuário clica no ícone de lixeira (trash) <br> - Usuário seleciona nota que deseja recuperar <br> - Usuário clica em "restaurar nota" |
| Restrições | - Usuário não encontrar nota na lixeira <br> - Usuário ter esvaziado a lixeira antes de recuperar a nota  |
| Exceção    | - Lixeira vazia <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou |
<p align="center"> Tabela 10: Cenário 09 <br> Autor: Leonardo</p>

### C10- O usuário deve ser capaz de anexar imagens

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Anexar imagens |
| Objetivo   | Usuário quer anexar um arquivo de imagem a uma nota |
| Contexto   | - Pré condição: Criar uma nota e ter um arquivo de imagem no dispositivo <br> - Local: Em um escritório <br> - Tempo: Preparação para uma reunião de trabalho |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário seleciona uma nota <br> - Usuário clica na funcionalidade de anexos <br> - Aplicativo mostra a galeria de imagens <br> - Usuário seleciona arquivo de imagem para anexar <br> - Usuário clica em anexar |
| Restrições | - Usuário não encontrar nota para anexar imagem <br> - Usuário não encontrar arquivo de imagem para anexar  - Usuário não criar uma nota <br> - Arquivo de imagem incompatível |
| Exceção    | - Dispositivo sem arquivo de imagem <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou |
<p align="center"> Tabela 11: Cenário 10 <br> Autor: Leonardo</p>

### C11- O usuário deveria poder pesquisar por suas anotações

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Pesquisar nas anotações |
| Objetivo   | Usuário quer pesquisar um trecho de texto dentro da anotação |
| Contexto   | - Pré condição: Criar uma nota, escrever na nota <br> - Local: Na faculdade <br> - Tempo: Estudando para uma prova teórica de programação |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário clica no ícone de pesquisar um trecho de texto <br> - Usuário digita o trecho ou palavra que deseja encontrar <br> - O aplicativo destaca trechos que correspondem à pesquisa <br> - Usuário navega pela nota do início ao fim saltando entre os trechos destacados <br> - Usuário encontra o trecho desejado |
| Restrições | - Usuário não ter criado uma nota <br> - Usuário selecionar uma nota sem conteúdo  |
| Exceção    | - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou |
<p align="center"> Tabela 12: Cenário 11 <br> Autor: Leonardo</p>

### C012- O usuário deveria poder compartilhar notas com outras pessoas

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Compartilhar anotações |
| Objetivo   | Usuário quer compartilhar notas com outros usuários |
| Contexto   | - Pré condição: Criar uma nota <br> - Local: Em casa <br> - Tempo: Escrevendo uma pesquisa em grupo |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário seleciona a anotação que deseja compartilhar <br> - Usuário clica na funcionalidade para colaborar <br> - Aplicativo cria uma caixa de texto para digitar um endereço de email <br> - Usuário digita endereço de email do usuário com o qual deseja compartilhar a nota <br> - Aplicativo envia solicitação de colaboração para o endereço de email <br> - Usuário destinatário aceita o pedido de colaboração |
| Restrições | - Destinatário não possui conta no aplicativo <br> - Usuário não ter criado uma nota <br> - Usuário não sabe o endereço de email de outro usuário |
| Exceção    | - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou |
<p align="center"> Tabela 13: Cenário 12 <br> Autor: Leonardo</p>

### C013- O aplicativo deve permitir a adição de etiquetas nas notas para facilitar a organização

|  Elemento  |         Descição      |
|------------|-----------------------|
| Título     | Colocando etiquetas (tags) nas anotações |
| Objetivo   | Usuário quer catalogar suas notas com etiquetas |
| Contexto   | - Pré condição: Criar uma nota, Criar uma etiqueta <br> - Local: Em casa <br> - Tempo: Organizando as notas das disciplinas do semestre |
| Recursos   | - Celular <br> - Aplicativo                                          |
| Ator       | Usuário                                                          |
| Episódios  | - Usuário seleciona a anotação que deseja colocar uma etiqueta <br> - Usuário clica na funcionalidade de colocar uma etiqueta <br> - Usuário seleciona qual etiqueta será atrelada à nota <br> |
| Restrições | - Usuário não ter criado uma nota <br> - Usuário não ter criado uma etiqueta <br> |
| Exceção    | - Celular sem bateria <br> - Celular não estar funcionando <br> - Aplicativo travou |
<p align="center"> Tabela 14: Cenário 13 <br> Autor: Leonardo</p>

## Bibliografia

[1] Slides Requisitos - aula 10. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise.

[2] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>.

[3] Repositório de disciplina: [Lichess](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/cenarios/)

## Histórico de Versão

| Versão | Data       | Descrição            | Autor(es)     | Revisor(es)   |
| ------ | ---------- | -------------------- | ------------- | ------------- |
| `1.0`  | 06/05/2023 | Criação do documento | Mylena e Leonardo | Kauã |
