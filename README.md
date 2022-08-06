# 2-sentence-answer-extraction
our application that takes two sentence and a question, and tries to predict the answer of that question based on the two sentence.<br/>
we multiple the two sentence embedding vectors with question embedding vector so we get the similarity score between them then we apply softmax to turns them into weights so we could multiple the two sentence embedding vectors with them to get where the answer is, kinda like the attention mechanism.
# how to run it
there is two ways to use it:<br/>
1-colab<br/>
2-locally<br/>
if you're using colab just upload the ipynb file and run it<br/>
locally:<br/>
1-you have to install python 3<br/>
2-the recommended libraries<br/>
3-install ide and open the .py file or .ipynb<br/>
4-run it

# the recommended libraries:
1-keras<br/>
2-numpy<br/>
3-matplotlib<br/>

# reference:
https://towardsdatascience.com/word2vec-explained-49c52b4ccb71<br/>
https://towardsdatascience.com/intuitive-understanding-of-attention-mechanism-in-deep-learning-6c9482aecf4f
