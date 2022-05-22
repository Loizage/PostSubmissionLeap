# Smart contracts

## LeapHub

Main LEAP protocol contract.

Regulating:
- Subscriptions (minting, staking, unstaking NFTs)
- Reward calculations and destributions
- User's progress data updates
- Protocol parameters updates

## LeapNFT

Basic NFT contract: Pausable, Mintable, Burnable, with Roles

Mint permissions belongs to LeapHub contract.
User can mint token through LeapHub contract `mintNFT` function.

On mint:
NFT token being minted and staked immedietly into LeapHub protocol.
Subscribing NFT owner to Leap protocol.

Unstaked tokens could be transfered or traded classic way for ERC721.

## LEAP Token (ERC20)

Basic ERC20 contract: Pausable, Mintable, Burnable, with Roles

Is used as bassic reward asset for LEAP protocol.