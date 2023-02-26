# Bank-Marketing
<h2>1. Objetivo do projeto</h2>

<p> Encontrar o conjunto de características que mais favoreçam o empréstimo da pessoa ao banco. Fazendo com que a empresa economize tempo e melhore seus resultados</p>
<h2>2. Sobre o dataset</h2>

<p> O dataset do projeto foi retirado de https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing</p>
<p> Originalmente possuia 21 colunas, sendo elas:</p>
<li>age</li>
<li>job</li>
<li>marital</li>
<li>education</li>	
<li>default</li>	
<li>housing</li>	
<li>loan</li>
<li>contact</li>
<li>month	day_of_week</li>
<li>campaign</li>	
<li>pdays</li>	
<li>previous</li>	
<li>poutcome</li>	
<li>emp.var.rate</li>	
<li>cons.price.idx</li>
<li>cons.conf.idx</li>	
<li>euribor3m</li>	
<li>nr.employedy</li>
  <p> A descrição de cada uma delas se encontra no arquivo bank-additional-names.txt da pasta data.</p>
  <p> Foi eliminada, durante o tratamento dos dados, a coluna duration, que indicava a duração da ligação, pois, como o objetivo do projeto era prever quais clientes estariam mais aptos a fazer o empréstimo e qual não estariam, não faria sentido utilizar essa coluna porque o resultado (fez empréstimo ou não) já seria conhecido ao terminar a ligação.</p>
 <h2>3. Modelos</h2>

<p>Foram testados os modelos Random Forest e Árvore de Decisão. Ambos apresentaram bons desempenhos, 89.46% e 89.91% de acurácia respectivamente. Foi escolhido o modelo de árvore de decisão pois com esse é possível ver as decisões tomadas pelo algoritmo e tirar conclusões.</p>
  
<h2>4. Resultados</h2>
<h3>O que deve ser feito?</h3>
<li>A empresa pode diminuir o número de empregados que fazem as ligações para um valor abaixo de 5088 sem prejuízo, porém com cuidado para não dimnuir muito.</li>
<li>A empresa deve repetir a ligação para a mesma pessoa em um período menor que 16 dias.</li>
<li>A empresa deve fazer um número menor de ligações na segunda-feira e priorizar os demais dias da semana</li>
<li>A empresa deve aumentar o número de ligações no mês de outubro.</li>
<li>A empresa deve priorizar as ligações quando a taxa euribor trimestral for menor que 1.368</li>
<li>A empresa deve priorizar pessoas com outros formas de contato que não são telefônicas.</li>
![](https://github.com/Leonardo010/Bank-Marketing/blob/main/arvore%20de%20decis%C3%A3o/arvore.png#vitrinedev)
