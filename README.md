# SAR Displacement Monitoring

This project focuses on monitoring critical infrastructure by detecting ground subsidence using Sentinel-1 Synthetic Aperture Radar (SAR) data. It automates pre-processing, visualization, and displacement rate prediction using Python and Snappy.

---

## 🔍 Overview

Developed as my final year engineering project, this tool:
- Automates SAR data pre-processing using Snappy.
- Displays interactive displacement maps using Leaflet.
- Predicts ground movement trends using time-series modeling.
- Targets early warning for infrastructure risks.

---

## ⚙️ Technologies Used

- Python (Snappy, NumPy, Pandas, Matplotlib)
- Sentinel-1 SAR Data
- Leaflet.js for visualization
- Flask (for the automation interface)
- DEM for terrain validation

---

## 📁 Project Structure

```bash
sar-displacement-monitoring/
├── preprocessing/         # Python scripts using Snappy
├── webapp/                # Flask web app code
├── visualizations/        # Leaflet maps, charts, images
├── data/                  # Example Sentinel-1 and DEM data
├── README.md
└── requirements.txt

