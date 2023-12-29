# ChatBot

## Video Demo:  <https://youtu.be/wnsD0LnFENU>

## Description:
a chatbot that can carry out conversations with users using natural language processing.
By using Microsoft DialoGPT, a pre-trained language model that can generate human-like responses to given prompts. and integrating DialoGPT with Flask, a popular Python web framework, to create a web application that can communicate with users via a chat interface.
For the frontend of my application, i will be using HTML, CSS, and JavaScript to create a visually appealing and interactive chat interface.
Additionally, we will be using jQuery (the internet helped me with the JQuery part) to handle the HTTP requests that are made to the backend server.
And lastly i will be using python, specifically Flask framework.
This project consists of the files:
templates:
Has the main HTML file which consists of the main part of the page that has a container that includes the message history of the user and the message history of the bot.
static:
CSS file that has the styling for the chat page and the image of the bot and the image of the user.
app.py:
where i have defined two routes and one function:
route("/"): that has the index funcion that uses the render template of the flask module to render chat.html which is the home page where the convorsation with the bot is carried.
route("/get"): that takes the inputted message and passing it to the function grt_chat response and calling the function at the same time.
the function (get chat response) :
takes the user input as an argument, sends it to the website of Microsoft DialoGPT, then grabs the bot's response and appends both the user's and the bot's messages to the chat history.
and also the text file requirement.txt that has the necessary modules for the app to function, you will need to install them before running this project on your local server.
tahnk you.
## Setup and Usage:
To set up and run the ChatBot project, please follow these steps:

1. Clone the repository if you want to run this project on your local server.
2. Navigate to the project directory which is called chat bot project.
3. Install the required dependencies using pip or manually from the internet.
4. Download the DialoGPT-medium model and tokenizer which are used to initiate the chat bot based on Microsoft's DialoGPT. 
5. Start the Flask server either by running flask run or python app.py in your terminal.
6. Access the ChatBot in your web browser via the link you will get after starting the flask server.
Once the application is running, you can interact with the ChatBot by typing messages in the chat input field and pressing Enter or clicking the send button. The ChatBot will respond with generated text based on the provided input.
do not forget that DialoGPT is a natural language processing model so it can be dumb sometimes.

Feel free to explore and modify the code to customize the behavior and appearance of the ChatBot according to your requirements.
you can change the visuals by editing the style.css file.
but pay attention to not change something that is not supposed to change and intrduce a bug. 
Enjoy conversing with your ChatBot!