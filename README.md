# A Healthcare Access & Density Visualization Web App

This Web App is a modern web application that visualizes the distribution and accessibility of healthcare facilities across Munich. It combines interactive maps, statistical data, and real-time analysis tools to inform citizens, researchers, and policymakers about healthcare density, proximity, and service gaps.

## Tech Stack
<p align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="50" height="50" alt="HTML5"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="50" height="50" alt="CSS3"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50" height="50" alt="JavaScript"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="50" height="50" alt="React"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/d3js/d3js-original.svg" width="50" height="50" alt="D3.js"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="50" height="50" alt="Bootstrap"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="50" height="50" alt="Python"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" width="50" height="50" alt="Django"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" width="50" height="50" alt="Jupyter Notebook"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" width="50" height="50" alt="SQLite"/> </p>

## 🚀 Features

- 📍 **Interactive Map**: Displays pharmacies, hospitals, and doctors with district-wise filters.
- 📊 **Statistical Insights**: Visualizes population-to-facility ratios across time (2010–2022).
- 🏥 **Nearest Hospital Info**: Dynamically calculates and displays the nearest healthcare center.
- 🌗 **Map Themes**: Toggle between light, dark, and normal themes for better readability.
- 📅 **Time Slider**: Explore historical data over a timeline.
- 📈 **Data Analysis**: Integrated tools to analyze healthcare density trends in Munich.


- **Mapping**:
  - Leaflet.js / OpenStreetMap for geolocation
  - GeoJSON for district borders

## 📍 Example View

- OCM Orthopädische Chirurgie München marked with detailed location
- --> In the Background my current location is fetched and the nearest hospital is calcualted and displayed
- District-wise breakdown of pharmacies per resident
- Dark and light visualizations for user preferences

## Example Videos
<p align="center">
  <img src="./Images/homepage.gif"  alt="Homepage demo"  width="600"/><br/>
  <em>🏠 Homepage – animated overview</em>
</p>

<p align="center">
  <img src="./Images/mappage.gif"   alt="Map page demo"  width="600"/><br/>
  <em>🗺️ Interactive Map – facility density & nearest hospital</em>
</p>

<p align="center">
  <img src="./Images/analysepage.gif"  alt="Analysis page demo"  width="600"/><br/>
  <em>📊 Analysis – time-slider & district statistics</em>
</p>

<p align="center">
  <img src="./Images/contact.gif"   alt="Contact page demo"  width="600"/><br/>
  <em>📞 Contact – get in touch / feedback form</em>
</p>


## 📊 Data Sources

- Public health data from Stadt München
- GeoData for districts and healthcare facility coordinates
- Analysis based on year 2022 with comparison back to 2010
  
## Preview
```sh
git clone "https://github.com/getintogit1/Healthcare-Access-Platform.git"
cd HealthHubMunich
cd code
pip install -r requirements.txt
cd website_code
python manage.py runserver
```



