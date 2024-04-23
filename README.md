# Natural Language Processing with Disaster Tweets

About Dataset

Each sample in the dataset has the following information:

id - a unique identifier for each tweet

text - the text of the tweet

location - the location the tweet was sent from (may be blank)

keyword - a particular keyword from the tweet (may be blank)

target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

About Notebook:

1. Cleaning the data</BR>
  i) Making text all lower case.</BR>
  ii) Removeing punctuation.</BR>
  iii) Removing numerical values.</BR>
  iv) Removing common non-sensical text.</BR>
  v) Tokenizing text.</BR>
  vi) Removing stop words.</BR>
3. Organizing the data</BR>
  i) Generating corpus.</BR>
  ii) Generating Document-Term Matrix(dtm).</BR>
4. Exploring the data</BR>
  i) Creating word cloud for most common words.</BR>
  ii) Finding the count of top 30 words associated with top 10 keywords.</BR>
  iii) Adding most common words to stopword list.</BR>
  iv) Updating document-matrix with new stop_words.</BR>
  v) Creating word cloud for top 5 keywords.</BR>
  vi) Finding the number of unique words associated with each unique keyword.</BR>
  vii) Check the profanity by analysing the common bad words.</BR>
6. Sentiment Analysis</BR>
  i) Find the polarity and subjectivity of each tweet.</BR>
  ii) Visualizing the results through scatter plot.</BR>
  iii) Split each tweet into 10 parts and finding their polarity.</BR>
  iv) Visualizing the results through subplots.</BR>
7. Topic Modeling</BR>
  i) Putting dtm into new gensim format.</BR>
  ii) Generating dictionary of the all terms and their respective location in dtm.</BR>
  iii) Applying Latent Dirichlet Allocation (LDA) for all text.</BR>
  iv) Applying Latent Dirichlet Allocation (LDA) for nouns only.</BR>
  v) Applying Latent Dirichlet Allocation (LDA) for nouns and adjectives.</BR>
8. Text Generation</BR>
  i) Building a Markov Chain Function.</BR>
  ii) Creating the dictionary of text data.</BR>
  iii)  Creating a Text Generator Function.</BR>
