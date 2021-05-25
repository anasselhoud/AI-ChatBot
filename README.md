# AI-MealBot
An AI based Chatbot used for healthy meal propositions. I applied this AI project for Healthy meals recommendations based on calories and preferences. If you want to use the original code for other utilities, please contact me so I can help you to get and made the modification needed to deploy it. 

I have used Nltk and Tensorflow for the construction of the model. I have shared the code of the model and its result. It's up to you to deploy it using the tool you want (on your localhost or on any platform dedicated to that like Discord, Telegram...)
I added the script "main-host.py" that can directly run a localhost in your browser where you can interact with the chatbot your trained.

For my application, I have linked this AI Bot with Discord. As I already mentionned, this option is not included in the files "main.py" and "main-host.py" because the discord bot setup is required beforehand (Discord Developer mode). Feel free to contact me or check (closed issues)[https://github.com/anasselhoud/AI-ChatBot/issues?q=is%3Aissue+is%3Aclosed] to seek help (or open a new one). I also recommend you to have a look at my tutorial on TDS Medium.

### Please check my article on TDS for more details: 
https://towardsdatascience.com/how-to-build-your-own-ai-chatbot-on-discord-c6b3468189f4

![Alt Text](https://media.giphy.com/media/hVlYEexgKvttKtqhFx/giphy.gif)

# Overview

# Installation
1. Clone and navigate to chatbot directory.

2. Install the required packages/dependacies.
```
pip install -r requirements.txt
```

3. Run the python server:

To interact with the chatbot directly via cmd/terminal:
```
python main.py 
```
or to interact with the chatbot directly via a simple plateform:
```
python main-host.py
```

4. Open http://127.0.0.1:5000 in your browser if you run the main-host.py file.
