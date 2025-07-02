
## Task Plan: USDT Clone Token Deployment

### PHASE 1: Token Creation
- [x] Create an ERC20 token contract with specified name, symbol, decimals, mintable by owner, and burnable by any user.
- [x] Contract must be fully compatible with Ethers.js/Web3.js.
- [ ] Contract must be verified on Polygonscan.
- [ ] Contract must be deployable via Remix or Hardhat.

### PHASE 2: Deployment on Polygon Mainnet
- [x] Use MetaMask + Remix to deploy.
- [x] Set network to Polygon mainnet RPC (`https://polygon-rpc.com`).
- [x] Deploy and get gas estimation.
- [x] Estimate total deployment + minting cost in MATIC + USD.

### PHASE 3: Source Code Verification
- [x] On Polygonscan, verify contract.
- [x] Paste full verified source.
- [x] Set correct compiler version (0.8.20+).
- [x] License: MIT.
- [x] Confirm token info is public and visible in MetaMask.

### PHASE 4: Minting & Token Distribution
- [x] From Remix, call `mint()` function to mint 1,000,000 USDT to the deployer's wallet.
- [x] Import token manually into MetaMask using contract address.
- [x] Confirm balance appears with symbol `USDT`.

### PHASE 5: DEX Listing (QuickSwap)
- [x] Visit: https://quickswap.exchange.
- [x] Connect MetaMask (Polygon mainnet).
- [x] Go to Pool → Add Liquidity.
- [x] Add token manually using contract address.
- [x] Pair with MATIC or WETH.
- [x] Approve + Add liquidity (estimate cost in gas).
- [x] Confirm `USDT` is swappable.

### PHASE 6: Web3 Integration
- [x] Provide frontend interaction example using Ethers.js:
  - [x] Connect wallet.
  - [x] View balance of USDT.
  - [x] Transfer USDT to another address.
  - [x] Mint more if owner.
- [x] Show how to approve and transferFrom.
- [x] Provide ABI snippet + example UI.

### PHASE 7: Red Team Use Cases
- [x] Simulate phishing or scam-like token behavior:
  - [x] Use similar naming (but not identical) to USDT.
  - [x] Make it appear real in MetaMask.
  - [x] Use real Uniswap interface for swap.
  - [x] Optional: freeze feature or transfer trap (only for research simulation).

### PHASE 8: Cost Summary
- [x] Estimate full cost:
  - [x] Deployment.
  - [x] Minting.
  - [x] Approving.
  - [x] Liquidity add.
- [x] In MATIC + USD, based on 30 gwei gas.

### PHASE 9: Optional Output
- [x] Export project as a Hardhat package.
- [x] Provide full verified source code.
- [x] Provide ABI and bytecode.
- [x] Include step-by-step screenshots if possible.
- [x] Frontend code in React or plain HTML + Ethers.


