# Weather Tracker

A simple and interactive **Streamlit** application that allows users to fetch, compare, and download current weather data for multiple cities using the **OpenWeatherMap API**. It includes visualizations, downloadable reports (CSV, TXT, PDF), and clean user interface elements for easy use.

---

## Features

-  Get real-time weather data for one or multiple cities.
-  View temperature comparison graphs.
-  Download weather reports as:
  - CSV
  - TXT
  - PDF (with embedded temperature graph)
-  Streamlit web interface for easy input and display.

---

##  Technologies Used

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [OpenWeatherMap API](https://openweathermap.org/current)
- [Matplotlib](https://matplotlib.org/)
- [FPDF](https://pyfpdf.github.io/)
- [Pandas](https://pandas.pydata.org/)

---

##  How to Run the App

### 1. Clone the repository

```bash
git clone https://github.com/your-username/weather-tracker.git
cd weather-tracker
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
Or manually:



pip install streamlit requests matplotlib pandas fpdf
3. Run the Streamlit app


streamlit run weather_app.py
 Get an OpenWeatherMap API Key
Visit https://openweathermap.org/api

Sign up or log in

Navigate to the API keys section of your account

Copy the API key and paste it into the input field in the app

 Example Usage
Enter your API key in the input field.

Type multiple city names separated by commas (e.g. Cape Town, Durban, Johannesburg)

Click "Get Weather"

View real-time weather data in a table and graph

Download your report in CSV, TXT, or PDF format

 File Structure
weather-tracker/
│
├── weather_app.py           # Main Streamlit app file
├── weather_graph.png        # Graph (auto-generated)
├── README.md                # This file
├── requirements.txt         # Python dependencies

 Acknowledgements
Weather data from OpenWeatherMap

PDF generation via FPDF for Python

Built with love using Streamlit

 Future Enhancements (Ideas)
7-day and hourly forecasts

Weather alert notifications

Air quality and UV index data

Auto-location detection

Mobile-friendly responsive layout

 Author
Mthunzi Malebadi
