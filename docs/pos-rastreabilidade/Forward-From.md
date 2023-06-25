# Forward-From
## Introdução
De acordo com o livro "Requirements Engineering Fundamentals"[²](#ancora2) de Klaus Pohl e Chris Rupp, rastreabilidade de requisitos é a capacidade de traçar rastros de requisitos durante toda a vida de um software.
Sendo assim, temos 4 formas de acompanhar a vida de cada requisito:

- Backward-To;
- Backward-From;
- Forward-To;
- Forward-From;

Este documento relaciona a tecnica de Forward-From com os [requisitos elicitados](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/) no projeto envolvendo o aplicativo Simplenote. Desta maneira, é importante
salientar que a tecnica tem como objetivo ligar os requisitos a artefatos de desenho e implementação[³](#ancora3).

## Metodologia
A princípio, foi separado todos os documentos nos quais seriam analisados e sumarizados. Para realizar a técnica para os requisitos funcionais, foi relacionado cada história de usuário ao seu respectivo épico,tema,cenário, léxico , caso de uso e onde foi elicitado. Já para os não-funcionais, cada requisito foi associado ao seu respectivo NFR e Especificação Suplementar e foi decidido se o mesmo já foi implementado. 

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
   |      Épico        |[E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US01](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT13](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/)/[B02](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/)|
   |       Léxico      |[L06](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/)|
   |     Caso de Uso   |[UC01](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/)|
   |      Cenário      |[C01](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 2: Requisito funcional 1 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF02 - Vizualizar uma nota</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US02](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT06](https://github.com/Requisitos-de-Software/2023.1note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |[C03](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 3: Requisito funcional 2 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF03 - Editar uma nota</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US03](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT13](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/)/[B02](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/)|
   |       Léxico      |[L02](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/)|
   |     Caso de Uso   |[UC02](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/)|
   |      Cenário      |[C04](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 4: Requisito funcional 3 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF04 - Excluir uma nota</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US07](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT02](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/)/[B03](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/)|
   |       Léxico      |[L11](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/)|
   |     Caso de Uso   |-|
   |      Cenário      |[C02](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 5: Requisito funcional 4 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF05 - Recuperar uma nota da lixeira</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US04](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        |  Notas   |
   |     Elicitação    |[INT03](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/)|
   |       Léxico      |[L08](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/)|
   |     Caso de Uso   |-|
   |      Cenário      |[C09](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 6: Requisito funcional 5 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF06 - Separar notas por tag</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E2](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US08](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        |  Organização   |
   |     Elicitação    |[INT14](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/)/[B05](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/)/[ENT03](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/)|
   |       Léxico      |[L04](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/)|
   |     Caso de Uso   |[UC03](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/)|
   |      Cenário      |[C05/C013](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)|
   |   Funcionalidade  |          |
   
   <div style="text-align: center">
      <p> Tabela 7: Requisito funcional 6 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF07 - Separar notas em pastas</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E2](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US09](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        |  Organização   |
   |     Elicitação    |[INT03](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/)|
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
   |      Épico        |[E3](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US10](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
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
   |      Épico        |[E3](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US11](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        | Suporte a formatos avançados de notas  |
   |     Elicitação    |[INT05](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/)/[GLO04](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/)/[ST2](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/)/[ENT04](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |[C06](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)|
   |   Funcionalidade  | |
   
   <div style="text-align: center">
      <p> Tabela 9: Requisito funcional 8 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF09 - Anexar imagens às notas</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E3](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US12](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        | Suporte a formatos avançados de notas  |
   |     Elicitação    |[B10](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |[C10](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)|
   |   Funcionalidade  | |
   
   <div style="text-align: center">
      <p> Tabela 10: Requisito funcional 9 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF10 - Sincronizar notas com todos os dispositivos</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E4](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US05](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        | Sincronização e armazenamento de notas  |
   |     Elicitação    |[ENT02](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |-|
   |   Funcionalidade  | |
   
   <div style="text-align: center">
      <p> Tabela 11: Requisito funcional 10 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF11 - Desenhar nas notas</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E4](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US05](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        | Sincronização e armazenamento de notas  |
   |     Elicitação    |[ST04](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |-|
   |   Funcionalidade  | |
   
   <div style="text-align: center">
      <p> Tabela 12: Requisito funcional 11 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF12 - Baixar cópia de uma nota</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E4](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US13](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        | Sincronização e armazenamento de notas  |
   |     Elicitação    |[ST06](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/)/[GLO06](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |[C09](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)|
   |   Funcionalidade  | |
   
   <div style="text-align: center">
      <p> Tabela 13: Requisito funcional 12 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
 <summary> RF13 - Salvar notas automaticamente</summary>

   |      Tópico       |Referência|
   |:-----------------:|:--------:|
   |      Épico        |[E4](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/)|
   |História de usuário|[US14](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)|
   |       Tema        | Sincronização e armazenamento de notas  |
   |     Elicitação    |[ENT07](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/)/[GLO05](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/)/[B19](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/)|
   |       Léxico      |-|
   |     Caso de Uso   |-|
   |      Cenário      |-|
   |   Funcionalidade  | |
   
   <div style="text-align: center">
      <p> Tabela 14: Requisito funcional 13 (Fonte: Autores, 2023).</p>
   </div>
</details>

#### Requisitos não funcionais

<details>
 
</details>

## Bibliografia
> [1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 24. 2019. Acessado em: 23/06/2023 </br>
>
> [2] Pohl, Klaus; Rupp, Chris. Requirements Engineering Fundamentals. Disponivel em [Aprender3](https://aprender3.unb.br/pluginfile.php/2523174/mod_resource/content/2/Rastreabilidade.pdf). Acesso em 23 de jun de 2023 </br>
>
> [3] Leite, Julio .Ratreabilidade de Requisitos.Disponivel em [Aprender3](https://aprender3.unb.br/pluginfile.php/2523175/mod_resource/content/3/05_20_sayao.pdf ). Acesso em 23 de jun de 2023</br>


### Histórico de versão

| Versão | Data       | Descrição                                  | Autor(es)   | Revisor(es) |
| ------ | ---------- | ------------------------------------------ | ----------- | ----------- |
| `1.0`  | 23/06/2023 | Criação do documento                       | Ana, Beatriz E Kauã | João, Leonardo e Mylena      |
| `1.1`  | 24/06/2023 | Adição de alguns requisitos funcionais     | Ana, Beatriz E Kauã | João, Leonardo e Mylena      |
