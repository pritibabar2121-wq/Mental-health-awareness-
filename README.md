# Mental-health-awarereness
def get_response(user_input):
    user_input = user_input.lower()

    if "hello" in user_input or "hi" in user_input:
        return "Hi there! How are you feeling today?"

    if "anxious" in user_input or "anxiety" in user_input:
        return ("I'm sorry you're feeling anxious. "
                "Try this breathing technique: Inhale 4s, hold 4s, exhale 4s. "
                "You're not alone. Would you like to see some tips for calming down?")

    if "sad" in user_input or "depressed" in user_input:
        return ("I'm here for you. It’s okay to feel this way. "
                "Remember, talking to a professional can really help. "
                "Here’s a helpline: 1-800-273-TALK")

    if "tips" in user_input or "help" in user_input:
        return ("Here are a few mental wellness tips:\n"
                "1. Get some fresh air\n"
                "2. Practice gratitude\n"
                "3. Stay connected with loved ones\n"
                "Would you like a new tip each day?")

    return "I'm here to listen. Can you tell me more about how you're feeling?"
