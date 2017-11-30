# Should You Be Tempted to Invest in Bitcoin?

## Project Statement:
Bitcoin, a worldwide cryptocurrency invented by an unknown person with alias Satoshi Nakamoto. It is the first decentralized digital currency, as the system works without a central repository or single administrator. The coins don’t exist in a tangible form but are made by computers and stored in a digital wallet or on the cloud but there is a finite number of bitcoin that can be supplied i.e. 21million and there are currently 16million in circulation.<br />

Why this topic? Bitcoin price soars above $11000 to a new record high value! This is the headline all news channels were telecasting from the past few days. And the question in everyone's mind is **Will it survive or is it just a bubble?** The value of bitcoin is tied purely to the concept of supply and demand, as the people are getting more aware about it and buying it, the prices are increasing. As we compare to other established currencies and commodities like USD/EURO dollar or gold prices, Bitcoin has been very volatile and also the market for Bitcoin is not regulated as per the laws. Still bitcoin prices are rising wildly, you might be wondering how wild it can be - Seven years ago, two pizzas could be bought for 10,000 bitcoins, which today would be worth $100 million.<br />
Demand is increasing, alongside criticism, if you want to get involved in the cryptocurrency then awareness is the key. Therefore, we will be doing a thorough analysis about the benefits and risks involved for a potential investor willing to diversify his/her portfolio of investment and then conclude "Would it be the best use of an investor's money?"

## Audience:
Our targeted audience is a potential investor interested in diversifying his/her existing portfolio of investments. In order to maximize expected return and minimize foreseeable risk inherited in the current industries of his/her investments, the ultimate objective of the mentioned investor is to invest in a industry different than the existing ones, and we are analyzing the positive and negative aspects of investing in crytocurrencies, specifically Bitcoin and "Will it a profitable avenue for the audience to consider investing in?"

### Audience Need:
The Audience is interested in taking profits from the likely arbitrage opportunity embedded in the cryptocurrencies. As we see in the patterns and trends of cryptocurrencies historical prices, there are short-term spikes and upticks in the prices which pose a decent profit making opportunity for prospective investors. Therefore, the immediate of the audience is to diversify their investment portfolio and to reap the benefits of earning sizable profits from investing in a digital currency like Bitcoin.

### Audience Want:
Our presumed audience for this analysis of Bitcoin investment is a prospective investor intending to diversify his/her investments. That particular investor wants to ascertain the positive aspects of investing in cryptocurrencies. The chances of earning a higher profit margin and return on investment as compared to other traditional investments are also part of the wants of our audience. 

### Audience Fears:
Being virtual and digital currencies, Cryptocurrencies are not backed by any government or a regulatory agency and the operations are decentralized as compared to the traditional centralized banking system and the financial markets. Therefore, a general perception and an expected fear of our audience would be the safety, reliability and foreseeability of their investment in cryptocurrencies. Since the legal status of cryptocurrencies still varies from country to country as some of them have yet not legalized its trading, so another audience fear may be the legality and sustainability of investing in the digital currencies.

## Project Progression:
### 1. Data Analysis:
![image0](https://user-images.githubusercontent.com/32077698/33408839-65357342-d52d-11e7-8a60-eb191d2f43b9.png)

To start with the data analysis, we collected data from 2013 to 2017 about the closing stock prices of Bitcoin and put that into tableau to get an overall picture of trends shown by Bitcoin over the time. The visualization showed, there was an increase in the price of bitcoin in the initial years because people started to get some insight about the cryptocurrency world and started buying and keeping it as an asset but then due to speculations in people’s mind that it is unstable and not legal and can crash anytime, made the prices to go down. After this, 2017 started with a bang as Bitcoin shot through the $1000 mark with no signs of slowing down and it has reached a record breaking mark of above $11000 today.<br />
![image1](https://user-images.githubusercontent.com/32077698/33408840-654e6eec-d52d-11e7-8470-b4f150119067.png)

We collected data about the number of bitcoins in circulation. Above graph shows the increasing number of bitcoins over the years in the market. It has been forecasted that only 21m bitcoin can be generated and 16m bitcoins are already in circulation, so bitcoins are finite in number. But this can also imply that as the bitcoins become scarce, the prices are going to rise, the simple demand and supply mechanism. Higher the demand, more are the prices. <br />
The reason we focussed on Bitcoin out of all the currencies, is because Bitcoin is the first one to be in the market and lot of people still are not aware of it. So, it would be interesting to see the reason behind its soaring prices and whether it is a safe currency to invest, or should you keep it as a long term asset or is it just a bubble that is soon going to crash?

### 2. Data Wrangling:
To reach a decision, we analyzed some key metrics about the market trends shown by the Bitcoin and other currencies. We have multiple data sets web scraped and downloaded from websites like kaggle.com, quandl.com, coindesk.com etc. We collected datasets about open, high, low, close prices of Bitcoin, Ethereum and Litecoin i.e. all the cryptocurrencies, Nasdaq and S&P Index for Bitcoin, Bitcoin’s comparison to USD/EURO currencies. Also, data about number of transactions per day for Bitcoin and Ethereum(the second best cryptocurrency in the market) to see if there are some exceptions. As cryptocurrencies are also being used as Initial coin offerings by some companies, we collected data about Bitcoin’s and Ethereum’s Return on Investment since ICO. <br />
The datasets did not require much cleaning, we renamed some columns and integrated the datasets as per the common attributes and got 3 different datasets in the end. Data sources are mentioned below:<br />

Data about Open, High, Low, Close prices of cryptocurrencies(Bitcoin, Litecoin, Monero, Ethereum):<br />
https://www.kaggle.com/team-ai/bitcoin-price-prediction/data, https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory/data<br />
Data about S&P 500 and Nasdaq Index: <br />
http://www.nasdaq.com/symbol/spy/historical, <br />
https://finance.yahoo.com/quote/%5EIXIC/history?period1=34588800&period2=1511510400&interval <br />
Data about Bitcoin and Ethereum's Return on Investment(ROI) since they are being used as Initial Coin Offerings(ICO):<br />
https://www.icostats.com/vs-btc <br />
Data about Number of Transactions per day for Bitcoin and Ethereum:<br />
https://etherscan.io/chart/tx, https://www.quandl.com/data/BCHAIN/TOTBC-Total-Bitcoins?utm_medium=graph&utm_source=quandl<br />
Data comparing EURO, USD Index prices:<br />
http://www.global-view.com/forex-trading-tools/forex-history/, http://www.macrotrends.net/1329/us-dollar-index-historical-chart <br />
##### Here is the link to juypter notebook: <br />

### 3. Visualizations showing Metrics:
#### Metrics 1: A $1000 investment in 2013, would have got you a minimum of 1700% in profits today!
Image2

The Visualization above shows a hindsight view of the value of Bitcoin against the major established currencies like USD and Euro in the market. The Cryptocurrency market is different from the Currency market in a way that the currencies are highly circulated to buy/sell goods and services globally and every platform accept these for transactions. But for Bitcoin, there are not as many platforms as other currencies have for tranactions, people have lately started to accept it. But as we observe the graph, the scale of the value of the investments in the Cryptocurrency market is very high. So, based on the past market trends of bitcoin, we can say that if you invest in bitcoin even today, it can promise you higher returns in the future. Bitcoin is indeed, a highly-valued asset to have!

#### Metrics 2: Bitcoin is an asset, Not a currency!
Image3

The visualization above shows the number of transactions per day of Bitcoin compared to Ethereum(the second best in the cryptocurrency market). Though Bitcoin came in early (around 2009) the number of transactions per day using bitcoin have not increased very much- just 240K. This number when compared to the time frame which is 8 years is very less, considering the fact that this is a currency. The reason behind this – A Lot of people are buying bitcoins but are not using them in day-to-day transactions as they are treating them as an investment, a long term asset to keep. The comparison with Ethereum makes it clearer. Ethereum has almost double the amount of transactions which means that people are not willing to use it as an asset rather a mode of exchange. Therefore, we can conclude Bitcoin is an asset, not a currency as perceived by people!

#### Metrics 3: Bitcoin, an ideal investment when compared to other cryptocurrencies!
Image4

Bitcoin, being the oldest in the cryptocurrency market provides a peer-to-peer transaction for all prospective investors and Ethereum is its biggest competitor. The above dashboard shows candlestick charts for Bitcoin and Ethereum showing the historical price pattern of both, since Ethereum was launched in 2015, we have taken a timeline of 2013-2017. As we observe, Bitcoin has witnessed a tremendous increase in its market price since inception and has remained the least volatile cryptocurrency in terms of investment and the price appreciation over the recent years when compared to Ethereum, which had a wide volatility rate in 2017. Despite being considered and generally perceived to be a digital currency which in technical terms, Bitcoin is, it is however currently operated as an investment with exceptionally great profit margins as mentioned in other metrics.

The reason behind considering Bitcoin an ideal investment is, Bitcoin has high liquidity and market capitalization among other currencies. In 2017, there has been a drastic increase of around 975% in its market price and has market capitalization of almost $70 Billion. Many financial institutions and banks like J.P. Morgan have announced their plans to introduce cryptocurrency future which would provide attractive investment opportunities to all the prospective investors and would bring more stability in the market of cryptocurrencies. Bitcoin investment would enable investors to utilize portfolio diversification, hedge their foreseeable risk and maximize the future expected return.

#### Bitcoin, less volatile than Ethereum!
Image5

The above Tableau visual shows the Bollinger Bands for Bitcoin and Ethereum's price using moving average and utilizing the lower and upper band as price indicators. As we see, Bitcoin has witnessed a steady rise and its moving average has reasonably stayed with the lower and upper bands. This indicates less volatility and better foreseeability for prospective investors interested in investing in Bitcoin while for Ethereum, since upper and lower bands indicate volatility, we can see that it has suffered a drastic volatility in 2017 as the bands widened in the gap from the moving average in the middle. Though this trend was witnessed by almost all of the major cryptocurrencies in the year 2017 but volatility of Ethereum was higher than that of Bitcoin.<br />
The reason being, Ethereum is an altcoin which makes it more prone to pump and dump behavior and less likely to be considered a long term asset. So, Ethereum being new to market is experiencing high supply ans people can move it around faster because of its low fees and block times.

#### Integrated Metrics(Comparing 3 cryptocurrencies together):
Image6

#### Metrics 4: Bitcoin's surge makes it bigger than these iconic companies!
Image7

Image8

Image9

## The Rebuttal:
### Ethereum has better ROI since ICO
Image10

The visualization above shows the Initial coin offering(ICO) names and the ROI for Bitcoin and Ethereum since they have started being used as ICO. This shows that Ethereum is better than Bitcoin when it comes to ROI





 
 
 
 
 
 References:
http://markets.businessinsider.com/currencies/news/bitcoin-pizza-10000-100-million-2017-11-1009827466


















https://support.coinbase.com/customer/portal/articles/1834921-why-does-bitcoin-change-value-why-is-the-price-so-volatile-
