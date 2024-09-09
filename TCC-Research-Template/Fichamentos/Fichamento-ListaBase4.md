

# Characterizing High-Quality Test Methods: A First Empirical Study

Victor Veloso and Andre Hora. 2022. Characterizing high-quality test methods: a first empirical study. In Proceedings of the 19th International Conference on Mining Software Repositories (MSR '22). Association for Computing Machinery, New York, NY, USA, 265–269. https://doi.org/10.1145/3524842.3529092

## 1. Fichamento de Conteúdo
O artigo investiga a qualidade de métodos de teste em projetos de código aberto utilizando Mutation Testing, com o objetivo de identificar características distintivas entre métodos de teste de alta e baixa qualidade. A pesquisa analisou métodos de teste classificados como melhores, aleatórios e piores, com base em métricas como número de linhas de código, número de assertivas e modificações. O estudo encontrou diferenças estatisticamente significativas entre esses grupos, mas com efeitos pequenos a muito pequenos. Além disso, foi observado que métodos de teste de baixa qualidade frequentemente apresentam "test smells" críticos, como Sleepy Tests e General Fixture, enquanto os métodos de alta qualidade têm menos desses odores críticos e mais odores relacionados à legibilidade, como Magic Number Test e Assertion Roulette. Os resultados sugerem que, embora não haja grandes variações em termos de tamanho e número de assertivas, a presença de certos odores de teste pode indicar a eficácia de um método de teste em identificar bugs reais.

## 2. Fichamento Bibliográfico 
* _Critical Test Smells_ (fedor em testes críticos) Métodos de teste de baixa qualidade frequentemente incluem odores críticos como _Sleepy Tests_ e _General Fixture_, enquanto métodos de alta qualidade têm odores relacionados à legibilidade, como _Magic Number Test_ (página 5).

* _Test Effectiveness_ (Efetividade dos testes) A presença de certos test smells, como Assertion Roulette, está mais associada à legibilidade dos testes e não diretamente à capacidade de detectar bugs (página 5).

* _Number of Bad Asserts_ (Número de asserções ruins) Métodos de teste de alta qualidade, em média, possuem mais assertivas (3.7) do que os de baixa qualidade (1.6), mas a diferença é pequena (página 4).
* _Number of Lines of Code_ (Número de linhas de código) A média de linhas de código dos melhores métodos de teste é ligeiramente menor (10) do que a dos piores (9), com um efeito muito pequeno (página 4).

## 3. Fichamento de Citações 
* _"We find a statistically significant difference in all metrics, with at least a very small effect"_ (página 4).
* _"High-quality test methods have less critical test smells, which are related to test readability, like Magic Number Test and Assertion Roulette"_ (página 5).
* _"The presence of some test smells is associated with the test suite’s ability in catching real bugs"_ (página 6).


