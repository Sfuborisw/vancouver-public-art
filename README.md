# 🎨 Vancouver Public Art — Geospatial Data Visualization

An interactive map visualizing the distribution of **747 public artworks** across Vancouver's 22 neighbourhoods, built with Python, Folium, and open data from the City of Vancouver.

---

## 📸 Preview

| Choropleth Map | Artwork Markers |
|---|---|
| Art density by neighbourhood | 747 clustered, clickable markers |

---

## 📊 Dataset Overview

| Property | Details |
|---|---|
| **Source** | [City of Vancouver Open Data Portal](https://opendata.vancouver.ca/explore/dataset/public-art/) |
| **Total Artworks** | 747 |
| **Year Range** | 1901 – 2026 |
| **Neighbourhoods** | 22 Local Areas |
| **Top Neighbourhood** | Downtown (217 artworks) |

### Top Art Types
| Type | Count |
|---|---|
| Sculpture | 186 |
| Two-dimensional artwork | 173 |
| Site-integrated work | 118 |
| Mural | 87 |
| Media work | 45 |

---

## 🗂️ Project Files

```
vancouver-public-art/
│
├── vancouver_public_art_presentation.ipynb   # Main notebook (presentation)
├── public-art.geojson                        # 747 artwork records with coordinates
├── local-area-boundary.geojson               # Vancouver neighbourhood boundaries
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/vancouver-public-art.git
cd vancouver-public-art
```

### 2. Install dependencies
```bash
pip install folium pandas jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook vancouver_public_art_presentation.ipynb
```

### 4. Run all cells
In Jupyter: **Kernel → Restart & Run All**

The final map will render inline in the notebook.

---

## 🗺️ Map Features

- **Choropleth layer** — colour intensity shows art count per neighbourhood
- **Clustered markers** — 747 individual artwork pins that group when zoomed out
- **Interactive popups** — click any marker to see title, year, type, address, and link to the Vancouver Public Art Registry
- **Light basemap** — CartoDB Positron for a clean, presentation-friendly look

---

## 📦 Dependencies

| Package | Purpose |
|---|---|
| `folium` | Interactive map rendering |
| `pandas` | Data cleaning and aggregation |
| `jupyter` | Notebook environment |

---

## 🔑 Key Findings

1. **Downtown dominates** — Over one-quarter of all public art is in the Downtown area
2. **West side vs East side** — Western neighbourhoods (Kitsilano, Fairview, Mount Pleasant) have significantly more art than eastern ones (Killarney, Sunset, Victoria-Fraserview)
3. **Century of art** — Vancouver's public art spans over 100 years (1901–2026)
4. **Sculpture leads** — The most common art type is sculpture (186 pieces), followed by two-dimensional artwork (173)

---

## 📖 Data Sources

| Dataset | URL |
|---|---|
| Public Art Registry | https://opendata.vancouver.ca/explore/dataset/public-art/ |
| Local Area Boundary | https://opendata.vancouver.ca/explore/dataset/local-area-boundary/ |

All data is made available under the [Vancouver Open Data Licence](https://opendata.vancouver.ca/pages/licence/).