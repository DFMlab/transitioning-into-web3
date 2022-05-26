# transitioning-into-web3


## instructions on creating ERC20 Token

1. Install Metamask for [chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ether-metamask/).

2. Create a wallet address.

3. Add Celo to MetaMask using the configuration below:

```
Network Name: Celo (Alfajores Testnet) 
New RPC URL: https://alfajores-forno.celo-testnet.org 
Chain ID: 44787 
Currency Symbol (Optional): CELO 
Block Explorer URL (Optional): https://alfajores-blockscout.celo-testnet.org 
```

4. Request for funds from [Celo Faucet](https://celo.org/developers/faucet)

5. Go to [remix IDE](http://remix.ethereum.org/).

6. Create a new file and name it ERC20.sol.

7. Paste the content of [the ERC20 file](ERC20.sol) to the ERC20.sol in Remix browser.

8. Compile the ERC20.sol.

9. Switch environment to Injected Web3

10. Switch contract to ERC20.sol
 
11. Click on Deploy and set your token name, symbol and supply.

12. Import your token to MetaMask and start sharing.

That's all
