# Smarkio  –  Teste  Prático  Ciência  de  Dados   


<b>Descrição do Dataset</b>

1. Primeira  aba  -  Análise_ML:   <br>
a pred_class  -  A  classe  que  foi  identificada  pelo  modelo; <br>
b probabilidade  -  A  probabilidade  da  classe  que  o  modelo  identificou;  <br> 
c. status  -  status  da  classificação  de  acordo  com  um  especialista  (approved); <br>
d.   true_class  -  A  classe  verdadeira  (se  nula,  assumir  o  pred_class); Obs:  Se  pred_class  é  igual  a  true_class,  temos  que  o  modelo  acertou. <br>

2. Segunda  aba  -  NLP:   <br>
a. letra  -  trecho  de  música; <br>
b. artista  -  cantora  referente  a  letra. <br>

<b>Etapas executadas no projeto:</b>

1. Análise exploratória dos dados utilizando estatística descritiva e inferencial,
considerando uma, duas e/ou mais variáveis;
2. Calcule o desempenho do modelo de classificação utilizando pelo menos três
métricas;
3. Crie um classificador que tenha como output se os dados com status igual a
revision estão corretos ou não (Sugestão : Técnica de cross-validation K-fold);
4. Compare três métricas de avaliação aplicadas ao modelo e descreva sobre a
diferença;
5. Crie um classificador, a partir da segunda aba - NLP do arquivo de dados, que
permita identificar qual trecho de música corresponde às respectivas artistas listadas
(Sugestão: Naive Bayes Classifier).

<b>Divisão do projeto:</b>
O projeto foi divididos em duas partes. 
As etapas de 1 à 4 estão no arquivo: smarkio_analise_ml.ipynb
e a etapa 5 está no arquivo: smarkio_analise_nlp.ipynb

<b>Execução do projeto e linguagem:</b>
Projeto feito em Python no Google Colab.
O projeto pode ser executado no google colab. O dataset deve ser incluído no mesmo diretório dos projeto. Talvez seja necessário dar acesso ao seu drive no google colab  através do menu esquerdo



