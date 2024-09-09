

# Maintenance and Evolution: GrimoireLab Graal

W. Meijer, D. Visscher, E. de Haan, M. Schröder, L. Visscher, A. Capiluppi, and I. Botez. 2022. Maintenance and evolution: GrimoireLab graal. In Proceedings of the 19th International Conference on Mining Software Repositories (MSR '22). Association for Computing Machinery, New York, NY, USA, 732–734. https://doi.org/10.1145/3524842.3528521

## 1. Fichamento de Conteúdo
O artigo explora a evolução e manutenção de software open-source utilizando o GrimoireLab Graal como estudo de caso. O foco está na aplicação de tarefas anti-regressivas para mitigar o aumento de complexidade que ocorre com a evolução do software. O estudo revela que, ao aplicar refatoração e outras técnicas anti-regressivas, os indicadores de qualidade do software, como complexidade ciclomática (CCN), número de métodos (NOM) e linhas de código (LOC), melhoraram, com a média desses indicadores diminuindo. A refatoração substituiu uma arquitetura de camadas por uma arquitetura baseada em padrões de fábrica e estratégia, resultando em uma maior prontidão para evolução e uma menor complexidade ao adicionar novas funcionalidades. O artigo também sugere que o uso de métricas de qualidade e insights de desenvolvedores pode auxiliar na identificação de problemas e na realização de manutenção eficiente.

## 2. Fichamento Bibliográfico 
* _Anti-regressive tasks_ (tarefas anti-regressivas): Métodos aplicados para reduzir a complexidade do software e combater o desgaste do software durante sua evolução (página 1).
* _Cyclomatic Complexity_ (Complexidade Ciclomática): Métrica que mede a complexidade do código com base no número de caminhos independentes através do código (página 2).
* _Number of Methods_ (Número de Métodos): Métrica que indica a quantidade de métodos definidos em uma classe, refletindo a complexidade do software (página 2).
* _Lines of Code_ (Linhas de Código): Métrica que contabiliza o número total de linhas de código, usada para medir o tamanho do software (página 2).


## 3. Fichamento de Citações 
* _"Anti-regressive tasks are methods by which we can reduce complexity in an effort to combat software decay."_
* _"The complexity of E-type systems will continue to increase if no anti-regressive efforts are made."_
* _"By performing a small case study it was observed that, in the original version of Graal, the CCN of back-end components increased significantly when adding support for a new third-party tool, whilst in the refactored version no files had to be altered."_
* _"The impact of the refactor was tested two-fold: by measuring the change in metrics overall, and by measuring how these metrics change during software evolution."_

