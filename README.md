# EVSU Chatbot - FAQ-Style Chatbot Interface

This chatbot is designed for Eastern Visayas State University (EVSU) as a dynamic and interactive way to provide answers to frequently asked questions (FAQs). Unlike traditional FAQ pages, this chatbot offers a more engaging user experience by simulating a conversation.

## Features:

- **Interactive UI**: The chatbot interface mimics a real conversation, making it easy for users to ask questions and get instant answers.
- **Keyword-Based Responses**: Users select from a list of predefined keywords, and the chatbot provides relevant responses based on these selections.
- **Response Suggestions**: After each interaction, the chatbot suggests related keywords, guiding users to explore more topics.
- **No Input Required**: Users interact with the chatbot by clicking on keywords, making it simple and intuitive to use, even on mobile devices.

## How It Works:

1. **Select a Keyword**: The user selects a keyword from the list of suggestions.
2. **Receive a Response**: The chatbot fetches the relevant response from the database and displays it.
3. **Explore Further**: The chatbot provides additional keyword suggestions based on the user's query, allowing for further exploration of related topics.

This chatbot aims to enhance the accessibility of information for EVSU students, faculty, and visitors by providing quick and easy access to frequently sought information in a modern and user-friendly way.

## Database Installation

To set up the database for the EVSU Chatbot, follow these steps:

1. **Locate the SQL File**: The SQL file is located inside the `database` folder in the root directory of the project.
2. **Import the Database**:

   - Open your preferred database management tool (e.g., phpMyAdmin, MySQL Workbench).
   - Create a new database named `chat_bot_db`.
   - Import the `chat_bot_db.sql` file located in the `database` folder into the newly created database.

3. **Configure the Application**:
   - Ensure that your database connection settings in the application match the credentials for your database server.
   - The chatbot is now ready to use with the pre-configured database.

By following these steps, the database will be set up, and the chatbot will have access to the necessary tables and data to function properly.
