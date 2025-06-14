# 🏠 AI Property Underwriting Tool – India 🇮🇳

[![Streamlit App](https://img.shields.io/badge/Deployed%20on-Streamlit-ff4b4b?logo=streamlit&logoColor=white)](https://your-streamlit-deployment-link)

This Streamlit-based tool enables Indian property underwriters to assess location-specific risk using elevation, flood potential, fire exposure, and nearby hazards — and instantly generate a printable PDF summary.

---

## 📸 Screenshots

| Risk Summary Panel | Fire Hotspot Map |
|--------------------|------------------|
| ![Summary](assets/screenshot_summary.png) | ![Map](assets/screenshot_map.png) |

> ℹ️ Add your screenshots in a local `assets/` folder and replace the above images.

---

## 🚀 Features

- 📍 **Elevation & Urban Flood Risk**  
  Get elevation using Open-Elevation API and assess flood sensitivity.

- 🔥 **Borrowed Fire Risk Detection**  
  Scan surroundings for petrol pumps, storage tanks, and flammable structures via OpenStreetMap.

- 🔥 **Live Fire Hotspot Analysis**  
  Fetches real-time fire data from NASA FIRMS (last 24h).

- 🗺️ **Interactive Map**  
  Plot the property and surrounding hazards in one view.

- 📄 **Auto PDF Report**  
  Download a formatted underwriting summary PDF instantly.

---

## 🛠️ Local Setup

1. Clone the repo:
    ```bash
    git clone https://github.com/boxerking/property-underwriter-ai.git
    cd property-underwriter-ai
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

---

## 🌐 Streamlit Cloud Deployment

Easily deploy on [Streamlit Cloud](https://streamlit.io/cloud):

1. Login and connect to GitHub
2. Select this repository
3. Set `app.py` as the main file
4. Click **Deploy**

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-streamlit-deployment-link)

---

## 📂 Project Structure

```
property-underwriter-ai/
├── app.py
├── requirements.txt
├── utils/
│   ├── elevation_utils.py
│   ├── exposure_utils.py
│   ├── fire_utils.py
│   └── pdf_utils.py
└── assets/
    ├── screenshot_summary.png
    └── screenshot_map.png
```

---

## 📢 Disclaimer

This tool is a proof of concept. Data is derived from public APIs and does not replace ground inspections or actuarial analysis.

---

## 👤 Author

Created by [@boxerking](https://github.com/boxerking)  
Contributions and feature requests welcome!