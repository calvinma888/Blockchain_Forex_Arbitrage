# Bitcoin Cryptocurrency Exchange and 13 Foreign Exchange Arbitrage

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project
We analyzed the pattern for crypto price, and quantify the market impact, which can be used to measure transaction costs. Then we used the Garch model to predict cryptocurrency volatility.
For the foreign exchange trading strategy, we converted the amount of USD a vailable to foreign currencies, and then used the foreign currency to purchase Bi tcoin taking into consideration of all the fees including exchange fees, market impact fees, and various other fees, and then we held the Bitcoin for a certain number of days, after which all of the Bitcoin was sold in the foreign exchange, and after paying for all of the fees in the selling transaction, the foreign currency is converted back into USD. In a two month period, taking into account of all the fees, the returns, which varied from 3.35% to 5.38% across the various foreig n exchanges, greatly exceed the flat annual fee of $95 needed to maintain the credit card that offers fee-less foreign currency exchanges. This shows that utilizing foreign exchanges and foreign currencies to purchase and sell Bitcoins does provide opportunities for arbitrage.

### Built With

* []()Python


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these steps.

### Prerequisites

This is a list of packages that need to be installed before the notebook can be run.
* sklearn
* quandl
* BlockChair
* yFinance
* pandas
* numpy
* seaborn
* matplotlib
* scipy


### Installation

Clone the repo: https://github.com/calvinma888/Blockchain_Forex_Arbitrage.git
   

<!-- USAGE EXAMPLES -->
## Usage

Run with Jupyter Notebook


<!-- CONTRIBUTING -->
## Contributing

Calvin (Yu chien) Ma
