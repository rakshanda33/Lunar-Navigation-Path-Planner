# 🌕 Lunar Navigation Path Planner

This project focuses on identifying safe navigation routes on the Moon’s south pole using topographic and optical datasets from the Chandrayaan missions. The goal is to chart a 100+ meter path for a solar-powered rover, avoiding hazards like craters and boulders, and ensuring optimal sunlight exposure.

## 🚀 Objective

- Plan a rover traverse starting from the landing site near **85.28° S, 31.20° E**
- Ensure the path is at least 100 meters long
- Mark **10+ scientifically interesting stops**
- Avoid obstacles such as steep slopes, shadows, boulders, and craters
- Favor sunlit regions to support the rover’s solar power needs

## 📌 Features

- Annotated map of rover path
- Major lunar features highlighted
- Safe, obstacle-free navigation path
- Stops marked for scientific examination

## 📍 Tools & Technologies

- Python
- Jupyter Notebook
- `rasterio`, `matplotlib`, `numpy`, `shapely`, `geopandas`
- GIS datasets (.tif, .hdf, .nc files)

## 📂 Data Sources

- Chandrayaan mission datasets (to be added)
- DEM and optical imagery of the Moon's south pole

## 🧠 Methodology

1. **Dataset Acquisition & Preprocessing**
2. **Obstacle Detection (Shadows, Craters, Slopes)**
3. **Path Planning Algorithm (A*, Dijkstra, or Custom)**
4. **Mapping & Annotation**
5. **Scientific Stop Selection**

## 🌞 Constraints

- Must consider sunlight availability
- Avoid permanently shadowed regions
- Account for solar-powered rover limitations

## 🖼️ Output

- Annotated map with landing zone, route, and stops
- Detailed explanation of the route selection
- Visual analysis of terrain features

## 📈 Future Improvements

- Real-time path planning using ML
- 3D terrain visualization
- Integration with real rover dynamics

## 📬 Contact

**Rakshanda Noor**  
📧 rakshandanoor20@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rakshanda-noor-9aaa24291/)  

---

> _This project is part of my **Weekly Project Series** where I explore real-world tech challenges and build creative solutions._
