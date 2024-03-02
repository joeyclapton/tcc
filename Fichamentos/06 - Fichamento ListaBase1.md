# An Empirical Study on Quality Issues of eBay’s Big Data SQL Analytics Platform

Feng Zhu, Lijie Xu, Gang Ma, Shuping Ji, Jie Wang, Gang Wang, Hongyi Zhang, Kun Wan, Mingming Wang, Xingchao Zhang, Yuming Wang, and Jingpin Li. 2022. An empirical study on quality issues of eBay's big data SQL analytics platform. In Proceedings of the 44th International Conference on Software Engineering: Software Engineering in Practice (ICSE-SEIP '22). Association for Computing Machinery, New York, NY, USA, 33–42. https://doi.org/10.1145/3510457.3513034

## 1. Fichamento de Conteúdo

O artigo apresenta um estudo sobre os problemas de qualidade enfrentados pela plataforma de análise SQL de *big data* da eBay, conhecido como Carmel. O estudo analisa 1,884 questões sobre qualidade de serviço ocorridas na plataforma ao longo de um ano. O objetivo do estudo é identificar causas raízes e oferecer ideias para mitigação dos problemas. O artigo classifica os problemas em: falhas de trabalho, lentidão e resultados incorretos, identificando que a maior parte dos problemas decorre de falhas internas do sistema, erros dos usuários e incompatibilidades entre componentes da plataforma. Os resultados oferecem uma visão ampla sobre os desafios enfrentados durante as análises e sugerem direções para pesquisas futuras, incluindo o desenvolvimento de ferramentas automáticas de suporte e a melhoria da confiabilidade e desempenho de tais plataformas.

## 2. Fichamento Bibliográfico 

- *SQL Anti-Patterns* (Anti padrões SQL) são padrões e configurações inadequadas que são definidas pelos usuários, gerando diminuição da performance e ocasionando erros no sistema (Página 4).
- *Big Data* (Grandes dados) são conjuntos de dados de grandes tamanhos, contendo maior variedade de dados e complexidade (Página 1).
- *SQL Query* (Consulta SQL) são comandos usados para recuperação e tratamento de informações dentro de um banco de dados (Página 1).

## 3. Fichamento de Citações 

- "Despite the popularity of open-source based big data SQL analytic platforms, to the best of our knowledge, few studies were carried out for them, including the service quality, maintenance and evolution."

- "More than 70% user-side faults caused by SQL anti-patterns, including code smells, low performant queries, ambiguous operators, and inefficient data mode design."

- "In the past, eBay had years of investment in Teradata as its business intelligence solution for company-wide data analytics. However, with the continuously increasing data volume, the solution from a third-party service vendor like Teradata not only exposes limitations on scalability and flexibility, but also becomes more expensive."