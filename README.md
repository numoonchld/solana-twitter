# solana-twitter
[solana-hackathon-encode-club](https://encodeclub.notion.site/Encode-Hackathon-sponsored-by-the-Solana-Foundation-cfd788bfb5ef44abaaaa00e380f85463)

## notes

I have built an Anchor framework based micro-blogging platform dApp. Vue enables the User Interface. 

The dApp is capable of connecting to a Phantom wallet and receiving transactions to post tweets on the tweet wall. 

Every tweet is a separate account - and different wallets can be used to login to the dApp and users can see all the tweets in the home page. 

Anchor acts as the Solana blockchain provider and Solana Web3JS is used for the connection from the UI to the program deployed via Anchor to the Solana blockchain. 

A solana-wallet-adapter library was used to enable connecting the UI to the wallet which is turn connects to localhost solana-test-validator. 

Future Work: Deploy program on to testnet and devnet to ensure usability. 


## code repos
- [solana-twitter-frontend](https://github.com/numoonchld/solana-twitter-frontend)
- [solana-twitter-backend](https://github.com/numoonchld/solana-twitter-backend)

## summary deck

- [Deck PDF](https://github.com/numoonchld/solana-twitter/blob/master/Solana%20Twitter%20-%20Overview%20Deck.pdf)
- [3-min Demo Screencast](https://github.com/numoonchld/solana-twitter/blob/master/solana-project-screencast-demo-obs.mkv)

## references
- [Create a Solana dApp from scratch](https://lorisleiva.com/create-a-solana-dapp-from-scratch)

