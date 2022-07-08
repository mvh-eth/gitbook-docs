# API

### Why is NFT valuation Needed

Non Fungible means each token is unique, making the problem of valuation more complex than simply taking the floor price or the average sale price from a collection. Each asset has its own unique valuation depending on its combination of traits and the current market value for the collection.

There are many instances where a user requires an accurate price valuation, for example if a user owns a rare Bored Ape and they want to take out a loan using the Ape as collateral it's important to know the specific value of that Ape.

The specific valuation of an asset is also important when a user wants to list the asset for sale, it’s not always clear what the fair market price is. This problem of not knowing the value of an asset often results in users listing for less than what it's actually worth.

### How does a valuation model help

The regression machine-learning model is able to predict the current price for a given NFT from its traits, their rarities and the current average price of the collection. Therefore, the model is learning how much “added-value” is given to an individual NFT by its traits compared to an average item within the collection.

### Data used to train the model

* NFT collection average sale price (at time of sale)&#x20;
* Overall Rarity ranking (within collection)&#x20;
* Number of traits the NFT has&#x20;
* Date of the NFT sale&#x20;
* Collection age (at the time of sale)&#x20;
* How long since most recent ATH (at time of sale)
* &#x20;USD value of sale currency (at time of sale)

#### Model Accuracy

Our model is trained on 80% of the data we’ve collected, leaving 20% of the data unseen by the model to test accuracy. We measure model accuracy in Median Absolute Percentage Error (MAPE) - on average how far away from the real price is our prediction.&#x20;

{% hint style="info" %}
Currently we’re achieving a MAPE of 7%&#x20;
{% endhint %}

This means that 50% of our predictions are within 7% of the correct value

![](https://lh6.googleusercontent.com/067S-wc\_C\_pBnXN1Pn5zimTAWhdQJpGqK3flfQV2pKQso2oOddBSf4Ct4TOvrfSG3\_N91WbBPbCtiVjS-0G\_DvbEPKkKXJoI4G43bXUh-DWsJ4l0EbjI7yFvhL0haZEhnfh0Vfk5Yrcr\_wxfu50)
