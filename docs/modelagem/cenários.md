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

### C08- O usuário deve poder criar uma conta e fazer login

### C9- O usuário deveria poder recuperar anotação excluída

### C10- O usuário deve ser capaz de anexar imagens

### C11- O usuário deveria poder pesquisar por suas anotações

### C012- O usuário deveria poder compartilhar notas com outras pessoas

### C013- O aplicativo deve permitir a adição de etiquetas nas notas para facilitar a organização

## Bibliografia

[1] Slides Requisitos - aula 10. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise.

[2] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>.

[3] Repositório de disciplina: [Lichess](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/cenarios/)

## Histórico de Versão

| Versão | Data       | Descrição            | Autor(es)     | Revisor(es)   |
| ------ | ---------- | -------------------- | ------------- | ------------- |
| `1.0`  | 06/05/2023 | Criação do documento | Mylena e Leonardo | Kauã |
