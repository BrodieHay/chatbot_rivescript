# Rivescript Chatbot
Chatbot for Treefrog Consulting implemented with Rivescript-js. The purpose of this bot was to get a better understanding of Rivescript and see if it is the best option when it comes to customer interactions. This bot's brain consists mostly of topic blocks to direct the conversation between the user and the bot in hopes of gathering a list of required information from the user, such as in a customer service situation. 

## How to run
Program is run by entering ``` npm riveshell ./bot ``` from the root directory.
You will them be prompted to start a conversation with the Chatbot. Saying Hello or Hi is a good place to start!
  The biggest weakness of this bot is its predetermined triggers, so please check the begin.rive file to get an idea of what it is expecting to hear from you!
If you would like to stop chatting, enter ``` /quit ```

## Notes
If you would like to see the dialogue options that the user has with the bot, see ``` /bot/brain/begin.rive ```


### Commands to start a conversation
```bash
npm install  
npx riveshell ./bot
```
## External Resources
Rivescript-JS - Documentation and github page here: https://github.com/aichaos/rivescript-js

The Rivescript tutorial I followed here: https://www.rivescript.com/docs/tutorial
