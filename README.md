# streaming-translated-extension

This project explores the potential of real-time text translation through the use of current available APIs and the AI API from Google Gemini. For an in-depth look at our proposed solutions and ideas, please refer to the `ideas.md` file.

## How to Use the Livestream Transcript and Translation Feature

This section provides guidance on how to utilize the newly integrated livestream transcript and translation feature within the streaming-translated-extension project. The feature leverages the AI API from Google Gemini to provide enhanced translation accuracy in real-time, making it easier for content creators and viewers to engage with livestreams across different languages.

To get started, ensure that you have the latest version of the streaming-translated-extension installed. Follow the setup instructions provided in the `implementation.md` document to integrate the feature into your livestream setup. Once integrated, the feature will automatically transcribe and translate the spoken content in your livestream, displaying the translated text to your viewers in real-time.

For more detailed information on the technical implementation and to view examples of API calls and responses, please refer to the `implementation.md` document.

## Interacting with the Chat Bot through the Web Interface

To enhance your experience with our chat bot, we have introduced a simple HTML web interface, detailed in the file `chat_interface.html`. This interface allows for direct interaction with the chat bot through a user-friendly web page. Additionally, we have now created a JavaScript version of our Python chat functionality, available in the `chat.js` file, which interfaces with the Google Gemini API to replicate the capabilities of our Python script `9.py`.

### How to Use

1. Open the file `chat_interface.html` in a web browser.
2. Enter your message in the text field provided and click the "Send" button to submit your query to the chat bot.
3. The chat bot's response will be displayed directly on the page, allowing for a seamless conversation.

This web interface provides an accessible way to communicate with our chat bot, making it easier for users to engage with and benefit from the bot's capabilities. For an enhanced chat experience, ensure to utilize the `chat.js` file for improved functionality and interaction with the Google Gemini API.
