# Perceptual Attributes
The goal of this work is to use distinct tools to define and display groups of people in user generated content. 
This is, to find groups that by analyzing their reviews on an entity, (such as a movie, product or service) agree on the importance of certain features. 
Features can be extracted explicitly by use of a Natural Language Processing and Sentiment Analysis approach, or in a more abstract way such as Vector Embeddings (doc2vec). 
Then the groups are generated via clustering algorithms, possibly Subspace Clustering, to deal with the high-dimentionality of the data.
The parameters of the algorithms should then be finely tuned by a domain expert to assure that the groups represent the actual perceptual agreement of users for the given entity.
Finaly, this groups should be shown in a manner similar to data cubes, with drill-down, slicing and dicing capabilities, etc.; with the end goal of capturing the information contained in many reviews in a useful way.
