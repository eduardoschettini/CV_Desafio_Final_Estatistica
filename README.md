# CV_Desafio_Final_Estatistica
Projeto Final do CAIXAVerso Estatística I

TRABALHO FINAL DE ESTATÍSTICA I 
PROFESSOR THIAGO TAVARES MAGALHÃES 
— 
● Entrega até o dia 31 de março, às 23:59:59, pelo LMS (seção projetos) 
● Grupos de 1 a 3 pessoas. 
● Se você estiver fazendo o trabalho em grupo, por favor, cada membro do grupo envie uma cópia do trabalho no LMS. 
● Entrega via link do github ou via upload qualquer arquivo facilmente legível (imagem, pdf, .py, .pynb) pela seção de projetos do LMS. 
— 
Crie uma conta no site kaggle.com, faça o download do DataSet Body Fat Prediction, disponível gratuitamente aqui e leia-o como um Python Pandas Dataframe. Este dataset é utilizado para testar a capacidade de diferentes heurísticas - como modelos de Inteligência Computacional, por exemplo - quanto às suas habilidades em traduzir uma série de dados corporais em uma porcentagem de gordura corporal. Mas vamos utilizá-lo para que você possa demonstrar os seus conhecimentos em estatística 
-
1- Utilizando seus conhecimentos em Estatística Descritiva, forneça algumas análises sobre as colunas que julgar mais relevantes do dataset.  
a) Para as colunas que você escolher, mostre-me as métricas de posição e de dispersão que julgar interessantes.  
b) Faça um pré-julgamento a respeito das colunas deste dataset tentando encontrar um par de colunas que, pela lógica, deve ser altamente correlacionado e outro par de colunas que, pela lógica, deve ser fracamente correlacionado. Depois utilize as métricas de correlação que você aprendeu para pôr à prova dessas suas opiniões, isto é, para descobrir se matemática confirma suas crenças iniciais ou não. 
c) Escolha pelo menos uma coluna que siga a distribuição normal, plote um boxplot e explique como você fez para concluir que esta coluna segue uma distribuição normal. 

2- Considerando o mesmo dataset e tomando-o como espaço amostral, responda:  (ps.: fique à vontade para usar o Python para facilitar a sua vida aqui): 
a) Qual é a probabilidade de uma pessoa selecionada ao acaso ter uma idade (coluna Age) superior a 40 anos? 
b) Qual é a probabilidade de uma pessoa selecionada ao acaso ter um percentual de gordura corporal (coluna BodyFat) superior a 20%? 
c) Qual é a probabilidade de uma pessoa selecionada ao acaso ter um percentual de gordura corporal (coluna BodyFat) superior a 20% e ao mesmo tempo ter uma idade (coluna Age) superior a 40 anos? 
d) Qual é a probabilidade de uma pessoa selecionada ao acaso ter um percentual de gordura corporal (coluna BodyFat) superior a 20% se eu já souber de antemão que esta pessoa tem uma idade superior a 40 anos? 

3- Durante o módulo, nós definimos algumas distribuições de probabilidade, cada uma com uma função de probabilidade. 
a) Escolha uma delas que não seja uma distribuição normal, e explique (talvez com algum exemplo) que tipos de evento esta distribuição descreve. 
b) Explique a utilidade prática das funções de probabilidade. Quero dizer: para quê elas servem? De que modo elas nos ajudam? 
c) Escolha uma das colunas do nosso dataset que sejam contínuas e que sigam uma distribuição normal, e calcule a probabilidade de uma pessoa escolhida ao acaso ter um valor > x para esta coluna (por exemplo, probabilidade de neck ser maior que 45). Mas, atenção: faça isso usando z-scores, através da função st.norm.cdf, do pacote Python scipy.stats. 

4- Escolha uma coluna de valores contínuos A que seja do seu interesse. Depois disso, filtre os registros da sua tabela usando uma segunda coluna B. E, por fim, valendo-se dos seus conhecimentos sobre p-valor, diga se a média de A antes da filtragem é de fato significativamente diferente da média dos valores de A pós filtragem, com um nível de confiança de 95%. Por exemplo: a coluna BodyFat tem uma determinada média geral. Se filtrarmos o nosso dataset para que ele inclua apenas registros com circunferência abdominal (coluna Abdomen) >= 85, certamente a média da coluna BodyFat mudará. Mas, podemos afirmar, com 95% de confiança estatística, que essa média pós-filtragem é, de fato, diferente da média original? 

5- Pesquisas eleitorais envolvem, quase sempre, um imenso problema estatístico: a menos que você esteja interessado nas eleições municipais de uma cidade com 5 mil habitantes, você nunca terá o tempo e o orçamento necessários para entrevistar 100% dos potenciais eleitores. Imagine só, como poderíamos entrevistar mais de 100 milhões de pessoas para tentar prever com exatidão o resultado das eleições presidenciais do Brasil? Utilizando os seus conhecimentos sobre amostragem estatística, descreva como você faria para selecionar, por exemplo, 20 mil pessoas para serem entrevistadas, com o objetivo de produzir uma amostra que seja minimamente suficiente para predizer as intenções de voto de um grupo tão maior de pessoas quanto 
no caso das eleições presidenciais brasileiras. Explique, também, por que você tomou essa decisão e diga qual é o nome do tipo de amostragem estatística que você utilizou. 
