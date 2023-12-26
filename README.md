# Shared Wallet
A shared wallet that will hold funds in ETH and that can be funded by an admin. The admin will provide an allowance to a few users who can then spend it as per their allowance and till a certain time limit set by the admin.

The entire flow will work as follows :

1. Admin deploys a smart contract that acts as a shared wallet.
2. Admin funds the wallet with some ETH, this will be the wallet’s total balance.
3. Admin authorises certain wallet addresses to spend a certain amount of ETH from the wallet within a certain time limit.
4. Finally, the users can spend the ETH within their allowance and time limit, as set by the admin.

Once it’s deployed, send some ETH to the smart contract.
To send Wei or ETH to the contract using Remix,
1. Click the deployer icon on the icon panel
2. Then add the amount of Wei to be transferred in the side panel (value)
3. And finally, click the Transact button at the bottom of the side panel: