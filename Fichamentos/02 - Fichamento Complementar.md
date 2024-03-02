# Performance Measurement of GraphQL API in Home ESS Data Server

E. Lee, K. Kwon and J. Yun, "Performance Measurement of GraphQL API in Home ESS Data Server," 2020 International Conference on Information and Communication Technology Convergence (ICTC), Jeju, Korea (South), 2020, pp. 1929-1931, doi: 10.1109/ICTC49870.2020.9289569. keywords: {Restful API;Relational databases;Time measurement;Information and communication technology;Servers;Time factors;Energy storage;home energy storage system;API;GraphQL;RESTful},

## 1. Fichamento de Conteúdo

O artigo tem como objetivo analisar a implementação de uma *API* utilizando GraphQL para o gerenciamento de sistemas de armazenamento de energia (ESS) em residências, visando a otimização da transmissão de dados. A motivação para a implementação vem das limitações encontradas em sistemas legados que utilizam *REST API*, os quais demandam várias requisições e consomem muitos recursos de dados. Por meio do uso de GraphQL, o estudo tem como objetivo a redução da quantidade de dados transmitidos e o tempo de resposta em comparação ao RESTful API. A análise de performance realizada foca no tempo de resposta e no consumo de dados móveis, destacando as vantagens do GraphQL em cenários que requerem a solicitação de uma grande quantidade de recursos. O estudo conclui que enquanto aplicações usando *REST API* podem ser mais adequadas para serviços simples com poucas requisições, o GraphQL se mostra mais eficaz para serviços complexos com várias requisições simultâneas.

## 2. Fichamento Bibliográfico 

- *GraphQL* é uma linguagem de consulta de dados desenvolvida pelo Facebook (página 1).
- *REST API* é uma abordagem para o desenvolvimento de *APIs* que trata cada parte do servidor como um recurso (página 2).
- *Performance Measurement* (Medição de desempenho) é a análise comparativa  visando entender de tempo de resposta e tamanho da resposta (página 3).

## 3. Fichamento de Citações 

- "This paper implemented an API server using GraphQL to transport only the data necessary for user of home ESS (Energy Storage System) management application."
- "In existing legacy system using RESTful API, the application had to send dozens of request messages to authenticate and get data from the server."
- "As a result, we found that it is better to use RESTful API for simple services with fewer resources to request at one time, but it is better to use GraphQL for complex services with a large number of resources to request at once."