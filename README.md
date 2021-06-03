# MRBIT - Cotação de criptomoedas

> **pontos norteadores para construção da aplicação:**

- construir um painel de preços;
- conectar o painel via API com um servidor de cotação;
- mostrar a última cotação em USD (dólar) das criptomoedas: **Bitcoin, Ethereum e Litecoin;**
- informar ao painel de preços o valor atual de cada ativo;
- as moedas estão representadas pelos seus símbolos: **BTCUSD, ETHUSD, LTCUSD**;
- atualizar o sistema a cada 100 segundos;



### API

> a atualização dos valores é realizada da API:

- [CoinMarketCap](https://coinmarketcap.com/api/documentation/v1/)

> o controle do temporizador é realizado através da biblioteca: 

- `time`.

> a exibição do horário atual é realizado através da biblioteca:

- `datetime`

