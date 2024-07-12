# Banco-de-dados-MVP

### 📋 Descrilção do projeto

```
Detalhamento
1. Busca pelos dados

Escolha uma base de dados para utilizar em seu MVP de forma que se possa atingir os objetivos traçados na etapa anterior.

Há inúmeras bases de dados gratuitas disponíveis na web, por exemplo:

Google Cloud Public Datasets (https://cloud.google.com/datasets)
Kaggle (https://www.kaggle.com/datasets)
Portal da Transparência (https://portaldatransparencia.gov.br/)
IMDB (https://datasets.imdbws.com/)
Tableau (https://www.tableau.com/learn/articles/free-public-data-sets)
Stanford Large Network Dataset Collection (https://snap.stanford.edu/data/index.html)
Yelp Open Dataset (https://www.yelp.ca/dataset)
Discutiremos sobre bases de dados abertas disponíveis para o MVP no Discord e iremos montar colaborativamente um repositório de possibilidades.

Caso haja uma licença de uso para o conjunto de dados escolhido, isto deve constar na documentação do MVP.

 

2. Coleta

Uma vez definido o conjunto de dados, devemos coletar e armazená-los na nuvem.

É possível que, a partir de sua escolha do conjunto de dados, seja necessária uma etapa de construção de robôs de coleta, e.g. via Web Scraping. Neste caso, atente-se para questões éticas sobre se é possível utilizar os robôs de coleta de informação nos sites escolhidos.

Caso tenha optado por utilizar um conjunto de dados real da empresa onde trabalha, tenha bastante cuidado com a confidencialidade destes dados e/ou das análises que serão feitas em sequência.

 

3. Modelagem

Você deve construir um modelo de dados em Esquema Estrela ou Snowflake, como em um Data Warehouse, ou flat por cada conceito, como em um Data Lake.

Independentemente do modelo, deve ser construído um Catálogo de Dados contendo minimamente uma descrição detalhada dos dados e seus domínios, contendo valores mínimos e máximos esperados para dados numéricos, e possíveis categorias para dados categóricos.

Este modelo deve também descrever a linhagem dos dados, de onde os mesmos foram baixados e qual técnica foi utilizada para compor o conjunto de dados, caso haja.

 

4. Carga

Nesta etapa, será feita a carga dos dados para o Data Warehouse/Data Lake. Na avaliação, nesta etapa, será dado valor pela utilização da pipelines de ETL (Extração, Transformação e Carga) na plataforma de dados utilizada. Iremos discutir pipelines de ETL na Plataforma Databricks durante nossos encontros pelo Zoom e no Discord.

Deve-se documentar os processos de transformação e carga, principalmente os de transformação, e.g. a junção e conciliação de dois conjuntos de dados diferentes.

 

5. Análise

Vamos dividir a etapa de análise em duas: qualidade de dados e solução do problema.

 

          a. Qualidade de dados

Deve ser feita uma análise da qualidade para cada atributo do conjunto de dados. Existem problemas no conjunto de dados? Caso haja, como esses problemas podem ser resolvidos para que não afetem as respostas das perguntas que quer solucionar?

É possível que não se encontre problemas nos conjuntos de dados, em alguns casos há conjuntos de dados curados e já bem tratados antes de serem disponibilizados. Entretanto, mesmo nestes casos, espera-se que seja feita uma análise de valores por atributo e que se demonstre que não se encontrou problemas.

 

          b. Solução do problema

Chegou o momento de se solucionar o problema em questão, definido preliminarmente nos objetivos. Deve-se buscar respostas para as perguntas elencadas. Para cada resposta obtida tecnicamente através da análise dos dados deve haver uma discussão do seu resultado, conectando os números obtidos às respostas ao problema a ser solucionado.

Ao final, deve haver uma discussão de uma forma geral sobre a solução do problema a partir das discussões de cada resposta.

Aqui, podem ser utilizadas bibliotecas Python vistas na disciplina Análise Exploratória e Pré-Processamento de Dados, ou as ferramentas vistas na disciplina Visualização de Informação. Entretanto, caso não tenha ainda cursado estas disciplinas, é possível responder as perguntas do objetivo somente através da linguagem SQL, objeto da disciplina de Banco de Dados ou através da linguagem de consulta do banco NoSQL escolhido, objeto da disciplina de Data Warehouse.
```


### 📋  Busca pelos dados

Plataforma para a coleta do dataset:

```
https://www.kaggle.com/datasets
```

### 🔧 Coleta

Base de dados para utilizar no MVP:
Uma vez definido o conjunto de dados, devemos coletar e armazená-los na nuvem.



```
https://www.kaggle.com/datasets/dillonmyrick/bike-store-sample-database
```



## ⚙️ Modelagem

A modelagem Snowflake é uma técnica de design de banco de dados que normaliza dados de dimensão em várias tabelas menores, criando uma estrutura mais organizada e sem redundâncias. Embora essa abordagem possa trazer benefícios em termos de integridade e economia de espaço, ela também pode introduzir complexidade e impactar o desempenho das consultas. Portanto, a escolha entre um esquema Snowflake e um esquema estrela deve ser baseada nos requisitos específicos do projeto e nas prioridades de desempenho e manutenção.

![Modelagem](https://github.com/LuisFelipeSeabra/Banco-de-dados-MVP/blob/master/imagens/DatabaseDiagram.jpeg)

Modelagem realizada em:
```
https://app.genmymodel.com/api/login
```


### 🔩 Análise

A análise da qualidade dos dados é um componente crítico de qualquer estratégia de gestão de dados. Ela ajuda a assegurar que as decisões sejam baseadas em informações precisas e confiáveis, melhorando a eficiência operacional, a satisfação do cliente, e a conformidade regulatória, além de reduzir custos e promover a segurança e a privacidade dos dados.
No item a. verificaremos todas as análises que foram efetuadas com o intuito de entender melhor o conjunto de dados.

[Notebook](https://github.com/LuisFelipeSeabra/Banco-de-dados-MVP/blob/master/MVP/MVP-notebook.ipynb)

### ⌨️ Trabalho em PDF

[Link para o PDF do projeto](https://github.com/LuisFelipeSeabra/Banco-de-dados-MVP/blob/master/MVP/Descri%C3%A7%C3%A3o_projeto.pdf)

