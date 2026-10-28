# Personal Portfolio Website with AI Chatbot

## About the Project

This project is a personal portfolio website designed to showcase personal information, skills, and projects. It includes interactive features such as a dark/light mode toggle, a weather application, and an AI-powered chatbot.

The website combines frontend web development with API integration to provide an interactive user experience.

## Features

- **Personal Portfolio:** Presents personal information and showcases projects.
- **Dark/Light Mode:** Allows users to switch between dark and light themes.
- **Weather Application:** Fetches current weather information for a city using the OpenWeatherMap API.
- **AI Chatbot:** Provides AI-generated responses to questions about web development, APIs, and projects.
- **Input Validation:** Checks whether a city name or chat message has been entered.
- **Error Handling:** Displays messages when weather data or AI responses cannot be retrieved.
- **Interactive Interface:** Uses JavaScript event listeners to respond to user actions.

## Technologies Used

- HTML — Website structure
- CSS — Styling and visual presentation
- JavaScript — Interactive functionality and API requests
- OpenWeatherMap API — Weather information
- Groq-compatible Chat Completions API — AI chatbot responses

## How It Works

### 1. Theme Toggle

The theme button switches the website between dark and light modes by toggling a CSS class on the page.

### 2. Weather Application

Users enter a city name, and JavaScript sends a request to the OpenWeatherMap API. The application displays the city's name, temperature in Celsius, and weather conditions.

### 3. AI Chatbot

Users enter a question and receive an AI-generated response. The chatbot sends a request to a chat completions API and displays the returned answer. It also handles errors such as rate limits and connectivity problems.

## Project Structure

The exact file structure may vary depending on the complete project.

```text
personal-portfolio/
├── index.html
├── style.css
├── script.js
├── chatbot.js
├── README.md
└── assets/
```

## How to Run

1. Download or clone the project repository.
2. Open the project folder in a code editor.
3. Configure the required API services securely.
4. Open `index.html` using a local development server.
5. Test the theme toggle, weather application, and AI chatbot.

The chatbot requires valid API configuration and internet connectivity. Its API integration should be handled through a secure backend before public deployment.

## Security

- Never commit API keys, passwords, or secret environment files to a public repository.
- Keep private AI API keys on the server, not in frontend JavaScript.
- Restrict and monitor API usage to avoid unauthorized requests.
- Rotate any API key that has already been exposed.

## Future Improvements

- Improve mobile responsiveness and accessibility.
- Add more project details and links to project repositories.
- Improve chatbot responses using accurate portfolio information.
- Add secure backend API integration.

## Author

**Janhavi**

second-year Computer Science and Engineering student.

## License

This project is intended for educational and personal portfolio purposes.&#x20;
