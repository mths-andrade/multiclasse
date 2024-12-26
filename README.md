# Classificação multiclasse

Vamos abordar a classificação multiclasse, onde lidaremos com múltiplas classes para fazer previsões.

Vamos desenvolver em um projeto envolvendo informações de estudantes universitários. Nossa meta é compreender e classificar os estudantes propensos a abandonar ou desistir do curso. Tudo isso será feito num notebook do Google Colab.

Banco de dados:  [Dados dos estudantes](https://github.com/mths-andrade/multiclasse/blob/e160c0198ebc1ebce576400b9f4796ff98e84a10/dados_estudantes.csv)

Vamos trabalhar com as bibliotecas Pandas, Matplotlib, Seaborn, Plotly, Scikit-Learn e Imbalanced-Learn.

Possuímos informações demográficas das pessoas estudantes, abrangendo seu estado civil, uma categoria que sinaliza a migração (indicando se houve uma mudança de cidade ou local para ingressar na faculdade), dados sobre o sexo biológico e a idade no momento da matrícula.

Além disso, dispomos de uma variável que identifica se o estudante é estrangeiro, uma vez que estamos lidando com uma instituição de ensino em Portugal, onde a presença de estudantes internacionais é uma possibilidade.

Também temos dados socioeconômicos, como se a pessoa possui "necessidades educacionais especiais", se é uma pessoa devedora - pois, sendo uma instituição particular, as mensalidades precisam ser pagas regularmente - e informações sobre a adimplência da taxa de matrícula e se a pessoa é bolsista.

Também temos acesso aos dados macroeconômicos, incluindo a taxa de desemprego, a taxa de inflação e o PIB do período em questão. Posteriormente, temos informações sobre o momento da matrícula: o curso escolhido, o período (diurno ou noturno), e se a pessoa tinha alguma qualificação prévia - é possível que encontre pessoas que já fizeram outra faculdade ou até pós-graduação, mas querem cursar um segundo curso.

Possuímos informações referentes aos cursos que os estudantes efetivamente frequentaram durante o primeiro e o segundo semestres. Isso compreende dados relacionados às disciplinas do primeiro semestre, tais como a quantidade creditadas, matrículadas, o número de avaliações que a pessoa estudante realizou, o total de disciplinas aprovadas, bem como as respectivas notas e outros pormenores semelhantes. O mesmo procedimento se aplica ao segundo semestre.
