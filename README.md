## Título: Análise de dados de criptomoedas para predição do seu valor no mercado

# Descrição

	Criptomoedas são moedas digitais que não existem fisicamente e não são emitidas por nenhum governo. Elas têm três principais funções: 1) servir como meio de troca, facilitando as transações comerciais; 2) reserva de valor, para a preservação do poder de compra no futuro; 3) unidade de conta, quando os produtos são precificados e o cálculo econômico é realizado em função dela (Infomoney, 2021).
	Uma desvantagem importante é que o preço das criptomoedas apresenta grande volatilidade (Infomoney, 2021). Seu preço varia conforme oferta e demanda. Além disso, elas ainda possuem baixo grau de aceitação nos estabelecimentos, por enquanto. Existe um risco de que os usuários apaguem ou percam suas moedas além de ser necessário se proteger da ação de hackers (Infomoney, 2021).
	Algoritmos de Machine Learning têm sido amplamente utilizados no mercado financeiro com o intuito de prever preço de ações (listei referencias para ler depois no tópico). Os modelos mais utilizados para essa tarefa são métodos ensemble LSTMs e redes neurais recorrentes.

# Problema a ser analisado: 

	O problema a ser analisado aqui será prever o preço de criptomoedas baseado em dados disponíveis de mercado. Além disso, notícias e interações nas redes sociais tem impacto no preço e, portanto, serão adicionados a análise.
Inicialmente o modelo será treinado com dados de valores de Bitcoin (BTC) por ser a mais famosa e depois de ter um modelo e estratégia clara funcionando, testar com outras criptomoedas. Outras criptomoedas: Bitcoin Cash (nova versão do Bitcoin), Ethereum (ETH), Tether (USDT), Ripple (XRP), Litecoin (LTC) etc.

# Dicionário de dados:

	Os dados utilizados serão preços das ações num intervalo de tempo.
	Tweets de páginas e assuntos que possam ter impacto no modelo.
	Podem ser incorporados notícias e outras fontes futuramente.

# Objetivos:

•	Modelo de Machine Learning para preços das açoes
o	Conexão do python com o site que possui os valores das ações através da API ou pacote binance.
o	Revisão de literatura para ver ferramentas que já estão sendo usadas
o	Treinamento do modelo-base – provavelmente uma rede neural
o	Avaliação do modelo e ajustes
•	Análise de Sentimento dos Tweets para incorporar ao modelo
o	Coleta dos tweets através da API
o	Análise de sentimento e rankeamento dos tweets relacionados ao tema
•	Incorporar análise de sentimentos ao modelo de predição das ações
o	Revisão de literatura sobre o tema e como fazer
•	Relatório e deploy

# Datas :

1 etapa : 22/08 - etl, decomposição série temporal, verificar estacionaridade
2 etapa : 19/09 - forecasting : ARIMA, SARIMA, ARMA, Prophet, Kats, LSTM
3 etapa : 26/09 - relatorio final 
