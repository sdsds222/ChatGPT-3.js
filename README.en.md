#### HTML-CHAatGPT-3.js
Software Architecture
Software architecture description

#### Installation
A ChatGPT chat interface written in native JavaScript, based on the openai GPT-3 API interface, with added memory context dialogue, making AI conversations more natural, with special means to prevent it from "talking back" to achieve a similar sustained dialogue effect to the official website ChatGPT. 

Static website:http://sdsds222.gitee.io/chat-gpt.js

![输入图片说明](img/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-02-11%20092124.png)

![输入图片说明](img/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-02-11%20092314.png)

Instructions
oftware architecture description: 
Javascript HTML CSS

#### Installation instructions
1. Clone the full project to the computer
2. Double click the index.html file 
3. Start the browser to run

#### Instructions for use:
1. An openai apikey is required in order to use this page properly.
2. Native JavaScript deployment directly to static web hosting platform.
3. Type "/help" in the input box to view supported commands which can be used to modify parameters to adjust AI behavior:
/help (to view help information)
/apikey (to add prior context to each text sent)
/prompt (to add prior context to each text sent)
/maxtoken (to control the number of words ChatGPT can generate each time.)
/tpr (can be used to control the diversity of speech generated by the chatbot)
/top (can be used to control the quality of speech generated by the chatbot)
/fp (can be used to control the “novelty” of speech generated by the chatbot)
/pp (to control the length of sentences generated by the bot)
/info (to display the current values of various parameters)
/mode (to set whether to enable continuous dialog mode)

After entering /info, the values of all parameters will be displayed:

![输入图片说明](img/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-02-11%20092529.png)

Since the principle of this project to enable continuous dialog is to also send the previous historical dialog content to the GPT-3 interface, it will lead to the wastage of account quota. You can type "/mode" in the console and enter "false" in the input box to turn off continuous dialog mode.

#### Other
Using the prompt parameter to reasonably set the prior context for each sentence can not only maintain consistent tone and character of the AI in the long run, but also ensure that key information is not forgotten by the AI.
Part of the code in this project is generated by ChatGPT.
This document is translated with the assistance of ChatGPT.

#### Contribute
1. Fork this repository
2. Create a Feat_xxx branch
3. Submit code
4. Create a Pull Request