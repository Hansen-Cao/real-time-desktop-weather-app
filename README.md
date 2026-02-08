# real-time-desktop-weather-app
☀️ Python Weather App

Hey! Thanks for checking out my weather app. I built this to practice working with APIs and creating desktop GUIs with Python. It allows you to search for any city and get real-time weather updates without opening a browser .
🎮 What it Does

    Live Weather Data: Fetches the current temperature and conditions for cities globally .

    Dynamic Emojis: The app automatically updates the visual emoji (like ⛈️ for storms or ❄️ for snow) based on the specific weather ID received from the API .

    Smart Error Handling: If you type a city that doesn't exist (like "Narnia") or lose internet connection, the app tells you exactly what went wrong instead of crashing .

    Custom Styling: I used CSS styling to make the fonts and layout look clean and modern .

🛠️ The Tech Stack

    Python: The brain of the operation.

    PyQt5: Used to build the window, buttons, and text fields .

    OpenWeatherMap API: Where the data comes from .

    Requests: The library that handles the conversation between my app and the weather server .

⚡ How to Run It

    Install the dependencies: You'll need PyQt5 and requests. Run this in your terminal:
    Bash

    pip install requests PyQt5

    Get your API Key:

        Sign up for a free account at OpenWeatherMap.org .

        Go to "My API Keys" and copy your key .

        Heads up: It usually takes about 10-20 minutes for a new key to actually activate, so grab a coffee while you wait .

    Add the Key: Open the code, find the api_key variable, and paste your key inside the quotes .

    Run the App:
    Bash

    python main.py

🧠 What I Learned

Building this helped me understand:

    How to send HTTP requests and handle JSON responses .

    How to handle HTTP status codes (like 404 Not Found or 401 Unauthorized) gracefully .

    How to connect backend logic to a frontend GUI using signals and slots .

Feel free to fork this and add your own features! 🚀
