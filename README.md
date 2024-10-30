<h1 align="center">🧠 Previsão de Inadimplência na Concessão de Crédito</h1>
<br>

![Banner](https://github-dbrazl.s3.us-east-1.amazonaws.com/ai-credit-default/banner.svg?)

<p align="center">
  Trabalho de Conclusão de Curso apresentado para obtenção do título de especialista em Data Science e Analytics – Universidade de São Paulo (USP) – 2024.
</p>

<br>
<p align="center">
  <img src="https://img.shields.io/badge/autor-@dbrazl-blue?style=flat" alt="Autor: @dbrazl">
</p>
<br>

## 📝 Resumo

<p align="justify">
  Este estudo tem como objetivo identificar os melhores métodos de aprendizado de máquina para prever inadimplência na concessão de crédito. Utilizando dados do repositório público “Statlog (German Credit Data)”, foram aplicados diversos modelos de machine learning, incluindo Regressão Logística, K Nearest Neighbors, Support Vector Machine, Gaussian Naive Bayes, Árvore de Decisão, Random Forest, XGBoost, Perceptron, Rede Neural Rasa e Rede Neural Profunda. O processo envolveu a transformação de dados categóricos, balanceamento da base de dados, normalização das variáveis e aplicação de técnicas de oversampling. A principal métrica utilizada foi a revocação, complementada pela avaliação das curvas ROC e PRC. O modelo Gaussian Naive Bayes destacou-se pela sua capacidade de identificar 81% dos inadimplentes, embora a Regressão Logística também tenha mostrado um bom desempenho. O estudo concluiu que a identificação precisa de inadimplência pode auxiliar instituições financeiras na mitigação de riscos de crédito. A metodologia e os resultados podem ser adaptados para outras instituições financeiras, ressaltando a relevância do trabalho.
</p>

## 📚 Publicação científica

<p align="justify">
  O trabalho estará disponível para acesso em breve! Não deixe de acompanhar as novidades!
</p>

## 🛠 Tecnologias

<p align="justify">
  As tecnologias utilizadas nesse projeto foram:
</p>

![Python](https://img.shields.io/badge/Python-333333?style=flat&logo=python&logoColor=green)
![Pandas](https://img.shields.io/badge/Pandas-333333?style=flat&logo=pandas&logoColor=blue)
![Numpy](https://img.shields.io/badge/Numpy-333333?style=flat&logo=numpy&logoColor=lightblue)
![Scikit-learn](https://img.shields.io/badge/-Scikit%2d-learn-333333?style=flat&logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-333333?style=flat&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxODAiIGhlaWdodD0iMTgwIiBzdHJva2U9ImdyYXkiPgo8ZyBzdHJva2Utd2lkdGg9IjIiIGZpbGw9IiNGRkYiPgo8Y2lyY2xlIGN4PSI5MCIgY3k9IjkwIiByPSI4OCIvPgo8Y2lyY2xlIGN4PSI5MCIgY3k9IjkwIiByPSI2NiIvPgo8Y2lyY2xlIGN4PSI5MCIgY3k9IjkwIiByPSI0NCIvPgo8Y2lyY2xlIGN4PSI5MCIgY3k9IjkwIiByPSIyMiIvPgo8cGF0aCBkPSJtOTAsMnYxNzZtNjItMjYtMTI0LTEyNG0xMjQsMC0xMjQsMTI0bTE1MC02MkgyIi8+CjwvZz48ZyBvcGFjaXR5PSIuOCI+CjxwYXRoIGZpbGw9IiM0NEMiIGQ9Im05MCw5MGgxOGExOCwxOCAwIDAsMCAwLTV6Ii8+CjxwYXRoIGZpbGw9IiNCQzMiIGQ9Im05MCw5MCAzNC00M2E1NSw1NSAwIDAsMC0xNS04eiIvPgo8cGF0aCBmaWxsPSIjRDkzIiBkPSJtOTAsOTAtMTYtNzJhNzQsNzQgMCAwLDAtMzEsMTV6Ii8+CjxwYXRoIGZpbGw9IiNEQjMiIGQ9Im05MCw5MC01OC0yOGE2NSw2NSAwIDAsMC01LDM5eiIvPgo8cGF0aCBmaWxsPSIjM0JCIiBkPSJtOTAsOTAtMzMsMTZhMzcsMzcgMCAwLDAgMiw1eiIvPgo8cGF0aCBmaWxsPSIjM0M5IiBkPSJtOTAsOTAtMTAsNDVhNDYsNDYgMCAwLDAgMTgsMHoiLz4KPHBhdGggZmlsbD0iI0Q3MyIgZD0ibTkwLDkwIDQ2LDU4YTc0LDc0IDAgMCwwIDEyLTEyeiIvPgo8L2c+PC9zdmc+)
![Seaborn](https://img.shields.io/badge/-Seaborn-333333?style=flat&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9Im5vIj8+CjwhLS0gVXBsb2FkZWQgdG86IFNWRyBSZXBvLCB3d3cuc3ZncmVwby5jb20sIEdlbmVyYXRvcjogU1ZHIFJlcG8gTWl4ZXIgVG9vbHMgLS0+Cgo8c3ZnCiAgIGZpbGw9IiMwMDAwMDAiCiAgIHdpZHRoPSI4MDBweCIKICAgaGVpZ2h0PSI4MDBweCIKICAgdmlld0JveD0iLTAuMiAwIDMyLjkzOSAzMi45MzkiCiAgIHZlcnNpb249IjEuMSIKICAgaWQ9InN2ZzIiCiAgIHNvZGlwb2RpOmRvY25hbWU9ImNoYXJ0LWN1cnZlZGNoYXJ0LWdyYXBoLWxpbmUuc3ZnIgogICBpbmtzY2FwZTp2ZXJzaW9uPSIxLjMuMiAoMToxLjMuMisyMDIzMTEyNTIxNTArMDkxZTIwZWYwZikiCiAgIHhtbG5zOmlua3NjYXBlPSJodHRwOi8vd3d3Lmlua3NjYXBlLm9yZy9uYW1lc3BhY2VzL2lua3NjYXBlIgogICB4bWxuczpzb2RpcG9kaT0iaHR0cDovL3NvZGlwb2RpLnNvdXJjZWZvcmdlLm5ldC9EVEQvc29kaXBvZGktMC5kdGQiCiAgIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIKICAgeG1sbnM6c3ZnPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CiAgPGRlZnMKICAgICBpZD0iZGVmczIiIC8+CiAgPHNvZGlwb2RpOm5hbWVkdmlldwogICAgIGlkPSJuYW1lZHZpZXcyIgogICAgIHBhZ2Vjb2xvcj0iI2ZmZmZmZiIKICAgICBib3JkZXJjb2xvcj0iIzAwMDAwMCIKICAgICBib3JkZXJvcGFjaXR5PSIwLjI1IgogICAgIGlua3NjYXBlOnNob3dwYWdlc2hhZG93PSIyIgogICAgIGlua3NjYXBlOnBhZ2VvcGFjaXR5PSIwLjAiCiAgICAgaW5rc2NhcGU6cGFnZWNoZWNrZXJib2FyZD0iMCIKICAgICBpbmtzY2FwZTpkZXNrY29sb3I9IiNkMWQxZDEiCiAgICAgaW5rc2NhcGU6em9vbT0iMC45MjYyNSIKICAgICBpbmtzY2FwZTpjeD0iMzk5LjQ2MDE5IgogICAgIGlua3NjYXBlOmN5PSI0MDAiCiAgICAgaW5rc2NhcGU6d2luZG93LXdpZHRoPSIyNTYwIgogICAgIGlua3NjYXBlOndpbmRvdy1oZWlnaHQ9Ijk0MSIKICAgICBpbmtzY2FwZTp3aW5kb3cteD0iMCIKICAgICBpbmtzY2FwZTp3aW5kb3cteT0iMjciCiAgICAgaW5rc2NhcGU6d2luZG93LW1heGltaXplZD0iMSIKICAgICBpbmtzY2FwZTpjdXJyZW50LWxheWVyPSJzdmcyIiAvPgogIDxnCiAgICAgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTIyNS4xNSAtMzg1LjA1NykiCiAgICAgaWQ9ImcyIgogICAgIHN0eWxlPSJmaWxsOiM1NTk5ZmYiPgogICAgPHBhdGgKICAgICAgIGQ9Ik0yNTYuNjg5LDQxOEgyMjUuMTVWMzg2LjA1N2ExLDEsMCwwLDEsMiwwVjQxNmgyOS41MzlhMSwxLDAsMCwxLDAsMloiCiAgICAgICBpZD0icGF0aDEiCiAgICAgICBzdHlsZT0iZmlsbDojNTU5OWZmIiAvPgogICAgPHBhdGgKICAgICAgIGQ9Ik0yMzAuMTcxLDQwOS45OTVhMSwxLDAsMCwxLS42OC0xLjczM2w1LjAyNC00LjY2OWE0LjcyNSw0LjcyNSwwLDAsMSw2LjQ0MS4wMjNsMS4xNTIsMS4wODdhMy42MjgsMy42MjgsMCwwLDAsNS40LS40NjhsNy40LTkuOTEyYTEsMSwwLDAsMSwxLjYsMS4ybC03LjQsOS45MTJhNS42MjgsNS42MjgsMCwwLDEtOC4zNzMuNzI2bC0xLjE1Mi0xLjA4N2EyLjcxNywyLjcxNywwLDAsMC0zLjcwNi0uMDE0bC01LjAyNSw0LjY3QTEsMSwwLDAsMSwyMzAuMTcxLDQwOS45OTVaIgogICAgICAgaWQ9InBhdGgyIgogICAgICAgc3R5bGU9ImZpbGw6IzU1OTlmZiIgLz4KICA8L2c+Cjwvc3ZnPgo=)
![Tensorflow](https://img.shields.io/badge/-Tensorflow-333333?style=flat&logo=tensorflow)
![Keras](https://img.shields.io/badge/-Keras-333333?style=flat&logo=keras&logoColor=red)
![MLFlow](https://img.shields.io/badge/-MLFlow-333333?style=flat&logo=mlflow)

## 💡 Próximas publicações

<p align="justify">
  Nos próximos trabalhos será abordado a aplicação dos modelos explorados  em base de dados maiores para saber como eles performam em aplicações com centenas de milhares ou milhões de registros. Espera-se que o modelo de Rede Neural Profunda, se sobressaia nesse cenário, o qual também receberá mais liberdade em sua arquitetura para melhor se ajustar aos dados fornecidos. Adicionalmente, será abordado o método SHAP (SHapley Additive exPlanations) para análise de importância de características na predição dos modelos, que será comparado com o método Permutation Feature Importance usado neste trabalho.
</p>

## 📬 Contato

<p align="justify">
  Se você tiver dúvidas ou sugestões, pode me encontrar em <a href="mailto:daniel.braz@vyox.io">daniel.braz@vyox.io</a> ou através do <a href="https://www.linkedin.com/in/dbrazl/">LinkedIn</a>.
</p>
