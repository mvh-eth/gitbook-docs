# Decision 3 - What NFT's to buy

By time decision 3 is reached the DAO has decided that the market is profitable and has chosen 5 collections to trade from. The next decision is then which NFTs to buy within these collections. This is where the preparatory NFT vision trading algorithm is used, by calculating the predicted price of all NFT’s within the given number of collections and cross referencing that with active listings the algorithm is able to determine the best NFT is to buy right now.



If an NFT is listed for over 10% less than what we predict its value to be then the DAO buys it&#x20;



{% hint style="info" %}
It may be possible to place bids on all potentially profitable NFT's
{% endhint %}



The price prediction model is given the average sale price within the collection at time of sale, and then uses additional NFT metadata to determine what gives the NFT "added value". The metadata used by the model includes, overall rarity, highest rarity trait, rarity of specific traits, number of traits.&#x20;

Using this data we have trained a model  which was able to predict sale price with a Median Absolute Percentage Error (MAPE) of 4.5%. Meaning half of our predictions were within 4.5% of the actual sale price.
