The Silent Helper: The Impact of Continuous Integration on Code Reviews

Referência:
 Nathan Cassee, Bogdan Vasilescu, Alexander Serebrenik. The Silent Helper: The Impact of Continuous Integration on Code Reviews, in 2020 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER), DOI: [10.1109/SANER48275.2020.9054818](https://ieeexplore.ieee.org/abstract/document/9054818).

1. Fichamento de Conteúdo
O artigo investiga o impacto da Integração Contínua (CI, do inglês Continuous Integration) na revisão de código, considerando-a como uma atividade socio-técnica fundamental no desenvolvimento de software. O estudo analisa 685 projetos open-source no GitHub que adotaram o Travis-CI, a ferramenta de CI mais popular na plataforma. Os resultados mostram que, após a introdução da CI, há uma redução significativa na quantidade de comentários nas revisões de código, indicando que a automação elimina parte das discussões antes necessárias. Entretanto, essa redução na comunicação não está associada a uma diminuição no número de atualizações dos pull requests, sugerindo que os desenvolvedores continuem fazendo ajustes sem precisar de tantas interações. O conceito de "CI como um ajudante silencioso" surge, onde a automação absorve parte das responsabilidades dos revisores humanos. A análise estatística do estudo utilizou Design de Descontinuidade de Regressão (RDD, do inglês Regression Discontinuity Design) e evidenciou que, em média, a CI reduz até um comentário por pull request, otimizando o tempo dos revisores sem comprometer a qualidade do código.

2. Fichamento Bibliográfico
Continuous Integration (integração contínua) é um processo de automação que executa testes e builds frequentemente para facilitar a integração de código e melhorar a qualidade do software (página 1)
Code review (revisão de código) é um dos maiores determinantes da qualidade do software e um mecanismo de controle necessário em comunidades de código aberto, onde as contribuições de solicitação de pull geralmente vêm de colaboradores externos do projeto (página 1).
Travis-CI é a ferramenta de CI, baseada em nuvem, mais utilizada em projetos GitHub open-source (página 1)
Regression Discontinuity Design (design de descontinuidade de regressão) foi utilizado para analisar mudanças no volume de comentários antes e depois da adoção da CI. (página 3).

3. Fichamento de Citações
"The decrease in the amount of discussion, however, cannot be explained by a decrease in the number of updates of the pull requests." (página 1)
"Indeed, we find that on average the amount of discussion during pull request reviews decreases over time after the introduction of CI." (página 2)
"On average CI saves up to one review comment per pull request, giving rise to the idea of continuous integration as a silent helper." (página 2)
"Maintainers need to report and discuss these topics less frequently, which could indicate a reduction in the amount of communication needed during pull request reviews." (página 3)
"By modeling code review data around the introduction of Continuous Integration we find that the number of comments per code review decreases after the adoption of continuous integration, while the number of changes made during a code review remains constant." (página 10)
