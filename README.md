# SafeMountain

A web application designed to improve outdoor safety by enabling official organizations to create, catalog, and manage hazardous areas on interactive maps.

## 🎯 Project Overview

SafeMountain allows authorized organizations and local authorities to:
- Draw and catalog dangerous zones on interactive maps
- Classify areas by type (avalanche risk, rockfall zones, etc.) and location
- Export geospatial data in GeoJSON format
- Provide hikers and mountaineers with downloadable hazard data for GPS devices

Unlike reactive safety systems that alert only after accidents, SafeMountain focuses on **proactive prevention** by warning users before they enter dangerous areas.

## 🚀 Features

- **Interactive Map Interface**: Built with Leaflet for easy navigation and zone drawing
- **Area Cataloging System**: Organize hazard zones by category, subcategory, and specific area
- **GeoJSON Export**: Export data for use on low-cost GPS devices
- **User-Friendly Design**: Simple interface for both authorities and end users
- **Offline Support**: Data can be cached for use in areas without connectivity

## 🛠️ Technologies Used

- HTML5, JavaScript
- [Leaflet.js](https://leafletjs.com/) - Interactive mapping library
- [Leaflet.draw](https://leaflet.github.io/Leaflet.draw/) - Drawing tools for hazard zones
- OpenStreetMap - Map tile provider
- GeoJSON - Geospatial data format

### Live Demo

🌐 [View Live Demo](https://mat2808.github.io/safemountainmaps/)

## 💡 How It Works

1. **Authorities** access the web app and draw hazard zones on the map
2. They **catalog** each zone with detailed information (type, severity, notes)
3. The system **exports** GeoJSON files to cloud storage
4. **Hikers** download the latest hazard data to their GPS devices
5. Devices provide **real-time alerts** when approaching danger zones

## 🌍 Why SafeMountain?

This project was created in response to serious accidents in my region - one of the greenest in Europe with countless hiking trails. By analyzing recent incidents, I designed a system that could have prevented them through early warnings.

## 📝 Project Status

Currently in development:
- ✅ Web application for hazard zone management
- ✅ Interactive map with drawing tools
- ✅ Cataloging and classification system
- ✅ GeoJSON export functionality
- ✅ Cloud storage integration
- 🔄 Physical GPS device (planned)


## 🤝 Contributing

This is a personal project which I have presented to the MIT Maker Portfolio. Feedback and suggestions are welcome!


## 👤 Author

Matteo Di Muzio
- GitHub: [@Mat2808][(https://github.com/Mat2808/safemountainmaps)]

---

**Note**: This project uses open-source libraries (Leaflet, OpenStreetMap) for mapping functionality. All system architecture, design decisions, and implementation are original work.
