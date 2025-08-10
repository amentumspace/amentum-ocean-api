

# 🌊 Amentum Ocean Data API

[![Landing Page](https://img.shields.io/badge/docs-ocean.amentum.io-blue)](https://amentum.io)
[![OpenAPI Spec](https://img.shields.io/badge/OpenAPI-v3.1-green)](https://ocean.amentum.io)
[![Free Trial](https://img.shields.io/badge/Free_Trial-14_days-brightgreen)](https://developer.amentum.io)

The **Amentum Ocean API** provides real-time and forecasted oceanographic data via a modern REST interface. Access global **currents**, **temperature**, **salinity**, **waves**, and **biogeochemical data** (chlorophyll, nitrate, oxygen, etc.) from trusted models like **RTOFS**, **MFWAM**, and **NEMO**.

## 🚀 Key Features
- 🌐 Global coverage with hourly to daily updates
- 📡 Forecasts up to 5 days ahead
- ⚙️ Simple REST API with JSON responses
- 📍 Precision data by depth, time, and location
- 🔐 Secure access with API keys

## 🧪 Quick Start
```bash
curl -X GET "https://ocean.amentum.io/nemo/bgc?year=2022&month=1&day=1&latitude=11.373&longitude=142.492&depth=10&variable=chl" -H "accept: application/json" -H "API-Key: <your_key>"
```

📚 Explore the Docs

🧭 Full documentation → https://ocean.amentum.io

💡 Use Cases
	•	Vessel routing & fuel optimisation
	•	Fisheries and aquaculture planning
	•	Coastal erosion studies
	•	Weather and wave forecasting
	•	Research and simulation input

📦 Related APIs
	•	Wave Forecast API
	•	Bathymetry API
	•	Biogeochemical Models

⸻

Try the Oceanography Assistant to query data using natural language.

📩 For support or commercial inquiries: contact@amentum.io
