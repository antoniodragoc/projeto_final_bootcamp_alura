# Projeto Final Bootcamp Data Science Aplicada 2

<h2 align='center'>
  Antonio Drago Caetano
</h2>

<p align='center'>  
  
  <a href="https://www.linkedin.com/in/antoniodragoc/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>  
  <a href="https://www.kaggle.com/antoniodragoc/">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" />
  </a>  
</p>

#
## Introdução

  O Sistema Unificado e Descentralizado de Saúde (SUDS), que mais tarde se tornou o SUS que conhecemos hoje, foi criado pela Constituição Federal de 1988, com o objetivo de organizar e centralizar os serviços de saúde dos estados e municípios no Ministério da Saúde. As primeiras grandes contribuições desenvolvidas pelo Sistema foi na década de 1990 com as campanhas de vacinação em massa, proporcionando a unificação dos departamentos de saúde e melhorando a logística da rede de assistência. Com o SUS, a saúde pública no país tem como base o tripé da Descentralização, da Integralidade, da Assistencia e Participação da comunidade, buscando oferecer um serviço de qualidade para toda a população independente do local em que o cidadão esteja.

  No ano de 2020, em razão da pandemia de COVID-19, o sistema de saúde do país passou por grandes dificuldades, o um dos principais foi a alta demanda de leitos de UTI que assim como em paises vários paises do mundo não estava preparado para acomodar tantos pacientes graves ao mesmo tempo. Causando um colapso no sistema de saúde, pois por conta da explosão da demanda por leitos, o sistema não foi capaz de atender todos os pacientes tendo que escolher quem iria priorizar pela chance de sobrevivência do paciente.

## Objetivo e Metodologia

  Utilizando Inteligência Artificial por meio do Aprendizado de Maquina, ou Machine Learning (ML) como também é conhecido, iremos ensinar o computador a prever se o paciente necessitará ser encaminhado para a UTI por meio de uma série de exemplos de casos e por meio de ferramentas matemáticas de agrupamento e probabilidade o algorítimo será capaz de calcular a probabilidade que um paciente tem de precisar de ir para a UTI.
  
  Para isso será utilizado como base os dados disponibilizados pelo hospital Sírio-Libanês na comunidade de data science Kaggle ([link](https://www.kaggle.com/S%C3%ADrio-Libanes/covid19)). Para a escolha do melhor modelo de previsão será utilizada a técnica de validação cruzada, ou Cross-Validation, que consistem em comparar várias possibilidades de parâmetros nos modelos de previsão.
  
## Conslusões 
  
  Após a otimização dos três melhores modelos testados (Random Forest, Logistic Regression e XGB Classifier) chegamos a conlusão que o desempenho do XBG foi superior, apresentando uma acurácia de 89,55% o que é bem supreendente tendo em vista que o conjunto de dados em questão é bem pequeno.
  Além do mais, o resultado se mostrou bem robusto já que nos testes de performance do classification_report apresentou resultados bem interessantes com a acurácia em torno de 80% em todos os cenários.
