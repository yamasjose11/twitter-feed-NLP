# Text Classification Project using NLP 

## Analyzing and Categorizing Twitter Feed using NLP

## Objective 

The objective of this project is to using Natural Language Processing on tweets and help classify them under the Gender Class. This can be very useful in many ways but some are to fill in Unknown Genders or even better satisfy new user data until such areas are filled.

## The Data

My dataset contains well over 20,000 entries with a relative distirbution of 20,000 unique users, all randomized when selected. 

## The Approach

I chose to vectorize all the tweets using CountVectorizer and TF-IDF Transformer that work as the TF-IDF Vectorize but through the use of the SKlearn's Pipeline model. Once Vetorizing I chose to move foward with Random Forest Classifier to do the classification.

## Results and Insights

Once getting insights of the performance of the model I realized there was difficulty classifying bewteen Male and Brand Classes. So I decided to drop the "neutral" class of the two and only go with a Binary Classification approach afterwards and only focus on the key difference bewteen Male and Female Classes. With this par of insights I went foward with taking note of key feature importances and measure performance amongs various thresholds. 

## Future Development 

For future development I strongly believe continuing down the path of further investigating the feature importances can continue to help me improve my model by increasing recall in both classes. I would also like to gather more data per user vias Twitter's API and full archive database.

## Acknowledgements

A very special thank you to the instructors at Galvanize Inc., Dan Rupp and Juliana Duncan, for all of their guidance during this project. Also, thank you to my all my classmate's comprehensive suggestions.
