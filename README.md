# Emojifier
Implement a model which inputs a sentence and finds the most appropriate emoji to be used with this sentence 
This mini project was a part of the course Sequential Models by deeplearning.ai

Using word vectors to improve emoji lookups
In many emoji interfaces, you need to remember that ❤️ is the "heart" symbol rather than the "love" symbol.
In other words, you'll have to remember to type "heart" to find the desired emoji, and typing "love" won't bring up that symbol.
We can make a more flexible emoji interface by using word vectors!
When using word vectors, you'll see that even if your training set explicitly relates only a few words to a particular emoji, your algorithm will be able to generalize and associate additional words in the test set to the same emoji.
This works even if those additional words don't even appear in the training set.
This allows you to build an accurate classifier mapping from sentences to emojis, even using a small training set.
