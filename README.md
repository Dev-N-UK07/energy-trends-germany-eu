#  Germany vs EU Energy Trends (1990–2023)

A data-driven analysis of how Germany's energy consumption has evolved over the past three decades — especially its transition to renewables — in comparison with the EU-27 average. This project explores policy impacts, visualises key energy shifts, and aims to showcase Germany's distinctive path in the European energy landscape.


##  Project Overview

This project analyzes Germany’s energy consumption trends from 1990 to 2023 using Eurostat data. It aims to:

- Understand Germany’s shift from fossil fuels to renewable energy.
- Compare Germany’s energy trends with the EU-27 average.
- Identify how policies like Kyoto, Paris Agreement, Energiewende, and 2022 energy crisis affected these transitions.
- Build compelling visual storytelling using Python and Jupyter.

---

##  Data Source

- **Primary Source**: Eurostat's Energy Balances (https://ec.europa.eu/eurostat/databrowser/view/nrg_bal_c/default/table)  
- **Countries**: Germany, EU-27 (from 2020)  
- **Time Range**: 1990–2023  
- **Energy Balance Indicator**: Gross Inland Consumption (GAE)  
- **Energy Types**: Fossil, Renewables (Bioenergy, Wind, Hydro, Solar), Nuclear, Natural Gas  
- **Unit**: Ktoe (Kilotonne of Oil Equivalent)

---

## 🧰 Tools Used

- **Language**: Python  
- **Notebook Environment**: Jupyter  
- **Libraries**: Pandas, Matplotlib  
- **Version Control**: Git & GitHub  

---

## 🧪 Methodology

1. Loaded raw dataset from Eurostat.
2. Filtered for Germany & EU, 1990–2023, Gross Inland Consumption.
3. Pivoted dataset for energy sources as columns.
4. Created clean comparative plots for:
   - Germany vs EU: Bioenergy vs Solid Fossil Fuels
   - Wind, Hydro, Solar Thermal (both Germany & EU)
   - Total Renewable vs Total Fossil (line & area plots)
5. Annotated plots with policy events (Energiewende, Paris Agreement, etc.)
6. Exported data and visuals for reuse and presentation.

---

## 📸 Visual Highlights

Visuals include:

- 📉 Bioenergy vs Solid Fossil Fuels (Germany & EU)
- 🌬️ Wind Energy Consumption (Germany vs EU)
- 🌊 Hydro Energy Comparison
- ☀️ Solar Thermal Trends
- 📈 Total Renewables vs Fossil (Germany & EU)
- 📝 Annotated charts showing policy impact

All charts saved in `visuals/` folder.

---


##  Sample Visualisations

| Germany: Bioenergy vs Solid Fossil Fuels | EU‑27: Bioenergy vs Solid Fossil Fuels |
|-----------------------------------------|----------------------------------------|
| ![Bio vs Fossil – Germany](notebooks/images/germany_bio_vs_fossil.png) | ![Bio vs Fossil – EU](notebooks/images/eu_bio_vs_fossil.png) |

*(Add your actual plot images here)*

---

## 📌 Key Insights

🟢 Germany has significantly increased its bioenergy and wind usage since 2000s.  
🔴 Solid fossil fuels have sharply declined in Germany — faster than EU average.  
🌬️ Wind energy grew more rapidly in Germany post-2000, signaling strong policy backing.  
💡 Germany’s overall renewable shift is steeper than the EU average.  
🧊 Solar Thermal shows late but steady growth since mid-2000s.  

(*Detailed insights for each chart are added inside the Jupyter notebook.*)

---

## 🏛️ Policy Impact Summary

- **1997 – Kyoto Protocol**: Triggered early awareness on fossil reductions.  
- **2000 – Energiewende Begins**: Marked Germany’s major renewable energy reforms.  
- **2015 – Paris Agreement**: Boosted global and EU-wide renewable commitments.  
- **2022 – Russia-Ukraine War**: Spiked urgency for energy independence → seen in recent trends.

Policy annotations help highlight the cause-effect of real-world events.

---
## 📁 Folder Structure

```
/data/
  germany_energy.csv
  eu_energy.csv

/notebooks/
  germany_vs_eu.ipynb

/visuals/
  *.png (All visual outputs)

README.md
```

---

## ▶️ How to Run

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/energy-trends-germany-eu.git
   cd energy-trends-germany-eu
   ```

2. Install required packages:
   ```bash
   pip install pandas matplotlib jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook
   ```

4. Open `notebooks/germany_vs_eu.ipynb` and run cells in order.

---

## 🚀 Future Work

- Integrate Eurostat API for live data updates
- Expand to include more EU countries
- Analyze per-capita or % share of renewables
- Add animated plots or time series storytelling

---

## 🙌 Credits

- Dataset: [Eurostat – Energy Balances](https://ec.europa.eu/eurostat/databrowser/view/nrg_bal_c/default/table)
- Visual inspiration from EU energy dashboards
- Developed by Devansh Negi
