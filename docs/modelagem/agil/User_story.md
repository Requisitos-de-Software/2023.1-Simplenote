# Histórias de Usuário

## Introdução
Neste artefacto será realizado as histórias de usuário do aplicativo Simplenote. Histórias de usuário é uma tecnica de modelagem ágil que permite que a equipe entenda a necessidade do usuário e trabalhe em cima dessas necessidades de maneira eficiente.

## Oque são histórias de usuário ?

Histórias de usuário são as menores unidades de trabalho de uma estrutura ágil que são escritas a partir da pespectiva de um usuário final, por vezes, em um projeto real, elas são quebradas em unidades menores que chamamos de "Spikes" feitas em reuniões de "refinamento". As mesmas visam contar uma "história" do porque uma feature é necessária para o produto de modo que seja mais fácil entender qual a finalidade de determinado requisito.
As histórias possuem determinadas dimensões, são elas:

- Funcionais: usuário(Qual o usuário ?), ação(Oque o usuário vai fazer ?), dados (Quais detalhes temos ?) e controle(Existe limite na ação ?).
- Não funcionais: interface (Por onde ?) e qualidade(Oque precisa ser garantido ?).

Com essas dimensões, podemos montar propriamente a estrutura das histórias de usuário. As histórias de usuário são pontos importantes da modelagem ágil pois trazem vários benefícios, como:

- Ritmo de equipe: com os requisitos particionados, a equipe pode gerar um ritmo afim de gerar pequenos desafios semanalmente.
- Permitem colaboração: incentivam o pensamento crítico da equipe afim de que possa atender melhor o usuário.
- Torna o produto tangível: com a existência de uma sumarização dos requisitos elicitados, pode-se entender melhor oque deve ser feito.
- Dentre vários outros beneficios.

## Metodologia
A princípio, durante o projeto foram elicitados os requisitos do aplicativo através de tecnicas como:
- [Brainstorming](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/brainstorming.md)
- [Entrevista](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/entrevista.md)
- [Glossário](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/glossario.md)
- [Instrospecção](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)
- [Personas](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/personas.md)
- [Questionário](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/questionario.md)
- [Storytelling](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/storytelling.md)
  
Posteriormente, foi efetuado a priorização dos requisitos elicitados com as tecnicas de:
- [FTF](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/Prioriza%C3%A7%C3%A3o/FirstthingsFirst.md)
- [MosCow](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/Prioriza%C3%A7%C3%A3o/MoScoW.md)
- [TLE](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/Prioriza%C3%A7%C3%A3o/ThreeLevelScale.md)

Então, as funcionalidades foram escritas de maneira rápida e padronizada seguindo as especificações presentes no [Backlog](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/backlog.md).E por fim, foi efetuado uma validação do documento através de uma reunião com o pseudo-PO do projeto.

## Padrão de história de usuário
Para escrever as histórias de usuário, devemos seguir as dimensões já especificadas neste documento, assim, para a modelagem da histórias de usuário deste projeto, devemos ter as seguintes informações:

- ID : Identificador das histórias de usuário, como o documento foi organizado em toggles, estão presentes no titulo dos mesmos.
- História de usuário: Deve conter a estrutura (Eu, como ... desejo ... para que ...).
- Tema: referente a qual tema a história está relacionada.
- Critérios de aceitação: conjunto de atributos que uma funcionalidade deve ter para ser considerada "aceita".
- Prioridade: Nível de importância da US no projeto, pode ser definida como alta, média ou baixa levando em conta fatores como valor para o usuário, facilidade de implementação, dependências tecnicas e restrições de prazo.

## Histórias de Usuário
Em seguida, temos as histórias de usuário:

<details>
   
   <summary>US01</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo escrever uma nota com tamanho de minha preferência para que eu possa desenvolver minhas notas na aplicação.</td>
           <td>Notas</td>
           <td>O sistema deve permitir escrever notas de tamanho variável.</br>O sistema deve salvar a nota em até 1 segundo.</br>O sistema deve disponibilizar o salvamento automatico das notas.</td>
           <td>Alta</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 1: História de Usuário 1 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US02</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo visualizar minhas notas, para que eu possa desenvolver minhas notas na aplicação.</td>
           <td>Notas</td>
           <td>O sistema deve permitir visualizar minhas notas na aplicação.</br>O sistema carregar as notas sem internet.</td>
           <td>Alta</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 2: História de Usuário 2 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US03</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo editar minhas notas, para que eu possa desenvolver minhas notas na aplicação.</td>
           <td>Notas</td>
           <td>O sistema deve permitir editar as notas já criadas.</td>
           <td>Alta</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 3: História de Usuário 3 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US04</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo poder recuperar minhas notas após movê-las para a lixeira.</td>
           <td>Notas</td>
           <td>O sistema deve ser capaz de recuperar notas deletados.</br>O sistema deve disponibilizar as notas movidas para a lixeira para visualização</td>
           <td>Média</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 4: História de Usuário 4 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US05</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo utilizar o aplicativo em diversas plataformas para que eu possa ter mais conforto para manipular minhas notas.</td>
           <td>Sistema</td>
           <td>O Aplicativo oferecer suporte para diversos sistemas operacionais.</br>O aplicativo deve fornecer interfaces adaptadas para cada tipo de plataforma</td>
           <td>Alta</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 5: História de Usuário 5 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US06</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo poder enviar e receber notas de múltiplas plataformas.</td>
           <td>Sistema</td>
           <td>O usuário deve ser capaz de enviar notas para dispositivos diferentes.</br>
               O usuário deve ser capaz de receber notas de plataformas diferentes.
          </td>
            <td>Alta</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 6: História de Usuário 6 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US07</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo excluir minhas notas para que eu possa me organizar melhor no aplicativo.</td>
           <td>Notas</td>
           <td>O sistema deve ser capaz de excluir as notas.</br>O sistema deve permitir haver uma "lixeira" para armazenar as notas excluidas </td>
           <td>Alta</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 7: História de Usuário 7 (Fonte: Autores, 2023).</p>
   </div>
</details>


<details>
   <summary>US08</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo separar minhas notas com tags, e filtrá-las caso queira.</td>
           <td>Notas</td>
           <td>
            O sistema deve poder utilizar-se de tags editáveis. </br>
            O sistema deve poder filtrar minhas notas usando as tags.</td>
         </tr>
         <td>Baixa</td>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 8: História de Usuário 8 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US09</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo separar minhas notas em pastas para que eu possa me organizar melhor no aplicativo.</td>
           <td>Notas</td>
           <td>O sistema deve ser capaz de organizar as notas em pastas.</br>O sistema deve ser capaz de pesquisar por estas pastas</br>O sistema deve permitir a visualização de todas as pastas.</td>
           <td>Baixa</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 9: História de Usuário 9 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US10</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo escrever em Latex ou equivalentes para notas mais acadêmicas.</td>
           <td>Notas</td>
           <td>O sistema deve permitir escrever em outros formatos como o Latex.</td>
           <td>Baixa</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 10: História de Usuário 10 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US11</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo escrever em Markdown ou equivalente para notas mais bem formatadas.</td>
           <td>Notas</td>
           <td>O sistema deve permitir escrever em Markdown.</td>
           <td>Baixa</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 11: História de Usuário 11 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US12</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo poder anexar imagens as minhas notas para maior dinamicidade com o aplicativo.</td>
           <td>Notas</td>
           <td>O sistema deve permitir com que o usuário anexe imagens as notas.</br>O sistema deve poder salvar essas imagens em até 1 segundo.</td>
           <td>Média</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 12: História de Usuário 12 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US13</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo poder fazer login no aplicativo para acessar minhas notas.</td>
           <td>Notas</td>
           <td>O sistema deve conter um campo de login.</br>O sistema deve conter uma interface para acesso do aplicativo tal como um de registro</td>
           <td>Alta</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 13: História de Usuário 13 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US14</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo poder fazer login no aplicativo através de outras plataformas como google ou facebook para melhorar minha interação com o aplicativo.</td>
           <td>Notas</td>
           <td>O sistema deve conter um campo de login.</br>O sistema deve conter uma interface para acesso do aplicativo tal como um de registro.</br>O aplicativo deve se ligar ao banco de dados do aplicativo selecionado.</td>
           <td>Alta</td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 14: História de Usuário 14 (Fonte: Autores, 2023).</p>
   </div>
</details>


## Validação das histórias de usuário
Para a validação das histórias de usuário, foi feita uma entrevista com o product owner(PO) [Júlio César](https://github.com/JulioDinizN) que esta disponivel clicando [neste link](). A reunião foi feita pelo Teams no dia 13/06/2023 às ,após a entrevista, foram feitas as alterações necessárias.

### Bibliografia
[1] https://www.atlassian.com/br/agile/project-management/user-stories </br>
[2] https://www.youtube.com/watch?v=pLJ3LxR292w

### Histórico de versão
| Versão | Data | Descrição| Autor(es)| Revisor(es)
|--|--|--|--|--|
| `1.0` |11/05/2023|Criação do documento| Kauã e João | Mylena |
|`1.1` |13/05/2023|Adição das user stories| Kauã e João | Mylena |
|`1.2`|24/05/2023|Mudanças pontuais |Kauã|Mylena|
|`1.3`|13/06/2023|Mudanças nas histórias de usuário e textos|Kauã|Mylena|
