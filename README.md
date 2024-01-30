Discord ChatBot with discord.py

Overview:

This Python-based Discord ChatBot utilizes the discord.py library to provide a responsive and customizable experience for Discord server users. The bot is designed to listen to messages, extract user queries, and generate responses based on predefined sets of responses.

Features:

Message Functionality: The bot efficiently analyzes incoming messages, extracts user queries, and generates responses using a modularized approach in the responses.py module.

Private and Public Responses: The bot caters to both private and public responses. Queries starting with a question mark (?) receive private responses, while others get public responses in the respective channels.

Error Handling: Robust error handling is implemented to catch and log any exceptions that may occur during the response generation process, ensuring smooth operation.

Startup Notification: The bot provides a clear startup notification in the console, indicating successful connection and readiness to respond within the Discord server.

Secure Token Management: Enhancing security, the Discord bot token is loaded from environment variables using the dotenv library. This ensures sensitive information remains confidential.

Clean Code Practices: The code adheres to clean coding practices, including the use of type hints, final variables, and meaningful variable names, promoting code readability and maintainability.

How to Use

Create a Discord Bot:
Visit the Discord Developer Portal and create a new application.
Turn the application into a bot and obtain the bot token.
Set up .env file:
Create a .env file in the project directory.
Inside the file, add your Discord bot token using the format DISCORD_TOKEN=your_token_here.

Run the Script:
Execute the script in your preferred Python environment.
The bot will connect to Discord using the provided token and start responding to messages.
Feel free to customize the responses.py module to tailor the bot's behavior to your server's needs.

![image](https://github.com/saqlainshabbir/Discord-Bot/assets/154231070/b104cadf-92fd-4bcb-92e1-b1f084c1def3)
