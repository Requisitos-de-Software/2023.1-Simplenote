# Especificação Suplementar

## Introdução
A Especificação Suplementar é uma tecnica de modelagem que captura os requisitos de sistema que não foram identificados nos casos de uso, como por exemplo: requisitos reguladores, atributos de qualidade do sistema, sistemas operacionais, requisitos de compatiblidade e restrições de design.

## Metodologia 
Para a produção deste artefacto, foi utilizado o modelo FURPS+, na qual definimos os requisitos de sistema com base em:
  - Funcionalidade;
  - Usabilidade;
  - Confiabilidade;
  - Performance;
  - Suportabilidade;

## Definições da especificação suplementar
### Funcionalidade
Representa os aspectos funcionais do software, aqui, temos diversos subtópicos que variam de acordo com a aplicação.</br>
Os requisitos funcionais podem ser encontrados nos [casos de uso]()

### Usabilidade
Avalia a interface com o usuário, podemos tratar a prevenção de erros, estética, design, documentação, consistências e padrões.

### Confiabilidade

### Performance

### Suportabilidade

### +
O acrônimo "+" se refere à :
- Requisitos de design: Linguagens de programação, processo de software, uso de ferramentas de desenvolvimento, biblioteca de classes, etc.
- Requisitos de implementação: Se restringem ao código ou algo do sistema.

## Especificação suplementar
|    ID    |                                Requisito                                                   |Categoria|
|----------|--------------------------------------------------------------------------------------------|--------------|
|  INT07  |       O aplicativo salvará a nota em até 1 segundo                                          ||  
|  INT09  |       O aplicativo abrirá em um tempo limite de até 2 segundos                              ||    
|  INT10  |       Deve ser possível fazer notas sem internet                                            |U|  
|  B19    |       O aplicativo deve ser confiável e estável, evitando falhas ou perda de dados.         |U|
|  B20    |       O aplicativo deve ser intuitivo e fácil de usar, com uma interface clara e simples.   |U|
|  B22    |       O aplicativo deve garantir a segurança e privacidade das notas dos usuários, protegendo-as contra acesso não autorizado ou perda de dados.||
|  B23    |       O aplicativo deve ser acessível para usuários com deficiências visuais ou motoras, com recursos como suporte a leitores de tela e opções de zoom.||
|  B24    |       O aplicativo deve estar disponível em várias plataformas, como iOS, Android, Windows e Mac, para garantir que os usuários possam acessar suas notas em qualquer dispositivo.||
|  B25    |       O aplicativo deve estar disponível para uso sempre que o usuário precisar, sem interrupções ou indisponibilidades não planejadas.|U|
|  B26    |       O aplicativo deve ser otimizado para usar recursos do dispositivo de forma eficiente, como CPU, memória e bateria.||
|  B27    |       O aplicativo deve ser facilmente mantido e atualizado, com um código limpo e bem documentado.|+|
|  ENT01  |       O aplicativo deve permitir a criação de notas de forma fácil e rápida, sem muitas etapas|U|
|  ENT09  |       O aplicativo deve permitir o login com diferentes opções, como e-mail, Google ou Facebook, para facilitar o acesso ao aplicativo após formatação ou troca de dispositivo||
|  GLO03  |       Ser capaz de ler e editar arquivos de texto de outras fontes||

## Bibliografia
[1] https://aprender3.unb.br/pluginfile.php/2523104/mod_resource/content/1/Especificacao_Suplementar_Exemplo.pdf
[2] https://qualidadebr.wordpress.com/2008/07/10/furps/

## Histórico de versão
| Versão | Data | Descrição| Autor(es)| Revisor(es)
|--|--|--|--|--|
| `1.0` |03/05/2023|Criação do documento| Ana e Kauã | Leonardo|
| `1.1`|06/05/2023|Adição de informações e do quadro | Ana e Kauã | Leonardo|

