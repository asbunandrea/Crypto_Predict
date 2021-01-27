## Project 2 Outline
1/16/21 <br>
<br>


**Project Title:**  Crypto Entry/Exit Bot <br>
<br>

**Team Members:**	Collin Holben, Jeff Myers, Cathy Slider, Andrea Asbun<br>
<br>

**Project Description:**

Our project is to develop a Crypto Entry/Exit Bot for four PoW digital cryptocurrencies based on multiple indicators that have reasonably tracked with their historical prices. We will fit our data from these indicators to (LSTM) recurrent neural network models and eliminate any indicators that do not track within a reasonable acceptance range. Based on the highest performers, we will create an entry/exit bot to help users learn what the current buy/sell sentiment is for that coin.<br>
<br>

**Research Questions to Answer:**

1.	What is a reasonable acceptance range for technical indicators/historical price tracking?
2.	Which predictive models track best to the historical coin performance and are therefore reliable to include in the buy/sell decision helper? Indicators we will analyze are as follows: two sentiment analysis indicators (FNG, NewsAPI), exponential weighted moving average, money flow index, and on-chain data (mining difficulty, network fees, hash rate, total transactions). Potentially use "if stock price 3 days positive, buy; if stock price 3 days negative, sell(??)."
3. Can a similar model be executed for Proof of Stake digital currencies?<br>
<br>

**Recurrent Neural Networks to be Used:**


**Datasets to be Used:**

* Digital currencies historical closing prices from Kraken (Jeff)
* News articles from NewsAPI(Reuters) - Bitcoin, DASH (Collin), Ethereum, Litecoin (Cathy)
* Crypto Fear and Greed Index (Cathy)
* Google BigQuery for blockchain data (use where clauses "where date is > date) (Andrea/Collin)<br>
<br>

**Breakdown of Tasks:**
(to be determined Saturday morning after data downloads are complete)

1.	Research the best APIs or other source to use for each of the indicators – consider monthly limits and/or charges in general; comprehensive datasets - (all)
2.	Set up GitHub and branches - (Andrea)
3.	Initialize notebooks (for each coin based on initial ethereum notebook) – (Cathy)
4.	Set up imports and dataframes to be consistent in each notebook – (Cathy)
5.	Set up train/test/scale/shape – (x)
6. How do we backtest? ()
7.	Build the notebooks for each coin – (Jeff)
8.  Which RNNs should we use – (Collin, Cathy)
9.	Analyze the results – (group)
10.	Prepare visualization dashboard – (Cathy, Andrea)
11.	Research building a bot – (group) <br>
<br>
<br>

**To Do:**

* Finish on-chain .csv files and money flow index .csv files - done
* Standardize datetime columns 
* Merge all dataframes into one dataframe per coin/notebook(?)

**Other Items for Consideration:**

* Backtesting <br>
* Visuals include weekly prediction <br>
* Visuals to show model results evaluation <br>
<br>


~





