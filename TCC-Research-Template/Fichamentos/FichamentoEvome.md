

# EVOME: A Software Evolution Management Engine Based on Differential Factbase

X. Wu, M. Li and Y. Li, "EvoMe: A Software Evolution Management Engine Based on Differential Factbase," 2021 36th IEEE/ACM International Conference on Automated Software Engineering (ASE), Melbourne, Australia, 2021, pp. 1252-1256, doi: 10.1109/ASE51524.2021.9678795.

## 1. Fichamento de Conteúdo
O artigo apresenta o EVOME, uma ferramenta para o gerenciamento da evolução de software que utiliza uma abordagem baseada em fatos diferenciais. O EVOME é composto por dois componentes principais: extratores de fatos e um tradutor de consultas. Os extratores geram fatos em Datalog a partir de artefatos de software versionados, como código-fonte e históricos de commits, facilitando a análise de mudanças entre versões. O tradutor de consultas converte consultas na linguagem SQL-like do EVOME para Datalog, o que permite realizar inferências e análises sobre as versões do software. A avaliação do EVOME em projetos Maven revelou que a extração de fatos é o processo mais demorado, mas é um custo inicial único, enquanto a execução das consultas é eficiente, com um tempo médio de 3,6 segundos. Os resultados indicam que o EVOME é eficaz para tarefas de gerenciamento de evolução de software, como seleção de testes de regressão e análise de impacto de mudanças, e possui potencial para prototipagem rápida.

## 2. Fichamento Bibliográfico 
* _Fact Extractors_ (Extratores de Fatos): Componentes que geram fatos em Datalog a partir de artefatos de software versionados. Atualmente, existem extratores para fatos intra-versão e inter-versão (página 4).
* _Query Translator_ (Tradutor de Consultas): Utiliza Flex e GNU Bison para converter consultas em EVOME para o formato Datalog usado pelo motor Soufflé (página 5).
* _Version-Aware Query Language_ (Linguagem de Consulta Sensível à Versão): Linguagem usada pelo EVOME para consultas que consideram diferentes versões de código (página 8).
* _Differential Facts_ (Fatos Diferenciais): Fatos que são reutilizados para reduzir o custo de tempo na extração e execução das consultas (página 7).


## 3. Fichamento de Citações 

* _"The majority of the time is spent during the fact extraction stage. Since facts can best be stored and reused, time used for extraction is a one-time cost."_
* _"The results show that the EVOME tool achieves significant efficiency gains through differential fact reuse, with up to a 44% reduction in time cost."_
* _"The total time usage increases when the repository size grows bigger and the history length involved in the query increases."_


