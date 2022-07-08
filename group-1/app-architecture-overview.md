# App Architecture overview

This app will have web2 components that are required to train and run the machine learning models, as well as compute the best value listings

This will be implemented using the reservoir api to provide transactions, metadata and all other NFT data

Airflow running on GCP will be used to store this data in a big query table

{% hint style="info" %}
How are we going to run the ML models from big query day
{% endhint %}
