GIS Dashboard with Flask & Leaflet 🚀
An interactive GIS Dashboard built using Flask (Python) and Leaflet.js (JavaScript). This project visualizes Indian cities with GeoJSON, interactive popups, and multiple basemaps.
✨ Features
•	⚡ Flask backend for serving templates + static files
•	🗺️ Interactive map powered by Leaflet.js
•	📍 GeoJSON data for Indian cities (Delhi, Mumbai, Kolkata, Bhubaneswar)
•	🎨 Multiple basemaps (Street, Light, Satellite)
•	💬 Popups with city details (capital + population)
•	📂 Clean project structure (ready for GitHub & deployment)
📂 Project Structure
gis-dashboard/
│
├── app.py                # Flask backend
├── requirements.txt      # Python dependencies
├── .gitignore            # Ignore unnecessary files
│
├── templates/
│   └── index.html        # Frontend map (Leaflet + GeoJSON)
│
├── static/
│   ├── style.css         # Custom styling
│   └── cities.geojson    # GeoJSON city data
⚡ Installation & Run
Clone the repository:
git clone https://github.com/<your-username>/gis-dashboard.git
cd gis-dashboard
Create virtual environment (recommended):
python -m venv venv
# Activate:
# Windows → venv\Scripts\activate
# Linux/Mac → source venv/bin/activate
Install dependencies:
pip install -r requirements.txt
Run Flask app:
python app.py
Open in browser: 👉 http://127.0.0.1:5000
📸 Demo Screenshot
(Add screenshot here after running app — index.html map view)
🔮 Future Improvements
•	Add Odisha state polygon boundary
•	Add search bar for cities
•	Integrate charts/graphs with Plotly
•	Deploy to Render / Vercel / Heroku
❤️ Made with
•	[Flask](https://flask.palletsprojects.com/)
•	[Leaflet.js](https://leafletjs.com/)
•	[OpenStreetMap](https://www.openstreetmap.org/)
