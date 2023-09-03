# GenAI_Chutki
Submission of Grey Hatters- Generative AI for impact

What is our project? - Check out our proposal https://drive.google.com/file/d/14be6VBbZj1n3g-tXe_lZl3m-8jmm-2HN/view?usp=sharing

How our model works:

The input sentence(s) is split into words. We compare the words with a bag of words, and create a vector.
This vector is then inputted into a neural network.
The final layer of this neural network represents a category.(We have multiple categories in the intents.json file. The output of the neural network gives the probabilities of the sentence inputted belonging to each category. Based on the category it is in, we return an output.)
We train the model with the intents.json file and save the model in a file, which we use when we run the chat finally.
How to execute the code:

Download all the files into the same folder
Execute train.py - this will train the model using the data in intents.json and will save the model in data.pth
Execute chat.py - the model saved in data.pth is used to execute the chatbot - Enjoy chatting :)
