<h2>Contando a história</h2>
A fictícia imobiliária InsightPlaces, situada na cidade do Rio de Janeiro, está enfrentando dificuldades para alugar e vender imóveis. Em uma pesquisa de como empresas semelhantes operam no mercado, a InsightPlaces percebeu que esse problema pode estar relacionado aos valores dos imóveis e às recomendações que faz.

Este é um projeto feito para analisar os dados de valores de imóveis no Rio de Janeiro através do banco de dados, criar uma previsão de preço de acordo com as características do imóvel e criar um recomendador.

<b>Status: Projeto concluído.<b/> 

<h2>Etapas realizadas</h2>
<h3>Processamento do conjunto de dados com PySpark</h3>
Utilizando o Pyspark, ideal para trabalhar com grandes volumes de dados, fiz os tratamentos no banco de dado, fiz a criação e avaliação dos modelos de machine learning com otimização por cross validation (Regressão Linear, Decision Tree e Random Forest) e rodei uma previsão baseada no modelo mais performático.


<h3>Criação do modelo de recomendação</h3>
Criei um modelo de recomendação de imóveis de acordo com os clusters determinados pela técnica KMeans. Para isso, fiz a redução da dimensionalidade, vetorizei e padronizei os dados e fiz o cálculo da distância euclidiana, além de criar um pipeline. A função recomendadora permite que o usuário escolha o imóvel de referência e diga quantos outros ele deseja receber como recomendação.
  
Esse projeto fez parte do Challenge de Dados da Alura.
