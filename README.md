# basic-chat-bot

def chatbot():
    print("ChatBot: Hello! I'm a simple chatbot. Type 'bye' to exit.")
    
    while True:
        user_input = input("You: ").lower()

        if 'hello' in user_input or 'hi' in user_input:
            print("ChatBot: Hello! How can I help you today?")
        elif 'how are you' in user_input:
            print("ChatBot: I'm just a bunch of code, but I'm doing fine! How about you?")
        elif 'your name' in user_input:
            print("ChatBot: I'm ChatBot, your friendly assistant.")
        elif 'help' in user_input:
            print("ChatBot: I can respond to greetings and simple questions. Try asking something else!")
        elif 'bye' in user_input:
            print("ChatBot: Goodbye! Have a great day 😊")
            break
        else:
            print("ChatBot: I'm not sure how to respond to that.")

# Run the chatbot
chatbot()
