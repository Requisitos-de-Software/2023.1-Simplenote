# Cenários

## Introdução
Um diagrama de casos de uso é uma representação visual que descreve as interações entre um sistema e os usuários externos. Ele é composto por uma série de ações, chamadas de casos de uso, que ilustram as principais funcionalidades do sistema e como elas são executadas pelos usuários. Essa ferramenta é útil para documentar e comunicar de forma clara e concisa o comportamento esperado do sistema, bem como a interação entre seus usuários e suas funcionalidades.

## Metodologia
Para a criação desse artefato foi utilizado a abordagem tradicional, ou seja, representação os casos de uso através de uma diagrama UML. A ferramenta utilizada para a criação do diagrama foi o LucidChart, um software online para criação de diagramas.

## Componentes
### Atores
Representam as pessoas que realmente executam os casos de uso. São representados por bonecos palito.

<div style="text-align: center">
<p>Figura 1: Ator</p>
</div>
<center>
<img width="160px" src="../img/ator-usecase.png">
</center>

<div style="text-align: center">
<p>Fonte: Ian Costa, LucidChart </p>
</div>

### Caso de uso
Representam os diferentes usos que um usuário pode ter. São representados por um formato oval rotulado.

<div style="text-align: center">
<p>Figura 2: Caso de uso</p>
</div>
<center>
<img width="220px" src="../img/caso-de-uso-usecase.png">
</center>

<div style="text-align: center">
<p>Fonte: Ian Costa, LucidChart </p>
</div>

### Comunicação
Ação que comunica o usuário ao caso de uso. Pode ser definida como inclusão ou exclusão.

Inclusão: Refere-se à relação em que um caso de uso requer a funcionalidade de outro caso de uso para ser executado. Em termos simples, quando um caso de uso A inclui um caso de uso B, significa que sempre que o caso de uso A for executado, o caso de uso B também será executado obrigatoriamente.

- Notação no diagrama: *<<includes\>\>*

Extensão: Por outro lado, a extensão implica que o caso de uso atual funcionará normalmente, mas alguns novos passos serão adicionados por meio de um caso de uso estendido. Em outras palavras, quando o caso de uso A é estendido pelo caso de uso B, se o caso de uso A for executado, o caso de uso B pode ou não ser executado como uma extensão opcional.
- Notação no diagrama: *<<extends\>\>*

<div style="text-align: center">
<p>Figura 2: Caso de uso</p>
</div>
<center>
<img width="220px" src="../img/comunicacao-usecase.png">
</center>

<div style="text-align: center">
<p>Fonte: Ian Costa, LucidChart </p>
</div>

### Limite do Sistema
Define um escopo do sistema para os casos de uso. É representado por um retângulo englobando os Casos de  Uso (forma oval rotulada)

<div style="text-align: center">
<p>Figura 2: Limite do Sistema</p>
</div>
<center>
<img width="230px" src="../img/sistema-usecase.png">
</center>

<div style="text-align: center">
<p>Fonte: Ian Costa, LucidChart </p>
</div>