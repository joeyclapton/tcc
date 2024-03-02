# A Cost-efficient Approach to Building in Continuous Integration

Xianhao Jin and Francisco Servant. 2020. A cost-efficient approach to building in continuous integration. In Proceedings of the ACM/IEEE 42nd International Conference on Software Engineering (ICSE '20). Association for Computing Machinery, New York, NY, USA, 13–25. https://doi.org/10.1145/3377811.3380437

## 1. Fichamento de Conteúdo

O artigo tem como objetivo propor uma nova abordagem chamada SmartBuildSkip para reduzir os custos da prática de Integração Contínua (CI) no desenvolvimento de software. O foco do estudo está em diminuir a quantidade de compilações executadas, mantendo a capacidade de identificar falhas de maneira precoce. Foi desenvolvido a técnica baseando-se em duas hipóteses : a grande parte das *builds* em CI são finalizadas com sucesso e muitas falhas ocorrem após uma falha inicial. A ferramenta utiliza de aprendizado de máquina para prever o resultado das builds e conseguir decidir quais devem ser executadas ou ignoradas. A técnica proposta é avaliada em termos de eficácia na previsão de falhas e a economia de recursos, demonstrando uma economia significativa de *builds* com um atraso considerado aceitável na detecção de falhas. Os resultados do artigo indicam que a ferramenta SmartBuildSkip pode melhorar a eficiência do processo de CI, reduzindo os custos sem comprometer a qualidade do software.

## 2. Fichamento Bibliográfico

- *Continuous Integration* (Integração Contínua) é a prática de engenharia de software que tem como objetivo a integração de mudanças e teste automatizados alterados frequentemente (Página 1).
- *Builds* (Construção) é o processo de compilar um código fonte e transforma em um executável (Página 1).
- *Build Prediction* (Predição de Builds) é o uso de aprendizado de máquina para prever o resultado de uma *build* (Página 15)

## 3. Fichamento de Citações

- "Continuous integration (CI) is a widely used practice in modern software engineering. Unfortunately, it is also an expensive practice" 
- "We propose SmartBuildSkip, a novel approach to reduce the cost of CI based on automatic build-outcome prediction"
- "The conceptual separation of build failures into first and subsequent failures, to improve the effectiveness of build prediction models"