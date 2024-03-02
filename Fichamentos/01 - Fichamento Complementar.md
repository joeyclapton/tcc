# Parsing gigabytes of JSON per second

Langdale, G., Lemire, D. Parsing gigabytes of JSON per second. _The VLDB Journal_ **28**, 941–960 (2019). https://doi.org/10.1007/s00778-019-00578-5

## 1. Fichamento de Conteúdo

O artigo aborda a importância e os desafios de analisar documentos JSON em alta velocidade, devido ao grande volume de dados trocados na web e em sistemas de banco de dados. Os autores apresentam a ferramenta simdjson, um analisador de JSON que utiliza instruções do tipo única instrução com múltiplos dados (SIMD, do inglês *Single Instruction, Multiple Data*) para processar gigabytes de JSON por segundo em um único núcleo de processador, alcançando uma eficiência significativamente maior em comparação com analisadores de JSON de referência, como RapidJSON. O artigo detalha o design e a implementação do simdjson, que inclui técnicas otimizadas para a detecção e análise de strings, números e outros tipos de dados encontrados em documentos JSON. Os autores também discutem o impacto do tamanho e da estrutura dos documentos JSON na performance do analisador e fornecem uma avaliação abrangente do simdjson usando uma variedade de documentos JSON. Os resultados demonstram que o simdjson pode oferecer um desempenho superior, tornando-o uma solução promissora para aplicações que exigem análise rápida de grandes volumes de dados JSON.

## 2. Fichamento Bibliográfico 

- *JSON Parsing* (Análise do JSON) é processo de análise e conversão de texto em formato JSON para uma representação em memória que programas de computador podem manipular facilmente (página 1-2).
- *UTF-8 Validation* (Validação UTF-8) é a validação que busca verificar a sequência de bytes  é um UTF-8 válido (página 4-5).
- *Parsing Performance* (Análise de performance)  refere-se à velocidade e eficiência com que um analisador JSON pode processar e converter documentos JSON em uma representação em memória (página 7-9).

## 3. Fichamento de Citações 

- "JavaScript Object Notation or JSON is a ubiquitous data exchange format on the web."
- "We present the first standard-compliant JSON parser to process gigabytes of data per second on a single core, using commodity processors."
- "Unlike other validating parsers, our software (simdjson) makes extensive use of single instruction and multiple data instructions." 
- "To our knowledge, publicly available JSON validating parsers make little use of SIMD instructions."
- "Every- thing else being equal, code that generates fewer instructions is faster."