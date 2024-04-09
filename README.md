def chatbot():
    print("Hello! I'm a simple chatbot. How can I assist you today?")
    user_input = input("User: ")
    if "hello" in user_input.lower():
        print("Chatbot: Hello! How can I help you today?")
    elif "bye" in user_input.lower():
        print("Chatbot: Goodbye! Have a great day!")
    else:
        print("Chatbot: Sorry, I didn't understand that. Can you please rephrase?")

chatbot()
