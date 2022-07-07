# Decision 3 - Which NFT's should be brought?

By the time decision 3 is reached, the DAO has decided that the market is profitable and has chosen 5 collections to trade from. The next decision is then which NFTs to buy within these collections. This is where the proprietary NFT Vision trading algorithm is used to determine the best NFT to buy right now. The predicted price of all NFT’s within the given number of collections is calculated, and cross referenced with active listings to find the best value NFT's.&#x20;

If an NFT is listed for over 10% less than what we predict its value to be, the DAO buys it&#x20;

{% hint style="info" %}
It may be possible to place bids on all potentially profitable NFT's
{% endhint %}

The price prediction model is given the average sale price within the collection at time of sale, and then uses additional NFT metadata to determine what gives the NFT "added value". The metadata used by the model includes, overall rarity, highest rarity trait, rarity of specific traits, number of traits.&#x20;

Using this data, we have trained a model which was able to predict sale price with a Median Absolute Percentage Error (MAPE) of 4.5%. This means half of our predictions were within 4.5% of the actual sale price.
