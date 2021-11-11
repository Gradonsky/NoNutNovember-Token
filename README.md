# NoNutNovember-Token

<p align="center">
  <img src="https://i.ibb.co/BG9gVM4/NNNToken.png" alt="NNNTokenLogo"/>
</p>


[NNN Website](https://nonutnovembertoken.com)

November is here and you want to participate in the most important Internet-Challenge during the year? 
Show your friends that you are brave enough to STOP Nutting for one month, but also unlock special human abilities (#ApprovedInfo).
This is your moment to be a part of the NoNutNovember-Army by buying & hodling the NoNutNovember-Token.
Be the next NoNutNovember-Chad and get ready to show your friends 6969x gains in your supernatural abilities! 

NNN-Token project is not only a meme
but also a real long-term project with plans to revolutionize the adult film industry.

## How to deploy your own Cryptocurrency based on NNN & Binance Smart Chain

1. Open [Remix IDE](https://remix.ethereum.org/) in your browser and create a new File (SOL file)
2. Connect your wallet (I prefer to use metamask)
3. Clone the NNN Token Code and paste it into the file which we created.
4. Now proceed to the NoNutNovember Contract in the file and find the lines 
```
    string private _name = "NoNutNovember";
    string private _symbol = "NNN";
    uint8 private _decimals = 9;
    
    uint256 public _taxFee = 2;
```
```
    uint256 public _liquidityFee = 3;
```
```
    bool public swapAndLiquifyEnabled = true;
    
    uint256 public _maxTxAmount = 1000 * 10**6 * 10**9;
    uint256 private numTokensSellToAddToLiquidity = 1000 * 10**9;
```
👉 As you probably noticed \_name_ stand for name of your Token, \_symbol is your Token symbol and \_decimals are the digits after the decimal point (9 in our case)

👉 \_taxFee - how much % of the transaction will be redistributed to the holders of your currency.

👉 \_liquidityFee - how much % of the transaction will be send back to the Liquidity Pool.

👉 \_maxTxAmount - is the maximum tansaction amount. 10\*\*6  indicates 10^6 ( in our case it will be 1 000 000 000). \* 10\*\*9 indicates the digits after the decimal point.

👉 numTokensSellToAddToLiquidity - when does the Tax/Liquidity fee trigger (in our case 1000 + 9 digits after decimal point).




**If you wanna deploy the contract on BSC-Testnetwork consider switching the PanCakeSwapV2 Router Address to _0xD99D1c33F9fC3444f8101754aBC46c52416550D1_**


Got any questions? 
Feel free to ask :)










