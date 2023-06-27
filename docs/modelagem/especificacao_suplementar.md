# Especificação Suplementar

## Introdução

A Especificação Suplementar é uma tecnica de modelagem que captura os requisitos de sistema que não foram identificados nos casos de uso, como por exemplo: requisitos reguladores, atributos de qualidade do sistema, sistemas operacionais, requisitos de compatiblidade e restrições de design.

## Metodologia

Para a produção deste artefacto, foi utilizado o modelo FURPS+, na qual definimos os requisitos não funcionais elicitados no projeto de acordo com o método FURPS+ no qual é expandido em:

- Funcionalidade;
- Usabilidade;
- Confiabilidade;
- Performance;
- Suportabilidade;
- +;

## Definições da especificação suplementar

### Funcionalidade

Representa os aspectos funcionais do software, aqui, temos diversos subtópicos que variam de acordo com a aplicação.</br>
Os requisitos funcionais podem ser encontrados nos [casos de uso](https://github.com/Requisitos-de-Software/2023.1-Simplenote/tree/main/docs/modelagem/casos_de_uso.md).

- Recursos.
- Segurança.
- Conjunto de recursos.

### Usabilidade

Avalia a interface com o usuário, podemos tratar a prevenção de erros, estética, design, documentação, consistências e padrões.

- Estética.
- Fatores humanos.
- Assistentes e agentes.
- Materiais de treinamento.
- Documentação do usuário.
- Ajuda on-line e sensível ao contexto.
- Consistência na interface com o usuário.

### Confiabilidade

Se refere à capacidade de um aplicativo de realizar suas funções de forma consistente, livre de erros e sem falhas ao longo do tempo.

- Frequência e gravidade de falha.
- Possibilidade de recuperação.
- Possibilidade de previsão.
- Tempo médio entre falhas.
- Exatidão.

### Performance

Diz respeito a capacidade do aplicativo em atender aos requisitos de desempenho estabelecidos na especificação suplementar.

- Tempo de resposta.
- Consumo de recursos.
- Escalabilidade.
- Disponibilidade.

### Suportabilidade

Corresponde à capacidade do software em fornecer suporte, tanto para si próprio quanto para o usuário.

- Testabilidade.
- Adaptabilidade.
- Manutenibilidade.
- Compatibilidade.
- Instalabilidade.
- Portabilidade.

### + (Mais)

O modelo FURPS+ inclui um "+" que representa requisitos adicionais, tais como:

- Requisitos de design: relacionados com a estrutura e a arquitetura do sistema, tais como a especificação do banco de dados a ser utilizado.
- Implementação: especificação de restrições de implementação, como o uso de bibliotecas nativas ou de terceiros.
- Interface: especificação de integrações e acessos externos, por exemplo, integração via serviços web (WS) ou REST.
- Físico: determinação de restrições de hardware e implantação, por exemplo, espaço em disco (HD) e memória RAM.

## Especificação suplementar
A tabela 1 apresenta os resultados da especificação suplementar, contendo o id do requisito, o texto do requisito, sua categoria e sua classificação (Requisito funcional e não funcional). Seguem os resultados:

| ID    | Requisito   | Categoria | 
| ----- | ----------- | --------- | 
| INT07 | O aplicativo salvará a nota em até 1 segundo  | P       |
| INT09 | O aplicativo abrirá em um tempo limite de até 2 segundos  | P         | 
| INT10 | Deve ser possível fazer notas sem internet   | U         | 
| B19   | O aplicativo deve ser confiável e estável, evitando falhas ou perda de dados.  | C         | 
| B20   | O aplicativo deve ser intuitivo e fácil de usar, com uma interface clara e simples.  | U         | 
| B22   | O aplicativo deve garantir a segurança e privacidade das notas dos usuários, protegendo-as contra acesso não autorizado ou perda de dados.  | S         |
| B23   | O aplicativo deve ser acessível para usuários com deficiências visuais ou motoras, com recursos como suporte a leitores de tela e opções de zoom. | U    |
| B24   | O aplicativo deve estar disponível em várias plataformas, como iOS, Android, Windows e Mac, para garantir que os usuários possam acessar suas notas em qualquer dispositivo. | P         |
| B25   | O aplicativo deve estar disponível para uso sempre que o usuário precisar, sem interrupções ou indisponibilidades não planejadas. | U         | 
| B26   | O aplicativo deve ser otimizado para usar recursos do dispositivo de forma eficiente, como CPU, memória e bateria.   | P    | 
| B27   | O aplicativo deve ser facilmente mantido e atualizado, com um código limpo e bem documentado.      | S         | 
| ENT01 | O aplicativo deve permitir a criação de notas de forma fácil e rápida, sem muitas etapas   | U         | 
| ENT09 | O aplicativo deve permitir o login com diferentes opções, como e-mail, Google ou Facebook, para facilitar o acesso ao aplicativo após formatação ou troca de dispositivo     | S         | 
| GLO03 | Ser capaz de ler e editar arquivos de texto de outras fontes       | U       |
| ES01  | O aplicativo deve ser de fácil entendimento para pessoas mais leigas com tecnologia | U|
| ES02  | O aplicativo deve conter uma cor que estimula calma para trazer a sensação de bem estar ao utilizar o aplicativo| U| 
| ES03  | O aplicativo deve sempre guardar as notas que o usuário cria | C |
| ES04  | O MTBF(Mean Time Between Failures) do aplicativo deve ser de pelo menos 300 horas| C |
| ES05  | O MTTR(Mean Time To Repair) do aplicativo que é o tempo máximo permitido para reparo de uma falha do sistema deve ser 4 horas | C |

Tabela 1: Resultado da especificação suplementar. (Fonte: Dos autores,2023)

Para melhor entendimento da tabela 1, temos a tabela 2 que mostra os simbolos referentes aos IDs dos requisitos:

|ID| Significado|
|--|------------|
|B|Brainstorming|
|ENT|Entrevista|
|ES|Especificação Suplementar|
|GLO|Glossário|
|INT| Introspecção|

Tabela 2: Tabela de significados da tabela 1. (Fonte: Dos autores,2023)

## Bibliografia

> [1] FERRARI, Fabrício. FURPS+. Qualidade BR, 06 de maio de 2023. Disponível em: https://qualidadebr.wordpress.com/2008/07/10/furps/
>
> [2] SERRANO, Milene - Slides da aula 11. Disponibilizados pelo Professor

## Histórico de versão

| Versão | Data       | Descrição                         | Autor(es)  | Revisor(es) |
| ------ | ---------- | --------------------------------- | ---------- | ----------- |
| `1.0`  | 03/05/2023 | Criação do documento              | Ana e Kauã | Leonardo    |
| `1.1`  | 06/05/2023 | Adição de informações e do quadro | Ana e Kauã | Leonardo    |
| `1.2`  | 08/05/2023 | Finalizando documento             | Ana e Kauã | Leonardo    |
| `1.3`  | 04/06/2023 | Correções após a entrega 3        | Leonardo   | Ian         |
| `1.4`  | 17/06/2023 | Correções após entrega 5.1        | Kauã       |      -      |
