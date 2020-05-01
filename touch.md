# Análise de Séries Temporais

## Métodos
* **Naive:** o melhor metodo para series que sao apenas ruido branco.
> naive()

* **Moving Averages**

* **Exponential Smoothing:** funciona melhor com series sem tendencias. 
> ses()
* **Holt Method:** não possui sazonalidade.
> hw()

* **Holt Winther's method**
    * **Additive:** para series com aumento na tendencia mas nao na amplitude.
    * **Multiplicative:** para series com aumento de amplitude.

* **Séries de Fourier**

* **Space State Models (ETS)**
> ets()

* **Modelo Autoregressivo (AR):** Regressao linear multipla utilizando valores anteriores até o número de Lag definido

* **Modelo de medias moveis:** Regressoes dos erros anteriores da serie em um processo interativo, trabalha melhor em series de white noise.

* **ARMA:** juncao do modelo regressivo e de médias móveis

* **ARIMA:** juncao do modelo ARMA com uma integracao da serie de dados.
> arima()
> auto.arima()

## Erros

* **Akaike's Information Criterion (AIC):** só pode comparar modelos de uma mesma classe

## Transformacoes
* **BoxCox**: Mistura envolvendo log
* **Raiz Quadrada**
* **Inversao 1/x**

