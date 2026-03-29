# Sky-cast
A modern, visually appealing desktop weather application built with Python and Tkinter that provides real-time weather information for any location worldwide.

✨ Features
1) Real-time Weather Data: Fetches current weather conditions from wttr.in API
2) Beautiful UI: Modern dark theme with animated background elements
3) Comprehensive Weather Info: Displays temperature, humidity, wind speed, pressure, visibility, and more
4) Tomorrow's Forecast: Shows detailed forecast for the next day including sunrise/sunset times
5) Smooth Animations: Loading animations and floating background circles
6) Responsive Design: Scrollable interface to accommodate all weather information
7) User-Friendly: Intuitive search with enter key support and hover effects

📸 Screenshots
Main Interface
The application features a sleek dark theme with animated background elements and easy-to-use search functionality.

Weather Display
1) Current temperature with weather emoji
2) Wind speed and direction
3) Humidity levels
4) Atmospheric pressure, visibility, cloud cover, and precipitation
5) Tomorrow's forecast with sunrise/sunset times

📋 Requirements
1) Python 3.6 or higher
2) Required packages:
      a)  tkinter (usually comes pre-installed with Python)
      b)  requests
   
🚀 Installation
   Step 1: Clone or Download
   git clone https://github.com/yourusername/weather-pro.git 
   cd weather-pro
  Step 2: Install Dependencies
  pip install requests
  Step 3: Run the Application
  python Sky-cast.py
  
💻 Usage
 1) Launch the application
 2)  python Sky-cast.py
 3) Enter a city name in the search box

Examples: "London", "New York", "Tokyo", "Paris"
Search for weather

4) Click the "🔍 Search" button, or
Press Enter key
5) View weather information:

Current temperature and "feels like" temperature🌡️ Temperature: Large display with current and "feels like" temperature
🌤️ Weather Condition: Description with contextual emoji
💨 Wind: Speed (km/h) with direction (compass point and degrees)
💧 Humidity: Current humidity percentage
🔽 Pressure: Atmospheric pressure in millibars
👁️ Visibility: Visibility range in kilometers
☁️ Cloud Cover: Cloud coverage percentage
🌧️ Precipitation: Precipitation amount in millimeters 


Tomorrow's Forecast
📅 Date: Tomorrow's date
🌡️ Temperature Range: Maximum and minimum temperatures
🌤️ Weather Condition: Forecast with emoji
🌅 Sunrise: Tomorrow's sunrise time
🌇 Sunset: Tomorrow's sunset time
🌧️ Rain Chance: Probability of rain
☀️ UV Index: UV index level

 
UI Elements
✨ Animated Background: Floating circles with smooth motion
⏳ Loading Animation: Animated dots while fetching data
🪟 Window Controls: Minimize and close buttons
📜 Scrollable Panel: Accommodates all weather information
🖱️ Hover Effects: Interactive buttons with visual feedback
⚠️ Confirmation Dialog: Prevents accidental closure

🌐 API Information
This application uses the wttr.in API:

Free weather data in JSON format
No API key required
Covers worldwide locations
Provides current conditions and forecasts
 
 API Endpoint Used:

https://wttr.in/{city}?format=j1



📁 Project Structure
weather-pro/
│
├── Sky-cast.py          # Main application file
├── README.md               # This file
└── requirements.txt        # Python dependencies (optional)


🐛 Troubleshooting
1) Issue: City not found
Solution:

Check spelling and try using a more specific location name
Try using city name with country (e.g., "Paris, France")
Ensure the city name is in English

2) Issue: Network error
Solution:

Check your internet connection
Ensure wttr.in is accessible from your location
Check if a firewall is blocking the connection

3) Issue: Slow loading
Solution:

This may be due to network latency
The app will display an error if the request times out after 10 seconds
Try a different network or check your internet speed

4) Issue: Application won't start
Solution:

Ensure Python 3.6+ is installed: python --version
Install required packages: pip install requests
Check if tkinter is installed: python -m tkinter

5) Issue: Scrolling doesn't work
Solution:
Use mouse wheel to scroll through weather information
On trackpad, use two-finger scroll gesture

🔒 Privacy & Security
No user data is collected or stored
All weather data is fetched directly from wttr.in
No API keys or authentication required
Application runs entirely on your local machine

📝 Notes
The application requires an active internet connection to fetch weather data
Weather data is provided by wttr.in and is generally accurate but may occasionally differ from other sources
The application uses threading to prevent UI freezing during data fetching
All temperature values are displayed in Celsius (°C)
Wind speeds are shown in kilometers per hour (km/h)

🚀 Future Enhancements
Potential features for future versions:

 Multiple city weather comparison
 7-day forecast
 Weather alerts and notifications
 Temperature unit toggle (Celsius/Fahrenheit)
 Save favorite locations
 Dark/Light theme toggle
 Export weather data to CSV
 Weather maps integration
 Hourly forecast
 
🤝 Contributing
Contributions are welcome! Here's how you can help:

1) Fork the repository
2) Create a feature branch (git checkout -b feature/AmazingFeature)
3) Commit your changes (git commit -m 'Add some AmazingFeature')
4) Push to the branch (git push origin feature/AmazingFeature)
5) Open a Pull Request

Contribution Guidelines
1) Follow PEP 8 style guidelines
2) Add comments for complex logic
3) Test your changes thoroughly
4) Update README if adding new features

📄 License
This project is open source and available for personal and educational use.

🙏 Acknowledgments
Weather data provided by wttr.in
Built with Python and Tkinter
Inspired by modern weather applications
Thanks to the open-source community

📞 Contact & Support
Issues: Report bugs or request features via GitHub Issues
Questions: Feel free to ask questions in the Discussions section

🌟 Star This Project
If you find this project helpful, please consider giving it a star on GitHub!
