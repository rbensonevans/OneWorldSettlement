# OneWorldSettlement
A settlement platform for Central Bank Digital Currencies. 


Note: This project was started during the Ripple CBDC Innovate hackathon (August 2023).

Project Name: OneWorld-XRP

Preface: 

Over the next 10 years, to enable financial activity, the financial world will move from primarily using physical cash to primarily using digital cash in the form of what is now called a Central Bank Digital Currency, CBDC. The basic form of a CBDC is generally understood but one can bet there will be a plethora of implementations.

This move to digital cash or CBDCs will require a modernization of other parts of the financial system, for example, in the settlement of foreign exchange.

Idea:

Create a platform and hub for the creation, exchange and settlement of CBDCs between countries via their central banks.

The generalized solution:

Since many different types of CBDCs can be expected a flexible solution is required. The solution implemented here would be to provide a “banking” system which keeps track of reserves, exchange rates and accumulation amounts of the different currencies within a country or economy. An interface for managing settlement of currencies between any two countries will be provided.  
In this solution, the “banking” system will keep track of currency amounts for each type of currency along with the private keys to the corresponding “blockchains” if a custodial solution is needed.  
If a non-custodial solution is required by any central bank, that central bank will have to provide the facility, the APIs, which permit the movement of funds on the various blockchains on which those funds exist. 

The XRP solution:

The XRP solution can be either an extension of the generalized solution above or possibly a replacement of it but fully implemented similarly on the XRP blockchain.

In such a design, tokens will be used to represent non-XRP CBDCs. The DEX may be used for settlement of currencies between countries. The drawback to this implementation is that settlement still has to be executed on the original blockchains. At a minimum the cost would have doubled given the XRP cost and the original blockchain cost for transactions.

Further research is needed.

System Interface:

* Account Opening Process – required by each participating central bank.  
* Deposit Reserve Funds By Country \- from central bank to settlement hub.  
* Withdraw Funds By Country \- from settlement hub to the central bank.  
* FX Exchange Basic – one to one currency exchange.  
* FX Exchange Multi – one to many currency exchange.  
* FX Exchange Complex – many to many set of currencies exchange.  
* Set Settlement Thresholds – drives automated settlement.  
* Block FX Transfers – for sanctioned countries.  
* UnBlock FX Transfers – for sanctioned countries.  
* Sell Funds \- at a specified rate.  
* Purchase Funds \- at a specified rate.  
* Trade Buy Currency \- at market rate.  
* Trade Sell Currency \- at market rate.  
* Activity Reports

 
