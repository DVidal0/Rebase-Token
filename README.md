# Cross-chain Rebase Token

1. A protocol that allows user deposit into a vault and in return, receve rebase tokens that represent their underlying balance.
2. Rebase Token -> balanceOf function is dynamic to show the changing balance with time.
   1. Balance increases linearly with time
   2. Mint tokens to our users every time they perform an action (minting, burning, transfering, bribging)
3. Interest rate
   1. Individually set an interest rate for each user based on some global interest rate of the protocol at the time the user deposits into the vault
   2. This global interest rate can only decrease to incentivise/reward early adopters.