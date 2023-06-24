# Forward-From
## Introdução
De acordo com o livro "Requirements Engineering Fundamentals"[²](#ancora2) de Klaus Pohl e Chris Rupp, rastreabilidade de requisitos é a capacidade de traçar rastros de requisitos durante toda a vida de um software.
Sendo assim, temos 4 formas de acompanhar a vida de cada requisito:

- Backward-To;
- Backward-From;
- Forward-To;
- Forward-From;

Este documento relaciona a tecnica de Forward-From com os [requisitos elicitados](https://github.com/Requisitos-de-Software/2023.1-Simplenote/tree/main/docs/elicitacao) no projeto envolvendo o aplicativo Simplenote. Desta maneira, é importante
salientar que a tecnica tem como objetivo ligar os requisitos a artefatos de desenho e implementação[³](#ancora3).

## Metodologia

## Mapeamento
Para realizar o mapeamento dos requisitos, será utilizado a tabela 1 na qual contém todos os simbolos necessários para o bom entendimento dos tópicos abaixo:

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

<div style="text-align: center">
<p> Tabela 1: Sigla de cada etapa (Fonte: autor, 2023).</p>
</div>

#### Requisitos funcionais

<details>
 <summary> RF01 - Escrever uma nota</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E1](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US01](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT13](https://github.com/Requisitos-de-Software/2023.1-note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)/[B02](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/brainstorming.md)|
   |       Léxico      |[L06](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/lexico.md)|
   |     Caso de Uso   |[UC01](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/casos_de_uso.md)|
   |      Cenário      |[C01](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/cen%C3%A1rios.md)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 2: Requisito funcional 1 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF02 - Vizualizar uma nota</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E1](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US02](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT06](https://github.com/Requisitos-de-Software/2023.1note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |[C03](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/cen%C3%A1rios.md)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 3: Requisito funcional 2 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF03 - Editar uma nota</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E1](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US03](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT13](https://github.com/Requisitos-de-Software/2023.1note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)/[B02](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/brainstorming.md)|
   |       Léxico      |[L02](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/lexico.md)|
   |     Caso de Uso   |[UC02](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/casos_de_uso.md)|
   |      Cenário      |[C04](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/cen%C3%A1rios.md)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 4: Requisito funcional 3 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF04 - Excluir uma nota</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E1](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US07](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT02](https://github.com/Requisitos-de-Software/2023.1-note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)/[B03](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/brainstorming.md)|
   |       Léxico      |[L11](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/lexico.md)|
   |     Caso de Uso   |-|
   |      Cenário      |[C02](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/cen%C3%A1rios.md)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 5: Requisito funcional 4 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF05 - Recuperar uma nota da lixeira</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E1](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US04](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT03](https://github.com/Requisitos-de-Software/2023.1-note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)|
   |       Léxico      |[L08](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/lexico.md)|
   |     Caso de Uso   |-|
   |      Cenário      |[C09](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/cen%C3%A1rios.md)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 6: Requisito funcional 5 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF06 - Separar notas por tag</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E2](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US08](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        |  Organização   |
   |     Elicitação    |[INT14](https://github.com/Requisitos-de-Software/2023.1-note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)/[B05](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/brainstorming.md)/[ENT03](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/entrevista.md)|
   |       Léxico      |[L04](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/lexico.md)|
   |     Caso de Uso   |[UC03](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/casos_de_uso.md)|
   |      Cenário      |[C05/C013](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/cen%C3%A1rios.md)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 7: Requisito funcional 6 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF07 - Separar notas em pastas</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E2](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US09](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        |  Organização   |
   |     Elicitação    |[INT03](https://github.com/Requisitos-de-Software/2023.1-note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |-|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 8: Requisito funcional 7 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF08 - Escrever notas em latex</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E3](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US10](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        |  Suporte a formatos avançados de notas   |
   |     Elicitação    |-|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |-|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 9: Requisito funcional 8 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF08 - Escrever notas em Markdown</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E3](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US11](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        | Suporte a formatos avançados de notas  |
   |     Elicitação    |[INT05](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)/[GLO04](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/glossario.md)/[ST2](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/storytelling.md)/[ENT04](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/entrevista.md)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |[C06](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/cen%C3%A1rios.md)|
   |   Funcionalidade  | |
   
   <div style="text-align: center">
      <p> Tabela 9: Requisito funcional 8 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF08 - Anexar imagens às notas</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E3](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md)|
   |História de usuário|[US12](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md)|
   |       Tema        | Suporte a formatos avançados de notas  |
   |     Elicitação    |[B10](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/brainstorming.md)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |[C10](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/cen%C3%A1rios.md)|
   |   Funcionalidade  | |
   
   <div style="text-align: center">
      <p> Tabela 10: Requisito funcional 9 (Fonte: Autores, 2023).</p>
   </div>
</details>

## Bibliografia
> [1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 24. 2019. Acessado em: 23/06/2023 </br>
>
> [2] https://aprender3.unb.br/pluginfile.php/2523174/mod_resource/content/2/Rastreabilidade.pdf </br>
>
> [3] https://aprender3.unb.br/pluginfile.php/2523175/mod_resource/content/3/05_20_sayao.pdf </br>


### Histórico de versão

| Versão | Data       | Descrição                                  | Autor(es)   | Revisor(es) |
| ------ | ---------- | ------------------------------------------ | ----------- | ----------- |
| `1.0`  | 23/06/2023 | Criação do documento                       | Ana, Beatriz E Kauã | João, Leonardo e Mylena      |
| `1.1`  | 24/06/2023 | Adição de alguns requisitos funcionais     | Ana, Beatriz E Kauã | João, Leonardo e Mylena      |
