## Basic Weather Web App with Flask and OpenWeatherMap
This is a simple weather web application built with Flask that retrieves weather data from OpenWeatherMap.

### Prerequisites
- Python 3
- Flask
- Requests library

### Setting Up the Project
1. Create a virtual environment:

   ```
   python3 -m venv venv
   source venv/bin/activate
   ```
2. Install Flask and Requests:
   ```
   pip install Flask requests
   ```
3. Project Structure:
    ```python
    weather_app/
        ├── main.py
        ├── requirements.txt
        ├── .gitignore
        ├── .env
        ├── weather.py
        ├── static\styles
            └── style.css
        └── templates/
            ├── index.html
            ├── weather.html
            └── city_not_found.html
                
            
    ```

### API Key
- Create an account on OpenWeatherMap: [https://home.openweathermap.org](https://openweathermap.org/)
- Generate an API key from your account dashboard.

 
      
