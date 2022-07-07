# Zash <> NFT Vision

### What does the model tell us

The regression model is able to predict the relationship between the traits a price for a given NFT within a collection, for example if the floor for okay bears is 100 SOL the model is able to tell us that okay bear x with y rarity is worth 234 SOL. Because the model is trained knowing the current floor and mean price all of the predictions are collaborated to the current market.

### How is the model trained

The model is trained on traits and sale history.

The algorithm is input with all of the metadata about a given NFT collection, using this data we calculate the rarity of each trait as well as the overall rarity, the mean rarity and the number of traits.

Along with this the model is input with the daily mean price for the collection, the daily floor price and the SOL or ETH price in USD

The target variable we are training the model for is price of the NFT

To predict the price a regression model is being used, specifically XGBoost

