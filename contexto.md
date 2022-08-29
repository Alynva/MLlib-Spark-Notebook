# Aprendizado de Máquina (Machine Learning - ML)

## O que é?

> "O aprendizado de máquina (ML) potencializa algumas das tecnologias mais importantes que usamos, de aplicativos de tradução a veículos autônomos. [...]
> 
> O ML oferece uma nova maneira de resolver problemas e responder a perguntas complexas. Em termos básicos, ML é o processo de treinamento de um software, chamado modelo, para fazer previsões úteis a partir de dados. Um modelo de ML representa a relação matemática entre os elementos de dados que um sistema de ML usa para fazer previsões.
> 
> Por exemplo, suponha que queiramos criar um aplicativo para prever chuvas. Poderíamos usar uma abordagem tradicional ou uma abordagem de ML. Usando uma abordagem tradicional, criaríamos uma representação baseada na física da atmosfera e da superfície da Terra, computando grandes quantidades de equações de dinâmica de fluidos. Isso é incrivelmente difícil.
> 
> Usando uma abordagem de ML, daríamos a um modelo de ML enormes quantidades de dados climáticos até que o modelo de ML eventualmente aprendesse a relação matemática entre padrões climáticos que produzem diferentes quantidades de chuva. Em seguida, daríamos ao modelo os dados climáticos atuais e ele preveria a quantidade de chuva."
> 
> \- Google Developers (https://developers.google.com/machine-learning/intro-to-ml/what-is-ml)

## Categorias

É possível separar os algoritmos de aprendizagem de máquina em três categorias:

- Aprendizado supervisionado
- Aprendizado não supervisionado
- Aprendizado reforçado

### Supervisionado

O aprendizado supervisionado cria modelos que realizam predições após terem recebido muitos dados com as corretas respostas, dessa forma descobrindo as conexões entre os elementos dos dados que produzem as respostas corretas. É chamado de "supervisionado" no sentido de que um humano dá ao sistema de ML um conjunto suficiente de dados e suas responstas esperadas.

#### Regressão

<div align="center">

![Exemplo de Regressão](./assets/linear-regression.gif)

</div>

Um modelo de regressão produz um resultado numérico. Por exemplo um modelo climático que prevê a quantidade de chuva, em litros por metro quadrado, é um modelo de regressão.

#### Classificação

<div align="center">

![Exemplo de Classificação](./assets/classification.jfif)

</div>

Um modelo de classificação é utilizado para dizer a qual classe um objeto ou dado pertence, e pode ser usado para classificar imagens, por exemplo.

### Não supervisionado

O aprendizado não supervisionado cria modelos sem receber nenhuma informação de qual é a resposta correta. O objetivo é encontrar padrões que façam algum sentido dentro dos dados. Em outras palavras, o modelo não tem nenhuma dica de como categorizar cada pedaço de dado, ao invés disso, ele deve inferir suas prórprias regras.

#### Clusterização

<div align="center">

![Exemplo de Clustarização](./assets/K-means_convergence.gif)

</div>

Um modelo de clusterização são utilizados para criar agrupamentos "escondidos" nos dados, por exemplo, agrupar filmes por gênero, clientes por comportamento de compra (tipo de produto, por exemplo), pessoas usuárias por estilo musical. É utilizado para criar sistemas de recomendação de serviços de streaming de música ou séries, por exemplo.

### Reforçado

O aprendizado reforçado cria modelos que fazem predições recebendo recompensas ou penalidades baseado nas ações realizadas dentro de um embiante. Um sistema de aprendizado reforçado gera uma política que define a melhor estratégia para receber mais recompensas. É muito utilizado para treinar robôs ao realizar tarefas, como antar pelo ambiente.

# Processamento Paralelo e Distribuído (PDD)

## Resilient Distributed Dataset (RDD)