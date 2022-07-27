# AEDA-Project

## Libraries Used : 
1. Numpy
2. Pandas
3. SkLearn
4. Keras
5. TensorFlow
6. Nltk
7. Matplotlib

## Dataset Used :
1. CR (Customer Reviews Dataset)
2. PC (Pros and Cons Dataset)
3. SST-2 (Standford Sentiment Treebank)
4. SUBJ (Subjectivity/Objectivity Dataset) 
5. TREC (Question Classification Dataset)

## Statistics of the datasets : 

![image](https://user-images.githubusercontent.com/52949047/181233645-e5a9e373-b607-4d8e-b862-63f92abbc40d.png)

## EDA
We perform four augmentations for each sentence, one corresponding to each of the following techniques.
1. Synonym Replacement (SR) : Choose 10% words out of the total number of words in the sentence and replace them with their synonyms.
2. Random Insertion (RI) : We have randomly inserted 10 percent words out of the total number of words in a sentence.
3. Random Swap (RS) : For 10 percent of the words out of the total number of words in a sentence, we have randomly chosen another word and replaced the two.
4. Random Deletion (RD) : We have randomly deleted 10 percent of the words out of the total number of words with a probability of 90 percent in a sentence.


## AEDA

1. We perform four augmentations for each sentence.
2. First convert the sentence into individual words.
3. Out of the six punctuation marks ['.', ',', '!', '?', ';', ':'] , we randomly select a punctuation to add to the sentence at any random position in the sentence.
4. Return the list of the updated sentences.


## Flow of Work : 

![image](https://user-images.githubusercontent.com/52949047/181233329-45a5a58d-5979-4792-9b2e-7fb71737b958.png)


## Result on each Dataset :

1.  Customer Reviews Dataset

![image](https://user-images.githubusercontent.com/52949047/181235829-61a4d3a5-1233-473d-95a8-d335926170ef.png)

2. Pros and Cons Dataset

![image](https://user-images.githubusercontent.com/52949047/181235909-598e1f49-7d83-4f0d-ab5e-cad540876340.png)


3. Standford Sentiment Treebank Dataset

![image](https://user-images.githubusercontent.com/52949047/181235973-7b65871b-0bef-4b02-8376-c84d5319a6df.png)


4. Subjectivity Objectivity Dataset

![image](https://user-images.githubusercontent.com/52949047/181236027-e3fe7515-5075-4cce-beba-7ca870d910b5.png)


5. Question Classification Dataset

![image](https://user-images.githubusercontent.com/52949047/181236079-b923bd73-e18a-4739-a1a8-cad6957ecffc.png)
