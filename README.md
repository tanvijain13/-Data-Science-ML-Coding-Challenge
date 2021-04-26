# Data-Science-ML-Coding-Challenge
This repository is for the Data Science ML Coding Challenge for Eluvio. Since this was an open challenge, I decided to include all the skills that I have learned from my academic projects and research to find an optimal problem and solve it.
## The first code is [Eluvio_Lime.ipynb](https://github.com/tanvijain13/-Data-Science-ML-Coding-Challenge/blob/main/Eluvio_Lime.ipynb) which targets on the classification of the specific *title* (text), and predict if it is an interesting title or uninteresting based on the *"up_votes"*. And to classify this, I have used following procedure :
  ### 1. Removing the null values/zero values for *"up_votes"*, so that only genuine title which has some number of votes is considered. 
  ### 2. Adding the classes (categories) for classification - I have created two categories **(High,Low)** for interesting and uninteresting/less interesting titles correspondingly.
  ### 3. Sampling the data such that both classes have equal number of datapoints in train dataset.
  ### 4. Preprocessing and cleaning data, like removing stopwords, punctuation, special characters, decontracting the phrase, stemming.
  ### 5. Performing TFIDF Vectorization -  
  ### 6. Taking vectors and lables (vectors for each title and class names (high,low)) and sending for classification through Random Forest, performing the prediction.
  ### 7. Using LIME to explain what machine learning classifiers (or models) are doing, and which/why did the specific *"title"* falls in High/Low category of being interesting or uninteresting based on models predictions. 
  

## The second code [Eluvio_business_challenge.ipynb](https://github.com/tanvijain13/-Data-Science-ML-Coding-Challenge/blob/main/Eluvio_business_challenge.ipynb), focus on Topic Modelling and TSNE visualization of the dataset provided. This focusses on *"providing analytical insights for some business use cases"* aspect of this coding challenge through extracting important topics by topic modelling and projecting information about the dataset and what's important (topic wise) through TSNE visualization. Here are the different steps which I have done:

  ### 1.Loaded the dataset **(Eluvio_DS_Challenge.csv)**
  ### 2.Tokenized sentences and converted the sentence into list
  ### 3.Lemmatized each work in the list
  ### 4.Built a topic model using LDA topic modeling
  ### 5.Extracted the most dominant topic from multiple topics
  ### 6.Most relevant words based on that topic
  ### 7.Plotted word frequency graph
  ### 8.Plotted a word cloud of keywords of each topic
  ### 9.Graph of word count of topic keywords
  ### 10.Visualization of Dominant Topics in dataset
  ### 11.Visualization using T-sne clustering chart
  ### 12.Final visualisation using PyLDA on mutiple topics 
