# Mini_ChatBot
simple chatbot that interacts with users and fetches information from Wikipedia based on the user's input.
step1:-
Importing the Wikipedia Library: The code imports the wikipedia library, which allows access to Wikipedia's API for retrieving information.
step2:-
Define the talk() function: This function starts the chatbot interaction. It begins by printing a welcoming message.
step3:-
Chat Loop:
Inside a while True loop, the chatbot awaits human input.
The user's input is saved in the user_input variable.
If the user types "exit" (case insensitive), the loop ends and the chatbot says farewell.

step4:-
Obtaining Information from Wikipedia:
The code uses wikipedia.page(user_input) to search for the user's input as a Wikipedia page.
If the page is discovered, the chatbot displays a summary of the Wikipedia page.

step5:-
Handling Exceptions: If a user's input results in a disambiguation error (many possibilities), the chatbot prompts them to be more precise.
If the user's input does not match any Wikipedia article, the chatbot notifies them that it was unable to retrieve any information and suggests they try an other topic.

Step6:-
Main Section:
The chat() method is called in the main body of the code using the if __name__ == "__main__":.

conclusion:-
Overall, this code generates a rudimentary chatbot that communicates with people, retrieves information from Wikipedia, and gracefully handles typical mistakes. Users may question the chatbot about a variety of topics, and it will try to deliver relevant information from Wikipedia.

