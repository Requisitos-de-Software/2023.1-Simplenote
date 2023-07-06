# Léxico

## Introdução

O Léxico é uma técnica utilizada para descrever os símbolos de uma linguagem. Os engenheiros de requisitos têm como objetivo encontrar frases e símbolos específicos para aplicação em questão. Cada símbolo é descrito com uma noção e um impacto, onde a noção está relacionada com o símbolo e o impacto com a descrição dos efeitos do símbolo na aplicação ou do efeito da aplicação sobre o símbolo.

Para essas descrições, são aplicados os princípios da circularidade e do vocabulário mínimo. O princípio da circularidade estabelece que cada extensão da descrição ou conotação deve referir-se a outros símbolos da linguagem. Além disso, a descrição deve utilizar um conjunto limitado de palavras com significado claro (vocabulário mínimo), evitando termos excessivamente técnicos ou ambíguos.

Léxicos podem ser clasificados como verbos, objetos ou estados. Os léxicos do tipo verbo são aqueles cuja noção consiste em um agente que realiza os procedimentos, e cujo impacto é o reflexo da ação do agente. Os de tipo objeto possuem a definição do objeto em questão na noção, além dos outros objetos com os quais se relaciona, e no impacto são descritas as ações que podem ser aplicadas no objeto. Por fim, os estados apresentam seu significado e quais ações levam a esse estado na noção do léxico, e seu impacto consiste nos estados e ações que podem ocorrer a partir do estado em questão.

## Modelo de Léxico

Os léxicos foram identificados por meio do uso do aplicativo SimpleNote e a seguir temos um exemplo de léxico na Tabela 1 abaixo:

| Léxico         | Sinônimo | Noção   | Impacto             | Classificação       |
| -------------- | -------- | ------- | ------------------- | ------------------- |
| Nome do Léxico | Sinônimo | Símbolo | Descrição do efeito | Verbo/Objeto/Estado |

<div style="text-align: center">
<p> Tabela 1: Modelo dos léxicos (Fonte: João e Beatriz, 2023).</p>
</div>

## Descrição dos Léxicos

### L01 - Usuário

|    Léxico   |     Sinônimo     |                       Noção                            |                 Impacto                   | Classificação |
| :---------: | :--------------: | :----------------------------------------------------: | :---------------------------------------: | :-----------: |
| Usuário | _User_ | Indivíduo que usará a aplicação e suas funcionalidades | Realiza as tarefas: editar nota, criar, pesquisar, enviar, importar e exportar | Objeto |

### L02 - Editar nota

|   Léxico    |     Sinônimo     |                         Noção                          |                  Impacto                  | Classificação |
| :---------: | :--------------: | :----------------------------------------------------: | :---------------------------------------: | :-----------: |
| Editar nota | Alterar anotação | Capacidade do usuário alterar o texto inserido na nota | Altera informações contidas nas anotações |     Verbo     |

### L03 - Fixar

| Léxico |        Sinônimo        |     Noção      |                   Impacto                   | Classificação |
| :----: | :--------------------: | :------------: | :-----------------------------------------: | :-----------: |
| Fixar  | cravar, colar, espetar | Fixar anotação | O usuário pode fixar suas anotações no topo |     Verbo     |

### L04 - Tag

| Léxico |     Sinônimo     |    Noção     |                    Impacto                     | Classificação |
| :----: | :--------------: | :----------: | :--------------------------------------------: | :-----------: |
|  Tag   | Etiqueta, rótulo | Colocar tags | O usuário pode dividir suas anotações por tags |    Objeto     |

### L05 - Histórico

|  Léxico   |   Sinônimo   |      Noção      |                     Impacto                      | Classificação |
| :-------: | :----------: | :-------------: | :----------------------------------------------: | :-----------: |
| Histórico | Antecedentes | Olhar histórico | O usuário pode ver o histórico de suas anotações |    Objeto     |

### L06 - Criar

| Léxico | Sinônimo  |            Noção            |          Impacto           | Classificação |
| :----: | :-------: | :-------------------------: | :------------------------: | :-----------: |
| Criar  | Adicionar | Ação de criar uma nova nota | Permite a criação de notas |     Verbo     |

### L07 - Pesquisar

|  Léxico   |     Sinônimo     |              Noção               |                       Impacto                        | Classificação |
| :-------: | :--------------: | :------------------------------: | :--------------------------------------------------: | :-----------: |
| Pesquisar | Procurar, buscar | Procurar por uma nota já escrita | O usuário pode pesquisar por título de notas ou tags |     Verbo     |

### L08 - Lixo

| Léxico |        Sinônimo         |                       Noção                        |                                          Impacto                                           | Classificação |
| :----: | :---------------------: | :------------------------------------------------: | :----------------------------------------------------------------------------------------: | :-----------: |
|  Lixo  | Deletados, jogadas fora | O usuário pode encontrar notas que foram deletadas | O usuário pode restaurar notas que foram apagadas por engano ou apagar elas por definitivo |    Objeto     |

### L09 - Colaboradores

|    Léxico     |     Sinônimo      |                             Noção                              |                           Impacto                            | Classificação |
| :-----------: | :---------------: | :------------------------------------------------------------: | :----------------------------------------------------------: | :-----------: |
| Coladoradores | Ajudantes, amigos | Pessoa adicionada pelo usuário para contribuir com alguma nota | Ajudar o proprietário da nota com anotações, sugestões úteis |    Objeto     |

### L10 - Nota

| Léxico | Sinônimo |               Noção                |                Impacto                 | Classificação |
| :----: | :------: | :--------------------------------: | :------------------------------------: | :-----------: |
|  Nota  | Anotação | Instância em que o usuário escreve | Ferramenta principal de uso do usuário |    Objeto     |

### L11 - Excluída

|  Léxico  | Sinônimo |                          Noção                          |        Impacto        | Classificação |
| :------: | :------: | :-----------------------------------------------------: | :-------------------: | :-----------: |
| Excluída | Apagada  | Nota foi movida para o lixo ou deletada permanentemente | Permite remover notas |    Estado     |

### L12 - Enviar

| Léxico |   Sinônimo   |                 Noção                 |               Impacto               | Classificação |
| :----: | :----------: | :-----------------------------------: | :---------------------------------: | :-----------: |
| Enviar | Compartilhar | Compartilha a nota com outras pessoas | Permite o compartilhamento de notas |     Verbo     |

### L13 - Importar

|  Léxico  | Sinônimo |           Noção            |                       Impacto                       | Classificação |
| :------: | :------: | :------------------------: | :-------------------------------------------------: | :-----------: |
| Importar | Carregar | Importa notas de outro app | Permite receber notas anteriores à conta do usuário |     Verbo     |

### L14 - Exportar

|  Léxico  | Sinônimo |                   Noção                    |                 Impacto                  | Classificação |
| :------: | :------: | :----------------------------------------: | :--------------------------------------: | :-----------: |
| Exportar |  Salvar  | Exporta a nota em outro arquivo ou formato | Permite enviar a nota em outros formatos |     Verbo     |

### L15 - Tema

| Léxico |    Sinônimo    |                  Noção                   |                  Impacto                   | Classificação |
| :----: | :------------: | :--------------------------------------: | :----------------------------------------: | :-----------: |
|  Tema  | Cor, Aparência | Troca o tema do app entre claro e escuro | Permite alterar a luminosidade e aparência |    Estado     |

## Bibliografia

> [1] Slides Requisitos - aula 10. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise. Disponível em: https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf (Acessado em 04/07/2023)

> [2] Repositório de disciplina: https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/lexico/ (Acessado em: 04/06/2023)

## Histórico de Versão

| Versão | Data       | Descrição                    | Autor(es)      | Revisor(es) |
| ------ | ---------- | --------------------         | :--------------: | :-----------: |
| `1.0`  | 07/05/2023 | Criação do documento         | João e Beatriz | Ana         |
| `1.1`  | 08/05/2023 | Adição dos léxicos           | João e Beatriz | Ana         |
| `1.2`  | 04/06/2023 | Correções após a entrega 3   | Leonardo       | Ian         |
| `1.3`  | 04/07/2023 | Correções após verificação   | João       | -         |

