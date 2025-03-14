The Silent Helper: The Impact of Continuous Integration on Code Reviews
Referência:
 Nathan Cassee, Bogdan Vasilescu, Alexander Serebrenik. The Silent Helper: The Impact of Continuous Integration on Code Reviews, in 2020 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER), DOI: 10.1109/SANER48275.2020.9054818

1. Fichamento de Conteúdo
O artigo investiga o impacto da Integração Contínua (CI) na revisão de código, considerando-a como uma atividade socio-técnica fundamental no desenvolvimento de software. O estudo analisa 685 projetos open-source no GitHub que adotaram o Travis-CI, a ferramenta de CI mais popular na plataforma. Os resultados mostram que, após a introdução da CI, há uma redução significativa na quantidade de comentários nas revisões de código, indicando que a automação elimina parte das discussões antes necessárias. Entretanto, essa redução na comunicação não está associada a uma diminuição no número de atualizações dos pull requests, sugerindo que os desenvolvedores continuam fazendo ajustes sem precisar de tantas interações. O conceito de "CI como um ajudante silencioso" emerge, onde a automação absorve parte das responsabilidades dos revisores humanos. A análise estatística do estudo utilizou Regression Discontinuity Design (RDD) e evidenciou que, em média, a CI reduz até um comentário por pull request, otimizando o tempo dos revisores sem comprometer a qualidade do código.

2. Fichamento Bibliográfico
Continuous Integration (CI) é um processo de automação que executa testes e builds frequentemente para facilitar a integração de código e melhorar a qualidade do software. (página 423)
Code review é uma prática essencial para garantir qualidade, sendo impactada pela CI devido à automação de verificações básicas, reduzindo a necessidade de discussão. (página 424)
Travis-CI foi escolhido como foco da pesquisa por ser a ferramenta de CI mais utilizada em projetos GitHub open-source. (página 425)
Regression Discontinuity Design (RDD) foi utilizado para analisar mudanças no volume de comentários antes e depois da adoção da CI. (página 427)
O conceito de "CI como um ajudante silencioso" refere-se à forma como a CI reduz a carga dos revisores humanos, sem impactar negativamente a qualidade do código. (página 431)

3. Fichamento de Citações
"Indeed, we find that on average the amount of discussion during pull request reviews decreases over time after the introduction of CI." (página 423)
"On average CI saves up to one review comment per pull request, giving rise to the idea of continuous integration as a silent helper." (página 424)
"The decrease in the amount of discussion, however, cannot be explained by a decrease in the number of updates of the pull requests." (página 425)
"Maintainers need to report and discuss these topics less frequently, which could indicate a reduction in the amount of communication needed during pull request reviews." (página 426)
"By modeling code review data around the introduction of Continuous Integration we find that the number of comments per code review decreases after the adoption of Continuous Integration, while the number of changes made during a code review remains constant." (página 432)
