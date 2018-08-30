# StackOverflow-assistant-bot
*Dialogue chat bot*, which will be able to:
* answer programming-related questions (using StackOverflow dataset).
* chit-chat and simulate dialogue on all non programming-related questions.
### Prerequisites
This tutorial requires the following packages:

* Anaconda Package
* tensorflow version 1.2 or later: https://www.tensorflow.org
* ipython/jupyter version 4.0 or later, with notebook support
* chatterbot
* nltk
* sklearn 
* requests
### installation

##### Anaconda
* https://conda.io/docs/user-guide/install/linux.html

##### Tensorflow
* https://www.tensorflow.org/install/

##### jupyter notebook
* https://ipython.org/

##### chatterbot
* https://chatterbot.readthedocs.io/en/stable/setup.html

##### nltk
* pip install nltk

##### Sklearn
* pip install sklearn

##### Requests
* pip install requests

##### Running 
* First Extract word_embeddings.tsv file from word_embeddings.tar.xz.Then run the StackoverBot-project.ipynb notebook to get all the necessary .pkl file.

* We are going to integrate the bot to Telegram messenger. To do so, you will need to create a token and use it to run the bot.

    * Talk to @BotFather in Telegram. The command "/newbot" will create a bot for you. You will be prompted to enter a name and a username for your bot. After that, you will be given a token.
    * Run the 'Hello world' bot with the scripted provided for you: python3 main_bot.py --token=YOUR_TOKEN

You can now talk to this bot in Telegram!
 
### Acknowledgments
Got the dataset from Natural Language Processing course (Coursera) https://www.coursera.org/learn/language-processing
