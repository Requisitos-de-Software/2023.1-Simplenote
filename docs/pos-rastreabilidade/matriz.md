# Matriz Geral

## 1. Introdução
Esse artefato tem por objetivo associar os resultados obtidos na rastreabilidade [_Forward-from_](pos-rastreabilidade/foward_from.md)
e na rastreabilidade [_Backward-from_](pos-rastreabilidade/backward_from.md) através de uma matriz geral de rastreabilidade.

## 2. Metodologia
A abordagem utilizada envolve a criação de uma tabela com 5 colunas, conforme descritas abaixo, que têm o objetivo de apresentar os dados do requisito de forma estruturada e resumida.

### Colunas a serem incluídas na tabela de rastreabilidade:
- ID: Identificação do requisito;
- Descrição: Breve explicação do requisito;
- Origem: Método que o requisito foi elicitado;
- Artefatos: Documentos/Artefatos relacionados ao requisito;
- Implementação: Descreve o status de implementação do requisito após a conclusão do projeto.

### Mapeamento

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

## 3. Matriz Geral
A matriz geral pode ser observada na _Tabela 1_ a seguir.

| ID | Descrição | Origem | Artefatos | Implementação |
| -- | --------- | ------ | --- |--- |
| RF01 | Escrever uma nota | [Instropecção](../elicitacao/introspeccao.md), [Brainstorming](../elicitacao/brainstorming.md)| [E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US01](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [L06](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/) [INT13](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/) [B01](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/) [UC01](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/) [C01](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)  | [Implementado](https://drive.google.com/file/d/1dL8Yt5TpStJwF17_wTCMiNc_ZbwBryY_/preview) |
| RF02 | Visualizar uma nota | [Instropecção](../elicitacao/introspeccao.md)| [E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US02](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [INT06](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/) [C01](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)| [Implementado](https://drive.google.com/file/d/1snMVs47tUh-hujS08d6KbFOM3KZqv47t/preview) |
| RF03 | Editar uma nota | [Instropecção](../elicitacao/introspeccao.md), [Brainstorming](../elicitacao/brainstorming.md)| [E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US03](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [L02](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/) [INT13](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/) [B02](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/) [UC02](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/) [C04](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/)| [Implementado](https://drive.google.com/file/d/1itBYrqoBlDab_GbQU-5b9APxl-d6dt-w/preview) |
| RF04 | Excluir uma nota | [Instropecção](../elicitacao/introspeccao.md), [Brainstorming](../elicitacao/brainstorming.md)| [E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog) [US07](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story) [L11](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico) [INT02](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o) [B03](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming) [C02](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios)| [Implementado](https://drive.google.com/file/d/1stno3pYUBPtD70FP_GXmdt2nXZHqGAvD/preview) |
| RF05 | Recuperar uma nota da lixeira | [Instropecção](../elicitacao/introspeccao.md)| [E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog) [US04](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story) [L08](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico) [INT03](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o) [C09](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios)| [Implementado](https://drive.google.com/file/d/16MHAt63E04b1b1tDPAxT8LPonxZJ8fK2/preview) |
| RF06 | Separar notas por tag | [Instropecção](../elicitacao/introspeccao.md)| [E2](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US08](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [L04](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/) [INT14](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/) [UC03](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/) [C05/C13](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/) | [Implementado](https://drive.google.com/file/d/1cYuq9hB-Dk8bYRyFRf5o17a128KgyMtJ/preview) |
| RF07 |Separar notas em pastas | [Instropecção](../elicitacao/introspeccao.md)| [E1](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US09](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [INT03](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/) | [Implementado](https://drive.google.com/file/d/1IDD-gZT1IvufTL3E8KvJFxISODgqCxgr/preview) |
| RF08 | Escrever notas em LaTeX | - | [E3](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US10](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/)  | [Implementado](https://drive.google.com/file/d/1oKd3A_4mWGxV7yFkGeEVoE9CUVmWrz3z/preview) |
| RF09 | Escrever notas em Markdown | [Instropecção](../elicitacao/introspeccao.md), [Glossário](../elicitacao/glossario.md), [Storytelling](../elicitacao/storytelling.md), [Entrevista](../elicitacao/entrevista.md) | [E3](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US11](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [ST2](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/) [INT05](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/) [GLO04](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/) [ENT04](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/) [C06](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/) | [Implementado](https://drive.google.com/file/d/1Hu8RKJsbN0NDwkE4gvLLmXuV0vaJOE3e/preview) |
| RF10 | Anexar imagens às notas | [Brainstorming](../elicitacao/brainstorming.md) | [E3](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US12](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [B10](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/) [C10](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/) | [Implementado](https://drive.google.com/file/d/1dtGUscbXALihip2gOxY5N7MBXbuLswIl/preview) |
| RF11 | Sincronizar notas com todos os dispositivos | [Entrevista](../elicitacao/entrevista.md) | [E4](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US05](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [ENT02](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/) | Não implementado |
| RF12 | Desenhar nas notas | [Storytelling](../elicitacao/storytelling.md) | [E4](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US05](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [ST04](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/) | [Implementado](https://drive.google.com/file/d/1dtGUscbXALihip2gOxY5N7MBXbuLswIl/preview) |
| RF13 | Baixar cópia de uma nota | [Storytelling](../elicitacao/storytelling.md), [Glossário](../elicitacao/glossario.md) | [E4](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US13](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [ST06](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/) [GLO06](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/) [C09](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/) | [Implementado](https://drive.google.com/file/d/1Uoh7bTqas_D2VmTzhlEFCsnFdPa_dYCx/preview) |
| RF14 | Salvar notas automaticamente | [Entrevista](../elicitacao/entrevista.md), [Glossário](../elicitacao/glossario.md), [Brainstorming](../elicitacao/brainstorming.md) | [E4](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/) [US14](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/) [B19](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/) [GLO05](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/) [ENT07](https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/) | [Implementado](https://drive.google.com/file/d/1Uoh7bTqas_D2VmTzhlEFCsnFdPa_dYCx/preview) |

Tabela 1: Matriz-Geral de Rastreabilidade (Fonte: autor, 2023).

## Bibliografia

> [1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 24. 2019 </br>
>
> [2] Pohl, Klaus; Rupp, Chris. Requirements Engineering Fundamentals. Disponivel em
> [Aprender3](https://aprender3.unb.br/pluginfile.php/2523174/mod_resource/content/2/Rastreabilidade.pdf). </br>
> [3] Leite, Julio .Ratreabilidade de Requisitos.Disponivel em
> [Aprender3](https://aprender3.unb.br/pluginfile.php/2523175/mod_resource/content/3/05_20_sayao.pdf). </br>


### Histórico de versão

| Versão | Data       | Descrição                | Autor(es)               | Revisor(es)         |
| ------ | ---------- | ------------------------ | ----------------------- | ------------------- |
| `1.0`  | 28/06/2023 | Criação do documento     | Ian | João, Beatriz e Leonardo |