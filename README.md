# NFT Market Analysis with Machine Learning

## Note: This Project is still under development.

Non Fungible Tokens, also known as NFTs can be seen everywhere these days. So much that the world witnessed these entities sell for millions of dollars similar to a 17th century piece of art. But is the hype here to stay, or according to some experts a bubble poised to pop? To find answers to this question, I decided to work on this project focusing on finding price predictions and analyzing market trends relative to this entity with the help of Machine Learning and graphs. The data was extracted from CryptoSlam, a website whose API was used to extract information about the top 100 NFTs in the market per sales volume.

One of the key words which we always assocciate or hear whenever there are discussions about NFTs is 'hype'. Hence, to test this theory, I extracted twitter data about discussion threads happening on Twitter and applied NLP Sentiment Analysis on it to see the ratio of people in favor or against a certain NFT collection. This analysis acted as a key parameter in delivering predictions with the help of our machine learning model. The extraction of twitter data was done with the help of 'Twint' library, a Twitter Intelligence Tool used to extract tweets relative to the target variable. The Machine Learning Model is trained in scikit-learn and the model of choice for this project is Decision Trees. The visualization of trends is achieved in Matplotlib, Plotly, Seaborn, and Tableau. The accuracy improvement and hyperparameter tuning is under progress for this project {Visual characteristic extraction}.




