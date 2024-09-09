

# What Code Is Deliberately Excluded from Test Coverage and Why?

A. Hora, "What Code Is Deliberately Excluded from Test Coverage and Why?," 2021 IEEE/ACM 18th International Conference on Mining Software Repositories (MSR), Madrid, Spain, 2021, pp. 392-402, doi: 10.1109/MSR52588.2021.00051.

## 1. Fichamento de Conteúdo
 O artigo explora práticas de exclusão de código em relatórios de cobertura de testes, com foco em entender o que e por que determinados códigos são excluídos das análises de cobertura. A pesquisa abrange 55 projetos Python para analisar como e por que os desenvolvedores utilizam a funcionalidade de exclusão oferecida por ferramentas de cobertura, como Coverage.py. Os resultados revelam que mais de um terço dos projetos analisados emprega exclusão deliberada de código. A maior parte do código é excluída desde a sua criação, com uma minoria sendo adicionada posteriormente. Os principais tipos de código excluídos incluem instruções condicionais e de tratamento de exceções, além de código específico de plataforma e de importações condicionais. A exclusão geralmente ocorre devido à complexidade, ao fato de o código ser não executável ou à sua baixa relevância para os testes. O estudo sugere melhorias na análise de cobertura e discute implicações para tornar os relatórios de cobertura mais precisos e úteis.

## 2. Fichamento Bibliográfico 

* _Coverage Exclusion_ (Exclusão de Cobertura) é a prática de remover certos segmentos de código dos relatórios de cobertura de testes para evitar que sejam contabilizados como não testados. Essa prática pode levar a relatórios de cobertura enviesados e enganosos (página 2).
* _Commit History_ (Histórico de Commits) refere-se ao registro das alterações feitas no código ao longo do tempo, incluindo adições, modificações e exclusões. O histórico de commits é analisado para identificar padrões de exclusão intencional de código (página 5).
* _Coala Project_ (Projeto Coala) é um exemplo de projeto que implementou diretrizes para a exclusão de código, forçando os desenvolvedores a fornecer explicações detalhadas para suas ações. Este projeto serve como um modelo positivo para práticas de exclusão de cobertura (página 12).

## 3. Fichamento de Citações 

* _"More than one-third of the studied projects engage in intentional code exclusion, which can lead to biased and misleading coverage reports"_ (página 7).
* _"Intentional code exclusion is often applied from the code's creation, and in 25% of cases, exclusion is added later, with an average time of 24 days"_ (página 8).
* _"The types of code most frequently excluded include non-executable code, debugging code, and defensive code, as well as platform-specific code and conditional imports"_ (página 10).
* _The main reasons for code exclusion are code complexity, level of detail, and issues such as parallelism and non-determinism"_ (página 11).
