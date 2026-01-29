# 🌤️ Weather App

A modern, responsive weather application that provides real-time weather information for any city worldwide. Built with vanilla HTML, CSS, and JavaScript, featuring a beautiful gradient UI and dynamic weather icons.

![Weather App](https://img.shields.io/badge/Status-Complete-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Setup](#api-setup)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## 🔍 Overview

This Weather App is a simple yet elegant web application that allows users to check current weather conditions for any city around the globe. It fetches real-time data from the OpenWeatherMap API and displays it in a visually appealing interface with smooth animations and responsive design.

**Project Details:**
- **Task:** PRODIGY_WD_05 - Weather App with Attractive UI
- **Assigned By:** Prodigy InfoTech
- **Duration:** 01-Feb-2024 to 29-Feb-2024

## ✨ Features

- 🌍 **Real-time Weather Data**: Get current weather information for any city worldwide
- 🎨 **Beautiful UI**: Gradient background design with smooth animations
- 📱 **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- 🌡️ **Comprehensive Info**: Displays temperature, humidity, and wind speed
- 🖼️ **Dynamic Icons**: Weather icons change based on current conditions (Clear, Clouds, Rain, Drizzle, Mist, and more)
- ⚡ **Fast & Lightweight**: Built with vanilla JavaScript - no frameworks required
- ❌ **Error Handling**: Displays user-friendly error messages for invalid city names
- 🔍 **Simple Search**: Easy-to-use search interface with instant results

## 🛠️ Technologies Used

- **HTML5** - Structure and semantic markup
- **CSS3** - Styling, animations, and responsive design
  - Flexbox for layout
  - Media queries for responsiveness
  - Google Fonts (Poppins)
  - Linear gradients
- **JavaScript (ES6+)** - Logic and API integration
  - Async/Await for API calls
  - DOM manipulation
  - Event listeners
- **Fetch API** - HTTP requests to weather service
- **OpenWeatherMap API** - Weather data provider

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sameer-Saleem1/WEATHER_APP.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd WEATHER_APP
   ```

3. **Open the application**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

4. **Access the app**
   - Direct: Open `index.html` in your browser
   - Local server: Navigate to `http://localhost:8000`

## 🚀 Usage

1. **Launch the application** by opening `index.html` in your web browser
2. **Enter a city name** in the search box (e.g., "London", "New York", "Tokyo")
3. **Click the search button** or press Enter
4. **View the weather information** including:
   - Current temperature in Celsius
   - Weather condition with corresponding icon
   - Humidity percentage
   - Wind speed in km/h

### Example Cities to Try:
- London
- New York
- Tokyo
- Paris
- Sydney
- Mumbai

## 🔑 API Setup

This project uses the OpenWeatherMap API. **Important:** You need to obtain your own API key for the application to work properly.

### Getting Your API Key:

1. Visit [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Navigate to your API keys section
4. Generate a new API key
5. Replace the API key in `script.js`:
   ```javascript
   const apiKey = "YOUR_API_KEY_HERE";
   ```

### API Endpoints Used:
- Current Weather Data: `https://api.openweathermap.org/data/2.5/weather`

## 📁 Project Structure

```
WEATHER_APP/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with responsive design
├── script.js           # JavaScript with API integration
├── README.md           # Project documentation
│
└── images/             # Weather icons and assets
    ├── clear.png       # Clear sky icon
    ├── clouds.png      # Cloudy weather icon
    ├── drizzle.png     # Drizzle icon
    ├── rain.png        # Rain icon
    ├── mist.png        # Mist/fog icon
    ├── snow.png        # Snow icon
    ├── humidity.png    # Humidity indicator icon
    ├── wind.png        # Wind indicator icon
    └── search.png      # Search button icon
```

## 📸 Screenshots

### Desktop View
The app features a centered card layout with a beautiful blue gradient background, making it visually appealing on larger screens.

### Mobile View
Fully responsive design that adapts to smaller screens with optimized font sizes and spacing for better mobile experience.

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

### Ideas for Contributions:
- Add more weather conditions and icons
- Implement temperature unit toggle (Celsius/Fahrenheit)
- Add weather forecast for upcoming days
- Include geolocation to auto-detect user's city
- Add search history or favorite cities
- Implement dark/light theme toggle

## 📄 License

This project is open source. Feel free to use it for learning and personal projects.

## 📧 Contact

**Sameer Saleem**
- Email: sameersaleemq75@gmail.com
- GitHub: [@Sameer-Saleem1](https://github.com/Sameer-Saleem1)

Feel free to reach out if you have any questions, suggestions, or feedback!

## 🙏 Acknowledgments

- **Prodigy InfoTech** - For providing the internship opportunity and assigning this project
- **OpenWeatherMap** - For providing the weather API
- **Google Fonts** - For the Poppins font family
- All contributors and users who provide feedback to improve this project

---

⭐ If you found this project helpful, please consider giving it a star!

**Made with ❤️ by Sameer Saleem**
