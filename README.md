# GDP Growth Dashboard

Run this Dash app to explore GDP per capita trends over time for different countries using the Gapminder dataset.

## Tech Stack
- Python 3.10+
- Dash – for building the web app UI
- Plotly – for interactive charts
- Gunicorn – WSGI HTTP server for deployment
- Render – for cloud deployment
- Pandas – for data handling
- Seaborn – for additional data visualization
- Gapminder Dataset – built-in from Plotly for demo data


## How to Run
1. Make sure you have Python 3.10+ is installed.
2. Install dependencies: `pip install -r requirements.txt`
3. Run `python myapp.py` to launch. 
4. Then open the browser and navigate to: http://localhost:8050

## Features
- Country selection dropdown (default: Canada)
- nteractive line chart showing GDP per capita over the years

## Deployment
This app is deployed on Render.
🔗 Live URL: https://py-asn11-gunicorn-app.onrender.com