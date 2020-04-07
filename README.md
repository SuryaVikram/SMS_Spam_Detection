# SMS_Spam_Detection

Problem is to Classify whether an SMS is Spam or not

Dataset contains labelled text messages. Ham indicating not spam.

The jupyter notebook deals with
Preprocessing the data
Feature Engineering 
  - create features based on word Counts and char counts
  - create features based on parts of speech tags (pos tags)
  - create features based on Count Vectoriser and Tfidf vectoriser
      -- tfidf vector with max features, ngrams
 Using Hstack, csr matrix to combine vetor features and meta features
 Label encoding target label and train test split to split 
 Model with Naive Bayes MultinomialNB
 Model with Logistic regression
 Model with svm.SVC
 Model with ensemble.ExtraTreesClassifer
 Model with CNN
  - using pretrained word vec https://dl.fbaipublicfiles.com/fasttext/vectors-english/crawl-300d-2M.vec.zip to create embeddings index
  -  create a word index with keras.texts
  - train_test_split 
  - padding trainx, valx using keras.sequence
  - create a embedding matrix using embeddings_index for words in word index
  - create a function for training the model
  - create a function for CNN
    - Input layer
    - Convolutional1D layer
    - pooling layer
    - Dropout layer
    - Output Layer
    - Model with adam optimiser and activation = binary crossentropy
 
 

  
