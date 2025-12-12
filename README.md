responses = {
     "Hi": "Hello! 👋",
  "bay": "Goodbye!",
    "how are you": "I'm just a bot, but I'm fine."
}

while True:
    user = input("You: ").lower()
    if user in responses:
        print("Bot:", responses[user])
    elif user == "exit":
       break 
    else:
        print("Bot: I don't understand.")4
