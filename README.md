🌍 GeoNexus

GeoNexus is a lightweight web-based route planner built with Leaflet.js, Leaflet Routing Machine, and OpenStreetMap. It allows users to search for an origin and destination by name, automatically geocodes the locations using the Nominatim API, and displays the shortest driving route on an interactive map.

⸻

✨ Features

* 🗺️ Interactive OpenStreetMap map
* 📍 Search locations by name
* 🚗 Automatic route calculation
* 🔄 Drag route to recalculate in real time
* ⚡ No backend required
* 📱 Responsive interface
* 🌐 Uses free OpenStreetMap services

⸻

🛠️ Technologies

* HTML5
* CSS3
* JavaScript (ES6)
* Leaflet.js
* Leaflet Routing Machine
* OpenStreetMap
* Nominatim Geocoding API

⸻

📂 Project Structure

GeoNexus/
│
├── index.html
└── README.md

⸻

🚀 Getting Started

Clone the repository

git clone https://github.com/yourusername/geonexus.git

Open the project

Simply open index.html in your web browser.

Or use a local server:

python -m http.server

Then visit:

http://localhost:8000

⸻

📖 How to Use

1. Enter an Origin location.
2. Enter a Destination location.
3. Click Get Route.
4. GeoNexus will:
    * Convert both addresses into GPS coordinates.
    * Calculate the best driving route.
    * Display the route on the map.
5. Drag the route to customize it.

⸻

🌐 APIs Used

OpenStreetMap

Provides free map tiles.

https://tile.openstreetmap.org

Nominatim

Used for converting addresses into geographic coordinates.

https://nominatim.openstreetmap.org/search

Leaflet Routing Machine

Calculates routes between waypoints.

⸻

📸 Screenshot

Add a screenshot here after running the project.

/images/screenshot.png

Example:

![GeoNexus Screenshot](images/screenshot.png)

⸻

⚠️ Limitations

* Internet connection is required.
* Depends on free OpenStreetMap services.
* Nominatim has usage limits and should not be heavily queried in production.
* Routing quality depends on OpenStreetMap data.

⸻

💡 Future Improvements

* 📍 Use browser geolocation
* ⭐ Save favorite locations
* 🧭 Multiple travel modes
* 🌙 Dark mode
* 📱 Mobile-friendly UI
* 🛰️ Satellite map layer
* 📏 Distance and travel time display
* 🔍 Route search history
* 🏁 Multiple waypoints
* 🌎 Offline map support

⸻

🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.

git checkout -b feature/new-feature

3. Commit your changes.

git commit -m "Add new feature"

4. Push to your branch.

git push origin feature/new-feature

5. Open a Pull Request.

⸻

📄 License

This project is licensed under the MIT License.

⸻

🙏 Acknowledgements

* OpenStreetMap Contributors
* Leaflet.js
* Leaflet Routing Machine
* Nominatim

⸻

👨‍💻 Author

Created with ❤️ using HTML, CSS, JavaScript, and Leaflet.
