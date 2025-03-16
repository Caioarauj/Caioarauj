What Helped, and What Did Not? An Evaluation of the Strategies to Improve Continuous Integration

Referência:
 Xianhao Jin, Francisco Servant. What Helped, and What Did Not? An Evaluation of the Strategies to Improve Continuous Integration, in 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE), [10.1109/ICSE43902.2021.00031](https://ieeexplore.ieee.org/document/9401965).


1. Fichamento de Conteúdo
O artigo analisa as estratégias para melhorar a Integração Contínua (CI, do inglês Continuous Integration), focando na redução de tempo de feedback e custo computacional. O estudo avaliou 14 variantes de 10 técnicas de priorização e seleção, tanto em nível de testes quanto de builds, utilizando 100 projetos reais do TravisTorrent. Foram analisadas métricas como tempo economizado, número de builds salvos e impacto na detecção de falhas. Os autores identificaram trade-offs entre economizar recursos e atrasar a identificação de falhas, destacando que técnicas de seleção em nível de build são mais eficazes na redução de custos, enquanto técnicas de priorização de testes oferecem o melhor tempo de resposta. O estudo também apontou que estratégias treinadas em dados de múltiplos projetos têm um desempenho inferior, pois se tornam mais conservadoras na detecção de builds que podem ser ignorados. Como conclusão, os autores sugerem combinar abordagens de priorização e seleção para maximizar os benefícios da CI.

2. Fichamento Bibliográfico
Continuous Integration (integração contínua): Prática de desenvolvimento de software em que o código é integrado a um repositório compartilhado várias vezes ao dia. (Introdução)
Time-to-feedback reduction (Redução do tempo de feedback): Estratégias que priorizam testes que provavelmente falharão, reduzindo o tempo até que um erro seja detectado. (Seção II)
Computational-cost reduction (Redução de custo computacional): Abordagens que selecionam quais testes ou builds executar, economizando recursos computacionais. (Seção II)
TravisTorrent: Conjunto de dados usado para analisar projetos de software hospedados no GitHub e testados no Travis CI, contendo histórico de builds de mais de 1.300 projetos. (Seção III)
Trade-off entre custo e confiabilidade: Algumas técnicas de economia podem falhar na detecção de erros importantes. (Seção VI)

3. Fichamento de Citações
"The cost of CI reaches millions of dollars, e.g., at Google and Microsoft." (página 213)
"Skipping full builds was a better strategy for saving cost." (página 218)
"Techniques trained across multiple projects became more conservative, skipping fewer builds." (página 219)
"Our observations suggest that future techniques should combine prioritization and selection to maximize CI benefits." (página 220)
"Build-selection techniques provided the highest cost savings, while test-prioritization techniques offered the best early failure detection." (página 221)
