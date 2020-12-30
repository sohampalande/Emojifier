# Emojifier
Implement a model which inputs a sentence and finds the most appropriate emoji to be used with this sentence 
This mini project was a part of the course Sequential Models by deeplearning.ai

Using word vectors to improve emoji lookups
In many emoji interfaces, you need to remember that ❤️ is the "heart" symbol rather than the "love" symbol.
We have to remember to type "heart" to find the desired emoji, and typing "love" won't bring up that symbol.
We can make a more flexible emoji interface by using word vectors
When using word vectors,even if the training set explicitly relates only a few words to a particular emoji, the algorithm will be able to generalize and associate additional words in the test set to the same emoji.
This allows us to build an accurate classifier mapping from sentences to emojis, even using a small training set.

Start with a baseline model (Emojifier-V1) using word embeddings.
And then build a more sophisticated model (Emojifier-V2) that incorporates an LSTM. 
