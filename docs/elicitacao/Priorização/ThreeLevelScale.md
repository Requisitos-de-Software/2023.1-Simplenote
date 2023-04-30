# Three Level Scale ou TLS

## Definição

**Three Level** Scale ou TLS é uma tecnica de priorização que separa os requisitos em 3 escalas que são: baixa, média e alta prioridade. É importante salientar que esta tecnica gera uma priorização subjetiva, isto devido à politicas de empresas e metas de negócio.

## Quadrantes

- **Alta prioridade**: São tanto importantes quanto urgentes, estes requisitos devem ser implementados o mais rápido o possível. </br>
- **Média prioridade**: Requisitos que são importantes, entretanto, não são urgentes.</br>
- **Baixa prioridade**: Não são nem importantes, e nem urgentes.</br>
- **O "quarto quadrante"**: São requisitos que para alguns stakeholders são urgentes, entretanto, não são necessários para atingir a meta de negócio.</br>

## Resultados

A tabela a seguir mostra os resultados alcançados após a priorização dos requisitos:

#### Requisitos funcionais:

| Identificador| Requisito | Quadrante|
|---------------|-----------|-----------|
|INT01|O usuário deve poder fazer anotação| Alta prioridade|
|INT02|O usuário deve poder excluir anotação| Alta prioridade|
|INT03|O usuário deve poder recuperar anotação excluida| Baixa prioridade|
|INT04|O usuário poderá compartilhar suas anotações com outras pessoas atraves de um link| Baixa prioridade|
|INT05| O usuário deve poder usar Markdown| Alta prioridade|
|INT06|O usuário deve poder vizualizar Anotação| Alta prioridade|
|INT08|	Para o primeiro acesso do usuário, deve ter uma breve explicação sobre o aplicativo e as suas funcionalidades|Quarto quadrante|
|INT11|O usuário poderia separar suas notas em pastas| Média prioridade|
|INT12|O usuário poderia definir templates para suas notas| Baixa prioridade|
|INT13|O usuário deve poder editar Anotação|Alta prioridade|
|INT14|O usuário deve poder buscar notas por palavras-chave| Média prioridade|
|INT15|O usuário deveria poder pesquisar por suas anotações|Média prioridade|
|INT16|O usuário poderia ver informações sobre sua nota| Alta prioridade|
|INT17|	O usuário poderia importar ou exportar modelos de layout| Baixa prioridade|
|GLO01|Possibilidade de usar marcação de texto (negrito, itálico, etc)|Baixa prioridade|
|GLO04|Possibilidade de criar checklists dentro das notas| Baixa prioridade|
|GLO05|Salvamento automático das notas|Média prioridade|
|GLO06|Capacidade de criar no dispositivo um arquivo cópia de uma nota|Quarto quadrante|
|ENT02|O aplicativo deve permitir a sincronização das notas em tempo real em diferentes dispositivos| Baixa prioridade|
|ENT03|O aplicativo deve permitir a adição de etiquetas nas notas para facilitar a organização|Média prioridade|
|ENT04|O aplicativo deve possuir um editor de texto avançado para permitir a utilização da função `toggle`|Quarto quadrante|
|ENT05|O aplicativo deve permitir o compartilhamento de notas com outras pessoas, por meio de um link ou por e-mail|Baixa prioridade|
|ENT06|O aplicativo deve ser acessível em diferentes plataformas, como computadores, tablets e smartphones|Alta prioridade|
|ENT07| O aplicativo deve permitir a criação de backups automáticos ou manuais das notas para evitar perda de informação
|ENT09| O aplicativo deve permitir o login com diferentes opções, como e-mail, Google ou Facebook, para facilitar o acesso ao aplicativo após formatação ou troca de dispositivo|Média prioridade|

#### Requisitos não funcionais:

| Identificador| Requisito | Quadrante|
|---------------|-----------|-----------|
|INT07|O aplicativo salvará a nota em até 1 segundo| Alta prioridade|
|INT09|O aplicativo abrirá em um tempo limite de até 2 segundos| Média prioridade|
|INT10|O usuário deveria poder fazer notas sem internet| Alta prioridade|
|INT18|A interface deve ser simples e intuitiva| Alta prioridade|
|GLO02|Estar disponível em diversos dispositivos (celulares, laptops, tablets, etc)| Alta prioridade|
|GLO03|Ser capaz de ler e editar arquivos de texto de outras fontes|Baixa prioridade|
|ENT01|O aplicativo deve permitir a criação de notas de forma fácil e rápida, sem muitas etapas| Alta prioridade|
|ENT08|O aplicativo deve ter uma interface simples e fácil de usar, sem muitas opções desnecessárias|Alta prioridade|



## Bibliografia

[1] https://aprender3.unb.br/pluginfile.php/2523072/mod_resource/content/2/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf

## Histórico de versão
| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 28/04/2023 | Inicialização do documento | Kauã e João | Mylena |
| 1.1 |28/04/2023| Adicionando requisitos e suas prioridades |Kauã e João|Mylena|
