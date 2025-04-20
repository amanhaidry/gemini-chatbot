# Gemini Chatbot

Gemini Chatbot is a web-based chatbot application built using HTML, CSS, and JavaScript. It provides an interactive interface for users to communicate with a generative language model.

## Features

- **Interactive Chat Interface**: Users can send messages and receive intelligent responses.
- **Light/Dark Theme Toggle**: Switch between light and dark modes for better accessibility.
- **Chat History Persistence**: Chat history is saved in local storage and restored on page reload.
- **Quick Suggestions**: Predefined prompts for easy interaction.
- **Copy Responses**: Copy chatbot responses to the clipboard with a single click.
- **Delete Chat History**: Clear all chat history with a single button click.


## Screenshots

### User Interface
![Screenshot1](screenshots/Screenshot1.png)

### Chat Interface
![Screenshot2](screenshots/Screenshot2.png)

## Technologies Used

- **HTML**: For structuring the chatbot interface.
- **CSS**: For styling the application, including responsive design.
- **JavaScript**: For handling chatbot logic, API integration, and user interactions.

---

# Project Setup Guide

The chatbot uses the Gemini 2.0 Flash API for generating responses. Replace the `API_KEY` in `script.js` with your own API key to enable functionality.

If you encounter an error like "API key not valid. Please pass a valid API key." while chatting with the Gemini, please follow these steps:

## Get Your API Key

1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Navigate to the API key section and create a new API key.

Your API key will look something like this: AIzaSyAtpnKGX13bTgmx0l_gQeatYvdWvY_wOTQ

**Note:** The API is free but has a limited number of usage requests.

## Insert Your API Key

1. Open your project folder in VS Code.
2. Locate to the `script.js` file in your project.
3. Find the `API_KEY` variable and replace `PASTE-YOUR-API-KEY` with your actual API key.

```js
const API_KEY = "YOUR_API_KEY_HERE";
```

## Save and Test

1. Save the `script.js` file after adding your API key.
2. Open` index.html` in your browser to verify that Gemini is working correctly.



## Live Demo

You can test the live version of the Gemini Chatbot here: [Chat Now](#)

---

Happy coding!