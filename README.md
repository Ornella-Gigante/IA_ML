# WolfTrackr 🐺 - Wildlife Data Analysis Toolkit  

**Unveiling the secrets of wolf subspecies through data-driven insights** 🌍📊  

---

## 📌 Project Overview  
**WolfTrackr** is a comprehensive data analysis project focusing on two wolf subspecies:  
- **Iberian Wolf** (*Canis lupus signatus*) 🇪🇸🇵🇹  
- **Labrador Wolf** (*Canis lupus labradorius*) 🇨🇦  

This Jupyter Notebook-based toolkit explores biological metrics, geographic distribution, and population trends using advanced statistical methods and visualizations.  

---

## 🚀 Key Features  
- **📥 Data Cleaning**: Handles missing values (`NaN`) and normalizes datasets for accurate analysis.  
- **🔍 Exploratory Analysis**: Compares size, weight, and reproductive patterns across subspecies.  
- **📈 Weight Metrics**:  
  - Female Weight Range: 25-35 kg (Iberian) vs. 32-56 kg (Labrador)  
  - Male Weight Range: 36-55 kg (Iberian) vs. 39.7-48.2 kg (Labrador)  
- **🌎 Geographic Insights**: Maps subspecies distribution in Northern Spain, Portugal, and Northern Quebec.  
- **🖼️ Visualizations**: Interactive plots showing size/weight correlations and regional comparisons.  

---

## 🛠️ Installation  

```bash
# Clone the repository
git clone https://github.com/yourusername/WolfTrackr.git

# Install dependencies
pip install jupyter pandas numpy matplotlib seaborn
```

---

## 🧩 Dataset Structure  
| Column | Description | Example Values |  
|--------|-------------|----------------|  
| `Adults_size(inches)` | Shoulder height | 44.4 (Iberian), 224.6 (Labrador) |  
| `Female_Adults_weight(kg)` | Female weight range | 27-32 kg (Iberian) |  
| `location` | Geographic region | Northern Spain, Portugal, Quebec |  
| `mating_time` | Breeding season | "Feb-Mar" (Labrador), "little known" (Iberian) |  

---

## 🎯 Usage  
1. **Launch Jupyter Notebook**:  
   ```bash
   jupyter notebook WolfTrackr_Analysis.ipynb
   ```
2. **Key Analyses**:  
   - Compare subspecies weight distributions:  
     ```python
     df.groupby('Scientific_name')['Male_Adults_weight(kg)'].describe()
     ```
   - Generate location-based heatmaps.  

**Sample Output**:  
Weight Distribution Comparison  

---

## 🤝 How to Contribute  
1. Fork the repository  
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)  
3. Submit a Pull Request  

---

## 📜 License  
Distributed under MIT License. See `LICENSE` for details.  

---

## ✨ Acknowledgements  
- Wildlife conservation datasets from [Global Wolf Initiative](https://example.com)  
- Iconography by [FontAwesome](https://fontawesome.com)  

