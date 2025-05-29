# Assessing Environmental Drivers of Blue Carbon Storage
This project investigates short-term environmental variability at Station 62149 (West Sole “A” AWS) in the southern North Sea — a region known for active carbon cycling and sediment exchange. The aim is to evaluate how physical conditions such as wind speed, wave height, and air temperature influence carbon storage potential in coastal shelf seas.

Developed as part of MSc coursework in Environmental Data Science and Analytics at the University of Leeds, this project uses the CRISP-DM framework to structure data retrieval, cleaning, exploration, and modelling.

## 🌊 Key Features
- **CRISP-DM Methodology**  
  Structured approach for data science problem solving: understanding, preparation, modelling, and evaluation.

- **Real-Time Data Retrieval**  
  Buoy data imported directly from NOAA using Python's `requests` library.

- **Time Series and Correlation Analysis**  
  Explores interactions between meteorological variables that influence seabed sediment dynamics.

- **Linear Regression and Heatmaps**  
  Applies regression modelling to assess relationships among variables with visual outputs for stakeholder insight.

## 🛠️ Tools and Libraries Used
- Python 3  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Plotly  
- Seaborn  
- Requests (API access)

## 📁 File Structure
blue-carbon-analysis/
├── Assessing_Blue_Carbon_Storage.ipynb # Main analysis notebook
├── README.md # Project overview and instructions


## 🚀 Getting Started
1. Clone or download this repository.
2. Open the `.ipynb` file in a Python environment (Jupyter Notebook or JupyterLab).
3. Run cells sequentially to fetch, clean, and analyse real-time NOAA data.

## 🔍 Insights
- Although no statistically significant correlation was found in the short 48-hour window, the techniques used demonstrate how environmental data can inform coastal carbon storage assessments.
- This type of analysis is critical to understanding disturbance impacts from wind and waves on seabed sediment — a key consideration in marine carbon sequestration policy.
- The structure provides a useful foundation for scaling to larger datasets or longer observation windows.

## 👤 Author
**Hannah Green**  
MSc Environmental Data Science and Analytics  
University of Leeds

## 📜 Acknowledgements
- NOAA National Data Buoy Center: [https://www.ndbc.noaa.gov](https://www.ndbc.noaa.gov)  
- CRISP-DM methodology applied from MSc coursework at the University of Leeds  
- This project was created as a learning and demonstration tool and is not intended for operational marine science use.
