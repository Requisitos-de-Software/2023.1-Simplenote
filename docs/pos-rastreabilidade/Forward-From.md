# Forward-From
## Introdução
De acordo com o livro "Requirements Engineering Fundamentals"[²](#ancora2) de Klaus Pohl e Chris Rupp, rastreabilidade
de requisitos é a capacidade de traçar rastros de requisitos durante toda a vida de um software.
Sendo assim, temos 4 formas de acompanhar a vida de cada requisito:

- Backward-To;
- Backward-From;
- Forward-To;
- Forward-From;

Este documento relaciona a tecnica de Forward-From com os [requisitos
elicitados](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Prioriza%C3%A7%C3%A3o/priorizacao_final/) no projeto envolvendo o
aplicativo Simplenote. Desta maneira, é importante
salientar que a tecnica tem como objetivo ligar os requisitos a artefatos de desenho e implementação[³](#ancora3).

## Metodologia
A princípio, foi separado todos os documentos nos quais seriam analisados e sumarizados. Para realizar a técnica para os
requisitos funcionais, foi relacionado cada história de usuário ao seu respectivo épico, tema, cenário, léxico, caso de
uso e onde foi elicitado, também foi feito um vídeo no qual é evidenciado como a funcionalidade é implementada no aplicativo ou no protótipo. Já para os não-funcionais, cada requisito foi associado ao seu respectivo NFR, Especificação Suplementar e onde foi elicitado .

## Mapeamento
Para realizar o mapeamento dos requisitos, será utilizado a tabela 1 na qual contém todos os simbolos necessários para o
bom entendimento dos tópicos abaixo:

<center>

  | Legenda | Artefato |
  | ------- | ------------------------- |
  | E | Épico |
  | P | Personas |
  | US | Histórias de usuário |
  | ST | Storytelling |
  | UC | Casos de Uso |
  | C | Cenários |
  | L | Léxico |
  | ES | Especificação Suplementar |
  | INT | Introspecção |
  | Q | Questionário |
  | GLO | Glossário |
  | B | Brainstorming |
  | ENT | Entrevista |
  | RF | Requisitos Funcionais |
  | RNF | Requisitos não Funcionais |

</center>

<div style="text-align: center">
  <p> Tabela 1: Sigla de cada etapa (Fonte: autor, 2023).</p>
</div>

#### Requisitos funcionais
As tabelas 2 até a 15 contidas dentros dos toggles evidenciam as informações já citadas dos requisitos funcionais elicitados durante o projeto. Tabelas a seguir:

<details>
  <summary>RF01 - Escrever uma nota</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US01</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT13</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B02</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L06</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/">UC01</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C01</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1dL8Yt5TpStJwF17_wTCMiNc_ZbwBryY_/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 2: Requisito funcional 1 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF02 - Visualizar uma nota</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US02</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://github.com/Requisitos-de-Software/2023.1note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md">INT06</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C03</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1snMVs47tUh-hujS08d6KbFOM3KZqv47t/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 3: Requisito funcional 2 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF03 - Editar uma nota</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US03</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT13</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B02</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L02</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/">UC02</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C04</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1itBYrqoBlDab_GbQU-5b9APxl-d6dt-w/preview" width="640" height="480"></iframe>
</td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 4: Requisito funcional 3 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF04 - Excluir uma nota</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US07</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT02</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B03</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L11</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C02</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1stno3pYUBPtD70FP_GXmdt2nXZHqGAvD/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 5: Requisito funcional 4 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF05 - Recuperar uma nota da lixeira</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US04</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT03</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L08</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C09</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/16MHAt63E04b1b1tDPAxT8LPonxZJ8fK2/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 6: Requisito funcional 5 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF06 - Separar notas por tag</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E2</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US08</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Organização</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT14</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L04</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/">UC03</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C05/C013</a>
        </td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1cYuq9hB-Dk8bYRyFRf5o17a128KgyMtJ/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 7: Requisito funcional 6 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF07 - Separar notas em pastas</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E2</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US09</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Organização</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT03</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1IDD-gZT1IvufTL3E8KvJFxISODgqCxgr/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 8: Requisito funcional 7 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF08 - Escrever notas em LaTeX</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E3</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US10</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Suporte a formatos avançados de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1oKd3A_4mWGxV7yFkGeEVoE9CUVmWrz3z/preview" width="640" height="480"></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 9: Requisito funcional 8 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF09 - Escrever notas em Markdown</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E3</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US11</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Suporte a formatos avançados de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT05</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO04</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST2</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT04</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C06</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1Hu8RKJsbN0NDwkE4gvLLmXuV0vaJOE3e/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 10: Requisito funcional 9 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF10 - Anexar imagens às notas</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E3</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US12</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Suporte a formatos avançados de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B10</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C10</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1dtGUscbXALihip2gOxY5N7MBXbuLswIl/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 11: Requisito funcional 10 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF11 - Sincronizar notas com todos os dispositivos</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US05</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Sincronização e armazenamento de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT02</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><img src=../../img/Sincronizar.PNG width="400"></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 12: Requisito funcional 11 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF12 - Desenhar nas notas</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US05</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Sincronização e armazenamento de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST04</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1dtGUscbXALihip2gOxY5N7MBXbuLswIl/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 13: Requisito funcional 12 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF13 - Baixar cópia de uma nota</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US13</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Sincronização e armazenamento de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST06</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO06</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C09</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1Uoh7bTqas_D2VmTzhlEFCsnFdPa_dYCx/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 14: Requisito funcional 13 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF14 - Salvar notas automaticamente</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US14</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Sincronização e armazenamento de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT07</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO05</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B19</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><img src=../../img/Sincronizar.PNG width="400"></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 15: Requisito funcional 14 (Fonte: Autores, 2023).</p>

</details>

<br>

#### Requisitos não funcionais
As tabelas 16 até a 33 contidas dentros dos toggles evidenciam as informações já citadas dos requisitos não-funcionais elicitados durante o projeto. Tabelas a seguir:

<details>
  <summary> RNF01 - O aplicativo salvará a nota em até 1 segundo</summary>
  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Performance</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Performance</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT07</a>
      </td>
    </tr>
  </table>

  <p> Tabela 16: Requisito não-funcional 1 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary> RNF02 - O aplicativo abrirá em um tempo limite de até 2 segundos</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Performance</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Performance</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT09</a>
      </td>
    </tr>
  </table>

  <p> Tabela 17: Requisito não-funcional 2 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary> RNF03 - Deve ser possível fazer notas sem internet</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Performance</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT10</a>
      </td>
    </tr>
  </table>


  <p> Tabela 18: Requisito não-funcional 3 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary> RNF04 - O aplicativo deve ser confiável e estável, evitando falhas ou perda de dados.</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Disponibilidade</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Confiabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B19</a></td>
    </tr>
  </table>


  <p> Tabela 19: Requisito não-funcional 4 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary> RNF05 - O aplicativo deve ser intuitivo e fácil de usar, com uma interface clara e simples.</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Usabilidade</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B20</a></td>
    </tr>
  </table>

  <p> Tabela 20: Requisito não-funcional 5 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF06 - O aplicativo deve garantir a segurança e privacidade das notas dos usuários, protegendo-as contra
    acesso não autorizado ou perda de dados.</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">-</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Confiabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B22</a></td>
    </tr>
  </table>

  <p> Tabela 21: Requisito não-funcional 6 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF07 - O aplicativo deve ser acessível para usuários com deficiências visuais ou motoras, com recursos como
    suporte a leitores de tela e opções de zoom.</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Usabilidade</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B23</a></td>
    </tr>
  </table>

  <p> Tabela 22: Requisito não-funcional 7 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF08 - O aplicativo deve estar disponível em várias plataformas, como iOS, Android, Windows e Mac, para
    garantir que os usuários possam acessar suas notas em qualquer dispositivo.</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Portabilidade</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Suportabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B24</a></td>
    </tr>
  </table>

  <p> Tabela 23: Requisito não-funcional 8 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF09 - O aplicativo deve estar disponível para uso sempre que o usuário precisar, sem interrupções ou
    indisponibilidades não planejadas.</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Disponibilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Usabilidade</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B25</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p> Tabela 24: Requisito não-funcional 9 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF10 - O aplicativo deve ser otimizado para usar recursos do dispositivo de forma eficiente, como CPU,
    memória e bateria.</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Performance</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Performance</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B26</a></td>
    </tr>
  </table>

  <p> Tabela 25: Requisito não-funcional 10 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF11 - O aplicativo deve ser facilmente mantido e atualizado, com um código limpo e bem documentado.
  </summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>NFR</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Disponibilidade</a></td>
      </tr>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Suportabilidade</a>
        </td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B27</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p> Tabela 26: Requisito não-funcional 11 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF12 - O aplicativo deve permitir a criação de notas de forma fácil e rápida, sem muitas etapas.</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Usabilidade</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT01</a></td>
    </tr>
  </table>

  <p> Tabela 27: Requisito não-funcional 12 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF13 - O aplicativo deve permitir o login com diferentes opções, como e-mail, Google ou Facebook, para
    facilitar o acesso ao aplicativo após formatação ou troca de dispositivo.</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Disponibilidade</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Suportabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT09</a></td>
    </tr>
  </table>

  <p> Tabela 28: Requisito não-funcional 13 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF14 - Ser capaz de ler e editar arquivos de texto de outras fontes</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">Portabilidade</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO03</a></td>
    </tr>
  </table>

  <p> Tabela 29: Requisito não-funcional 14 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF15 - O aplicativo deve ser de fácil entendimento para pessoas mais leigas com tecnologia</summary>

  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">-</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES01</a></td>
    </tr>
  </table>

  <p> Tabela 30: Requisito não-funcional 15 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF16 - O aplicativo deve conter uma cor que estimula calma para trazer a sensação de bem estar ao utilizar o aplicativo</summary>
  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">-</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES02</a></td>
    </tr>
  </table>

  <p> Tabela 31: Requisito não-funcional 16 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF17 - O aplicativo deve sempre guardar as notas que o usuário cria</summary>
  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">-</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Confiabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES03</a></td>
    </tr>
  </table>

  <p> Tabela 32: Requisito não-funcional 17 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF18 - O MTBF(Mean Time Between Failures) do aplicativo deve ser de pelo menos 300 horas</summary>
  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">-</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Confiabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES04</a></td>
    </tr>
  </table>

  <p> Tabela 33: Requisito não-funcional 18 (Fonte: Autores, 2023).</p>
</details>

<details>
  <summary> RNF19 - O MTTR(Mean Time To Repair) do aplicativo que é o tempo máximo permitido para reparo de uma falha do sistema deve ser 4 horas</summary>
  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>NFR</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/">-</a></td>
    </tr>
    <tr>
      <td>Especificação Suplementar</td>
      <td><a
          href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">Confiabilidade</a>
      </td>
    </tr>
    <tr>
      <td>Elicitação</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES05</a></td>
    </tr>
  </table>

  <p> Tabela 33: Requisito não-funcional 18 (Fonte: Autores, 2023).</p>
</details>

## Bibliografia
> [1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 24. 2019. Acessado em: 23/06/2023 </br>
>
> [2] Pohl, Klaus; Rupp, Chris. Requirements Engineering Fundamentals. Disponivel em
[Aprender3](https://aprender3.unb.br/pluginfile.php/2523174/mod_resource/content/2/Rastreabilidade.pdf). Acesso em 23 de
jun de 2023 </br>
>
> [3] Leite, Julio .Ratreabilidade de Requisitos.Disponivel em
[Aprender3](https://aprender3.unb.br/pluginfile.php/2523175/mod_resource/content/3/05_20_sayao.pdf ). Acesso em 23 de
jun de 2023</br>


### Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---------- | ------------------------------------------ | ----------- | ----------- |
| `1.0` | 23/06/2023 | Criação do documento | Ana, Beatriz E Kauã | João, Leonardo e Mylena |
| `1.1` | 24/06/2023 | Adição de alguns requisitos funcionais | Ana, Beatriz E Kauã | João, Leonardo e Mylena |
| `1.2` | 26/06/2023 | Adicionando requisitos não funcionais | Ana, Beatriz E Kauã | João, Leonardo e Mylena |
| `1.3` | 26/06/2023 | Adicionando mais requisitos não funcionais | Ana, Beatriz E Kauã | João, Leonardo e Mylena |
| `1.4` | 26/06/2023 | Adicionando vídeos das funcionalidades | Ana, Beatriz E Kauã | João, Leonardo e Mylena |

