# Backward-From

## Introdução

De acordo com o livro "Requirements Engineering Fundamentals"[²](#ancora2) de Klaus Pohl e Chris Rupp, rastreabilidade
de requisitos é a capacidade de traçar rastros de requisitos durante toda a vida de um software.
Sendo assim, temos 4 formas de acompanhar a vida de cada requisito:

- Backward-To;
- Backward-From;
- Forward-To;
- Forward-From;

Este documento relaciona a tecnica de Bacward-From com os [requisitos
elicitados](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/) no projeto envolvendo o
aplicativo Simplenote. Desta maneira, é importante
salientar que a tecnica tem como objetivo ligar os requisitos a artefatos de desenho e implementação[³](#ancora3).

## Metodologia

Para a realização desse artefato, considerou-se o meta-modelo de Toranzo[³](#ancora3) que é composto por 4 categorias de informação:

- Ambiental: Informações provenientes do ambiente em que a organização opera
- Organizacional: Informações relacionadas à identidade e direcionamento da organização.
- Gerencial: Dados relevantes para a gestão do projeto.
- Desenvolvimento: Dados relacionados aos diferentes artefatos produzidos durante o processo de desenvolvimento.

Além dessas categorias, os elos entre os requisitos são divididos entre:

- Satisfação: A classe "Origem" possui dependência de satisfação com a classe "Destino".
- Recurso: A classe "Origem" possui uma dependência de recurso com a classe "Destino".
- Responsabilidade: Registra a participação, responsabilidade e ação de pessoas em relação aos artefatos.
- Representação: Captura a representação ou modelagem dos requisitos em linguagens alternativas.
- Alocado: A classe "Origem" está relacionada à classe "Destino", que representa um subsistema.
- Agregação: Indica “composição” de elementos.


## Mapeamento

Para realizar o mapeamento dos requisitos, será utilizado a tabela 1 na qual contém todos os simbolos necessários para o
bom entendimento dos tópicos abaixo:

<center>

| Legenda | Artefato                  |
| ------- | ------------------------- |
| E       | Épico                     |
| P       | Personas                  |
| US      | Histórias de usuário      |
| ST      | Storytelling              |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| INT     | Introspecção              |
| Q       | Questionário              |
| GLO     | Glossário                 |
| B       | Brainstorming             |
| ENT     | Entrevista                |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

</center>

<div style="text-align: center">
  <p> Tabela 1: Sigla de cada etapa (Fonte: autor, 2023).</p>
</div>

### Requisitos funcionais

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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US01</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L06</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT13</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B01</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/">UC01</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C01</a>
        </td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF01
        </td>
      
    
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US02</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT06</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C01</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF02
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US03</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L02</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT13</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B02</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/">UC02</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C04</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF03</a>
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US07</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L11</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT02</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B03</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C02</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF04
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US04</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L08</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT03</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C09</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF05
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E2</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US08</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L04</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT14</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/">UC03</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C05/C13</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF06
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US09</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT03</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF07
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E3</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US10</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF08</a>
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E3</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US11</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST2</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT05</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO04</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT04</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C06</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF09</a>
        </td>
      </tr>
      
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
      <tr>
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E3</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US12</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B10</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C10</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF10</a>
        </td>
      </tr>
      
    
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US05</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT02</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF11
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US05</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST04</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF12</a>
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US13</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST06</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO06</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C09</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF13</a>
        </td>
      </tr>
      
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US14</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B19</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO05</a>
        <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT07</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>EF14
        </td>
      </tr>
      
  </table>

  <p>Tabela 15: Requisito funcional 14 (Fonte: Autores, 2023).</p>

</details>

<br>

### Requisitos não funcionais

<details>
  <summary> RNF01 - O aplicativo salvará a nota em até 1 segundo</summary>
  <table>
    <tr>
      <th>Tópico</th>
      <th>Referência</th>
    </tr>
    <tr>
      <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT07</a>
      </td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-
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
      <td>Origem</td>
     <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT09</a>
    </td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-
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
      <td>Origem</td>
      <td> <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT10,</a> <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST07</a>
      </td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-ENF01
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
      <td>Origem</td>
      <td>  <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B19</a> 
      </td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-
      </td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B20,</a> <a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT08,</a>
      </td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>ENF02
      </td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B22</a></td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-
      </td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B23</a></td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-
      </td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B24,</a><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO02,</a><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST05,</a><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT06</a>
      </td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>ENF03
      </td>
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B25</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>-
        </td>
      </tr>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B26</a></td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-
      </td>
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
        <td>Origem</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B27</a></td>
      </tr>
      <tr>
        <td>Elo</td>
        <td>-
        </td>
      </tr>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT01</a></td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-
      </td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT09</a></td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-</td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO03</a></td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>- </td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES01</a></td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-
      </td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES02</a></td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-</td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES03</a></td>
    </tr>
    <tr>
      <td>Elo</td>
      <td>-</td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES04</a></tr>
    <tr>
      <td>Elo</td>
      <td>-</td>
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
      <td>Origem</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/">ES05</a></tr>
    <tr>
      <td>Elo</td>
      <td>-</td>
    </tr>
  </table>

  <p> Tabela 33: Requisito não-funcional 18 (Fonte: Autores, 2023).</p>
</details>


### Elos Funcionais


#### EF01

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E1
  - Histórias de Usuário: US01
  - Léxico: L06
  - Introspecção: INT13
  - Brainstorming: B01
  - Casos de Uso: UC01
  - Cenários: C01

- Elos:
  - C01 representa INT13 e B01
  - L06 representa INT3 e B01
  - UC01 representa C01
  - E1 representa INT13 e B01
  - US01 representa  E1

#### EF02

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E1
  - Histórias de Usuário: US02
  - Introspecção: INT06
  - Cenários: C01
- Elos:
  - C01 representa INT06
  - E1 representa INT06
  - US02 representa  E1


#### EF03

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E1
  - Histórias de Usuário: US03
  - Introspecção: INT13
  - Brainstorming: B02
  - Casos de Uso: UC02
  - Cenários: C04
  - Léxico: L02

- Elos:
  - C04 representa INT13 e B02
  - L02 representa INT13 e B02
  - UC02 representa C04
  - E1 representa INT13 e B02
  - US03 representa E1

#### EF04

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E1
  - Histórias de Usuário: US07
  - Léxicos: L11
  - Introspecção: INT02
  - Brainstorming: B03
  - Cenários: C02
- Elos:
  - C02 representa INT02 e B03
  - L11 representa INT02 e B03
  - E1 representa INT02 e B03
  - US07 representa E1

#### EF05

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E1
  - Histórias de Usuário: US04
  - Léxicos: L08
  - Introspecção: INT03
  - Cenários: C09 
- Elos:
  - C09 representa INT03
  - L08 representa INT03
  - E1 representa INT03
  - US04 representa E1

#### EF06

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E2
  - Histórias de Usuário: US08
  - Léxicos: L04
  - Introspecção: INT14
  - Casos de Uso: UC03
  - Cenários: C05, C13
- Elos:
  - C05 representa INT14
  - C13 representa INT14
  - L04 representa INT14
  - UC03 representa C05 e C13
  - E2 representa INT14
  - US08 representa E2

#### EF07

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E1
  - Histórias de Usuário: US09
  - Introspecção: INT03
- Elos:
  - E1 representa INT03
  - US09 representa E1

#### EF08

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E3
  - Histórias de Usuário: US10
- Elos:
  - US10 representa E3


#### EF09

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E3
  - Histórias de Usuário: US11
  - Storytelling: ST2
  - Introspecção: INT05
  - Glossário: GLO04
  - Entrevista: ENT04
  - Cenários: C06
- Elos:
  - ST2 depende de um recurso provido por ENT04
  - C06 representa INT05, GLO04, ENT04 e ST2
  - E3 representa INT05, GLO04, ENT04 e ST2
  - US1 representa 1E3

#### EF10

- Categoria: Desenvolviumento

- Elementos Rastreáveis:
  - Épicos: E3
  - Histórias de Usuário: US12
  - Brainstorming: B10
  - Cenários: C10
- Elos:
  - C10 representa B10
  - E3 representa B10
  - US12 representa E3

#### EF11

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E4
  - Histórias de Usuário: US05
  - Entrevista: ENT02
- Elos:
  - E4 representa ENT02
  - US05 representa E4

#### EF12

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E4
  - Histórias de Usuário: US05
  - Storytelling: ST04
- Elos:
  - E4 representa ST04
  - US05 representa E4

#### EF13

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E4
  - Histórias de Usuário: US13
  - Storytelling: ST06
  - Glossário: GL006
  - Cenários: C09
- Elos:
  - C09 representa ST06 e GLO06
  - E4 representa ST06 e GLO06
  - US13 representa E4

#### EF14

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Épicos: E4
  - Histórias de Usuário: US14
  - Brainstorming: B19
  - Glossário: GLO05
  - Entrevista: ENT07
- Elos:
  - E4 representa B19, GLO05 e ENT07
  - US14 representa E4

### Elos não funcionais

#### ENF01

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Introspecção: INT10
  - Storytelling: ST07
- Elos:
  - ST07 agrega INT10

#### ENF02

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Brainstorming: B20
  - Entrevista: ENT08
- Elos:
  - B20 agrega ENT08

#### ENF03

- Categoria: Desenvolvimento

- Elementos Rastreáveis:
  - Brainstorming: B24
  - Glossário: GLO02
  - Storytelling: ST05
  - Entrevista: ENT06
- Elos:
  - ST05 depende de recursos providos por ENT06


## Bibliografia

> [1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 24. 2019. Acessado em: 23/06/2023 </br>
>
> [2] Pohl, Klaus; Rupp, Chris. Requirements Engineering Fundamentals. Disponivel em
> [Aprender3](https://aprender3.unb.br/pluginfile.php/2523174/mod_resource/content/2/Rastreabilidade.pdf). Acesso em 23 de
> jun de 2023 </br>
>
> [3] Leite, Julio .Ratreabilidade de Requisitos.Disponivel em
> [Aprender3](https://aprender3.unb.br/pluginfile.php/2523175/mod_resource/content/3/05_20_sayao.pdf). Acesso em 23 de
> jun de 2023</br>

### Histórico de versão

| Versão | Data       | Descrição                | Autor(es)               | Revisor(es)         |
| ------ | ---------- | ------------------------ | ----------------------- | ------------------- |
| `1.0`  | 26/06/2023 | Criação do documento     | João, Leonardo e Mylena | Ana, Beatriz E Kauã |
| `1.1`  | 27/06/2023 | Atualização do documento | João, Leonardo e Mylena | Ana, Beatriz E Kauã |
|`1.2`|28/06/2023|Inserção dos elos|João, Leonardo e Mylena|Ana, Beatriz E Kauã|
