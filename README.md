# 🇧🇩 TrainJatri Data – Bangladesh Railway App Resources

Welcome to the official open-data repository for **TrainJatri**, a modern mobile/web application built to track real-time train status in Bangladesh using a hybrid crowdsourcing + map-based GPS approach.

This repository includes:
- ✅ Train schedule files (JSON format)
- ✅ GeoJSON railway route maps
- ✅ Station data (GeoJSON and coordinates)
- ✅ Optional fare information and metadata

## 📁 Folder Structure

trainjatri-data/
├── train_schedules/ # JSON files for each train (with route, timings)
├── railway_paths/ # GeoJSON files of railway routes
├── stations/ # GeoJSON of major and minor stations
├── logo/ # Logo or app branding assets

## 🔍 Sample Files

- `train_schedules/EKOTA_EXPRESS_705.json`: Full schedule including arrival/departure at each station.
- `railway_paths/Biman_Bandar_to_Dewanganj.geojson`: Pathline (coordinates) of route.
- `stations/stations_en.json`: List of all stations with metadata, coordinates, and names in Bangla/English.

## 🔧 Usage

These files power the backend and frontend of the **TrainJatri app**, enabling:
- Real-time train tracking (based on GPS reports)
- Live station arrival confirmation (crowdsourced)
- ETA visualization (progress bar)
- Google Maps or Mapbox railway overlays

## 🛠 Integrations

- 🔁 Supabase (for DB & storage)
- 🌐 Cline AI (for no-code/low-code app build)
- 🗺 Google Maps API / Mapbox GL (for mapping)

## 📘 Licensing & Credits

- All railway line data sourced from **OpenStreetMap**, used under the [ODbL license](https://opendatacommons.org/licenses/odbl/).
- Station and train data collected from publicly available and manually entered sources.
- You are free to use or fork this repo for educational or app-building purposes.

---

Made with ❤️ for Bangladesh 🇧🇩 by TrainJatri Team.
