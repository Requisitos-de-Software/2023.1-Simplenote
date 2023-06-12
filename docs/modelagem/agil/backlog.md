# Backlog do Produto

## Introdução

O backlog do produto é uma relação priorizada de requisitos e funcionalidades do projeto que trazem benefícios comerciais para o cliente. Novos itens podem ser acrescentados ao backlog em qualquer momento durante o projeto. Os requisitos são descritos em diferentes níveis de abstração, que variam desde temas, que são a forma mais abstrata, até histórias de usuário, que são a forma mais concreta.

## Metodologia

O backlog do produto foi realizado a partir da análise e revisão dos requisitos funcionais coletados. Em seguida, esses requisitos foram agrupados em temas e épicos, que foram utilizados como base de criação as [histórias de usuário](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/).

## Elicitação de Requisitos

Serão apresentados todos os requisitos funcionais elicitados durante o processo de elicitação.

<center>

| Identificador |                                                   Requisito                                                   |                               Rastreabilidade                                |
| :-----------: | :-----------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------: |
|     RF01      |                                Escrever notas em conjunto com outros usuários                                 |      [ST01](../../elicitacao/storytelling.md#elicitacao-de-requisitos)       |
|     RF02      |                                          Criar checklists nas notas                                           |      [ST02](../../elicitacao/storytelling.md#elicitacao-de-requisitos)       |
|     RF03      |                                Compartilhar publicamente as notas existentes.                                 |      [ST03](../../elicitacao/storytelling.md#elicitacao-de-requisitos)       |
|     RF04      |                                              Desenhar nas notas                                               |      [ST04](../../elicitacao/storytelling.md#elicitacao-de-requisitos)       |
|     RF05      |                                 Poder baixar uma cópia da nota no dispositivo                                 |      [ST06](../../elicitacao/storytelling.md#elicitacao-de-requisitos)       |
|     RF06      |                                      Deve ser possível escrever uma nota                                      | [INT01](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |
|     RF07      |                                       Deve ser possível excluir a nota                                        | [INT02](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |
|     RF08      |                             Deve ser possivel recuperar a nota depois de excluída                             | [INT03](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |
|     RF09      |              O usuário poderá compartilhar suas anotações com outras pessoas atraves de um link               | [INT04](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |
|     RF10      |                                        O usuário poderá usar markdown                                         | [INT05](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |
|     RF11      |                            O usuário será capaz de ver informações sobre sua nota                             | [INT06](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |
|     RF12      | Para o primeiro acesso do usuário, deve ter uma breve explicação sobre o aplicativo e as suas funcionalidades | [INT08](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |
|     RF13      |                                 O usuário poderá separar suas notas em pastas                                 | [INT11](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |
|     RF14      |                              O usuário poderá definir templates para suas notas                               | [INT12](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |
|     RF15      |                        Possibilidade de usar marcação de texto (negrito, itálico, etc)                        |       [GLO01](../../elicitacao/glossario.md#elicitacao-de-requisitos)        |
|     RF16      |                              Possibilidade de criar checklists dentro das notas                               |       [GLO04](../../elicitacao/glossario.md#elicitacao-de-requisitos)        |
|     RF17      |                                        Salvamento automático das notas                                        |       [GLO05](../../elicitacao/glossario.md#elicitacao-de-requisitos)        |
|     RF18      |                        Capacidade de criar no dispositivo um arquivo cópia de uma nota                        |       [GLO06](../../elicitacao/glossario.md#elicitacao-de-requisitos)        |
|     RF19      |                       Sincronização das notas em tempo real em diferentes dispositivos                        |       [ENT02](../../elicitacao/entrevista.md#elicitacao-de-requisitos)       |
|     RF20      |                     Permitir a adição de etiquetas nas notas para facilitar a organização                     |       [ENT03](../../elicitacao/entrevista.md#elicitacao-de-requisitos)       |
|     RF21      |               Possuir um editor de texto avançado para permitir a utilização da função `toggle`               |       [ENT04](../../elicitacao/entrevista.md#elicitacao-de-requisitos)       |
|     RF22      |          Permitir o compartilhamento de notas com outras pessoas, por meio de um link ou por e-mail           |       [ENT05](../../elicitacao/entrevista.md#elicitacao-de-requisitos)       |
|     RF23      |                                     O usuário deve poder editar Anotação                                      | [INT13](../../elicitacao/Introspec%C3%A7%C3%A3o.md#elicitacao-de-requisitos) |

</center>

<div style="text-align: center">
<p> Tabela 1: Requisitos funcionais elicitados (Fonte: Autor, 2023).</p>
</div>

#

# Backlog

## Temas

Foram identificados dois grandes temas durante a etapa de verificação e análise dos requisitos. São eles:

- Notas: Engloba as funcionalidades relacionadas as notas do aplicativo como criação, visuzlização, edição e exclusão.
- Sistema: Trata sobre as funcionalidades do sistema em si, envolvendo aspectos técnicos e de suporte.

## Épicos

Os épicos são muito importantes no desenvolvimento de produtos de software, consistem basicamente em histórias de usuário que descrevem funcionalidades importantes que o produto de forma a atender às necessidades dos usuários. Elas são escritas de maneira mais abstrata e genérica do que as histórias de usuário comuns, o que permite uma visão mais ampla do projeto.

Neste tópico, os épicos foram divididos em histórias de usuário menores e mais detalhadas para que possam ser implementados em partes menores e iterativamente.

Com base nos temas, foi possível criar os seguintes épicos:

<center>

<table>
  <tr>
    <th>Tema</th>
    <th>Épicos</th>
    <th>ID</th>
  </tr>
  <tr>
    <td style="vertical-align:middle">Notas</td>
    <td>Gerenciamento de Notas: Todas as funcionalidades relacionadas as notas.</td>
    <td>EP01</td>
  </tr>

  <tr>
    <td style="vertical-align:middle" rowspan="2">Sistema</td>
    <td>Organização de notas: Funcionalidades relacionadas à organização das notas.</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td>Suporte para formatos avançados de Notas: Envolve as funcionalidades relacionadas ao suporte de formatos de notas.</td>
    <td>EP03</td>
  </tr>
</table>

</center>

<p style="text-align: center"> Tabela 2: Épicos Definidos (Fonte: autores, 2023).</p>

Cada épico vai possuir suas histórias de usuário correspondente, o que serão especificadas e detalhadas dentro do documento de [histórias de usuário](../agil/User_story.md).

<details>
   <summary>E01 - Gerenciamento de Notas</summary>
   <table>
    <tr>
        <th>Épico</th>
        <th>ID</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Gerenciamento de notas</td>
        <td>EP01</td>
        <td>
        <ul>
            <li>US01: Eu, como usuário, desejo escrever uma nota com tamanho de minha preferência para que eu possa desenvolver minhas notas na aplicação.</li>
            <li>US02: Eu, como usuário, desejo visualizar minhas notas, para que eu possa desenvolver minhas notas na aplicação.</li>
            <li>US03: Eu, como usuário, desejo editar minhas notas, para que eu possa desenvolver minhas notas na aplicação.</li>
            <li>US04: Eu, como usuário, desejo poder recuperar minhas notas após movê-las para a lixeira.</li>
            <li>US07: Eu, como usuário, desejo excluir minhas notas para que eu possa me organizar melhor no aplicativo.</li>
        </ul>
        </td>
    </tr>
    </table>
    <div style="text-align: center">
    <p>
        Tabela 3: Épico - Gerenciamento de Notas (Fonte: autor, 2023).
    </p>
</div>
</details>

<details>
   <summary>E02 - Organização de notas</summary>
   <table>
    <tr>
        <th>Épico</th>
        <th>ID</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Organização de notas</td>
        <td>EP02</td>
        <td>
        <ul>
            <li>US08: Eu, como usuário, desejo separar minhas notas com tags e filtrá-las caso queira.</li>
            <li>US09: Eu, como usuário, desejo separar minhas notas em pastas para que eu possa me organizar melhor no aplicativo.</li>
        </ul>
        </td>
    </tr>
    </table>
    <div style="text-align: center">
    <p>
        Tabela 4: Épico - Organização de notas (Fonte: autor, 2023).
    </p>
</details>

<details>
   <summary>E03 - Suporte a Formatos Avançados de Notas</summary>
    <table>
    <tr>
        <th>Épico</th>
        <th>ID</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Suporte a Formatos Avançados de Notas</td>
        <td>EP03</td>
        <td>
        <ul>
            <li>US10: Eu, como usuário, desejo escrever em LaTeX ou equivalentes para notas mais acadêmicas.</li>
            <li>US11: Eu, como usuário, desejo escrever em Markdown ou equivalente para notas mais bem formatadas.</li>
        </ul>
        </td>
    </tr>
    </table>
    <div style="text-align: center">
    <p>
        Tabela 5: Épico - Suporte a Formatos Avançados de Notas (Fonte: autor, 2023).
    </p>
</details>

## Product Backlog

Nas tabelas 6 e 7 possui o Backlog completo com os temas, épicos, Histórias de Usuário (US), prioridade e origem dos requisitos.

<table>
    <tr>
        <th style="text-align: center" colspan=6>
            <h2>Notas</h2>
        </th>
    </tr>
    <tr>
        <td style="text-align: center"> <b> Épico </b></td>
        <td style="text-align: center"> <b> História de Usuário (US) </b></td>
        <td style="text-align: center"> <b> ID </b></td>
        <td style="text-align: center"> <b> Prioridade </b></td>
        <td style="text-align: center"> <b> Origem </b></td>
    </tr>
    <tr>
        <!-- Épico -->
        <td style="vertical-align: middle; text-align: center" rowspan="5"> <a href="#epicos">E01</a></td>
        <td>Eu, como usuário, desejo escrever uma nota com tamanho de minha preferência para que eu possa desenvolver
            minhas notas na aplicação.</td>
        <td><a href="../User_story">US01</a></td>
        <td>Must</td>
        <td><a href=#elicitacao-de-requisitos>RF06</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo visualizar minhas notas, para que eu possa desenvolver minhas notas na aplicação.
        </td>
        <td><a href="../User_story">US02</a></td>
        <td>Should</td>
        <td><a href=#elicitacao-de-requisitos>RF11</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo editar minhas notas, para que eu possa desenvolver minhas notas na aplicação.</td>
        <td><a href="../User_story">US03</a></td>
        <td>Should</td>
        <td><a href=#elicitacao-de-requisitos>RF23</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo poder recuperar minhas notas após movê-las para a lixeira.</td>
        <td><a href="User_story.md">US04</a></td>
        <td>Should</td>
        <td><a href=#elicitacao-de-requisitos>RF08</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo excluir minhas notas para que eu possa me organizar melhor no aplicativo.</td>
        <td><a href="../User_story">US07</a></td>
        <td>Must</td>
        <td><a href=#elicitacao-de-requisitos>RF07</td>
    </tr>

</table>

<div style="text-align: center">
    <p>
        Tabela 6: Tema - Notas (Fonte: autor, 2023).
    </p>
</div>

#

<table>
    <tr>
        <th style="text-align: center" colspan=6>
            <h2>Sistema</h2>
        </th>
    </tr>
    <tr>
        <td style="text-align: center"> <b> Épico </b></td>
        <td style="text-align: center"> <b> História de Usuário (US) </b></td>
        <td style="text-align: center"> <b> ID </b></td>
        <td style="text-align: center"> <b> Prioridade </b></td>
        <td style="text-align: center"> <b> Origem </b></td>
    </tr>
    <tr>
        <!-- Épico -->
        <td style="vertical-align: middle; text-align: center" rowspan="2"> <a href=#epicos>E02</a> </td>
        <td>Eu, como usuário, desejo separar minhas notas com tags, e filtrá-las caso queira.</td>
        <td><a href="../User_story">US08</a></td>
        <td>Must</td>
        <td><a href=#elicitacao-de-requisitos>RF19</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo separar minhas notas em pastas para que eu possa me organizar melhor no aplicativo.</td>
        <td><a href="../User_story">US09</a></td>
        <td>Could</td>
        <td><a href=#elicitacao-de-requisitos>RF09</td>
    <tr>
        <!-- Épico -->
        <td style="vertical-align: middle; text-align: center" rowspan="2"> <a href=#epicos>E03</a> </td>
        <td>Eu, como usuário, desejo escrever em LaTeX ou equivalentes para notas mais acadêmicas.</td>
        <td><a href="../User_story">US10</a></td>
        <td>Should<br></td>
        <td><a href=#elicitacao-de-requisitos>RF13</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo escrever em Markdown ou equivalente para notas mais bem formatadas.</td>
        <td><a href="../User_story">US11</a></td>
        <td>Could<br></td>
        <td><a href=#elicitacao-de-requisitos>RF14</td>
    </tr>
</table>

<div style="text-align: center">
    <p>
        Tabela 7: Tema - Sistema (Fonte: autor, 2023).
    </p>
</div>

## Referências

[1] Repositórios de disciplina: [Linkedin](https://requisitos-de-software.github.io/2022.2-LinkedIn/modelagem/backlog/) e [Lichess](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/)

[2] GOMES, Diego. Product Backlog - Introdução [vídeo]. Agile Coach Diego Gomes. Publicado em 23 jun. 2020. Disponível em: https://youtu.be/z4ubaBwjCsU. Acesso em: 14 maio 2023.

## Histórico de versão

| Versão | Data       | Autor             | Descrição                   | Revisor |
| :----: | ---------- | ----------------- | --------------------------- | ------- |
| `1.0`  | 11/05/2023 | Ana Beatriz       | Criação do artefato         | João    |
| `1.1`  | 14/05/2023 | Ana Beatriz e Ian | Finalização da Tabela de RF | João    |
| `1.2`  | 12/06/2023 | Ana Beatriz       | Ajustes                     | João    |
