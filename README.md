# 🇮🇳 Renewable Energy Dataset: India (State-wise, Yearly)

This open-source dataset provides comprehensive, state-wise data on renewable energy installations across India over multiple years. It includes capacity data (in megawatts) for various energy sources along with economic and demographic indicators like GSDP and population, enabling rich analysis of India’s clean energy landscape.

Some missing values in the dataset have been predicted using the **XGBoost (XGB) Regression** model, ensuring greater continuity and enabling robust time-series or ML-based analysis.

---

## 📦 Dataset Overview

| Column Name       | Description                                       |
| ----------------- | ------------------------------------------------- |
| `State`           | Name of the Indian state or union territory       |
| `Year`            | Year of observation (e.g., 2018, 2019, 2020, ...) |
| `GSDP`            | Gross State Domestic Product (in ₹ Crores)        |
| `Population`      | Estimated population of the state in that year    |
| `Solar`           | Installed solar capacity (in Megawatts)           |
| `Wind`            | Installed wind energy capacity (in Megawatts)     |
| `Small Hydro`     | Installed small hydro capacity (in Megawatts)     |
| `Biomass`         | Installed biomass energy capacity (in Megawatts)  |
| `Waste to Energy` | Installed waste-to-energy capacity (in Megawatts) |

---

## 📊 Potential Use Cases

* Analyze trends in renewable energy deployment across states
* Study the relationship between renewable energy and economic indicators like GSDP
* Benchmark per capita and per-GSDP clean energy growth
* Develop ML models for forecasting or policy analysis
* Create data visualizations for advocacy or awareness

---

## 📂 Repository Structure

```
renewable-india-dataset/
├── data/
│   └── renewable_energy_india.csv
├── notebooks/
│   └── explore_dataset.ipynb
├── LICENSE
└── README.md
```

---

## 🌐 Data Sources

* Ministry of New and Renewable Energy (MNRE)
* State Government Economic Surveys
* Census of India
* RBI & Planning Commission (GSDP data)

---

## 🔖 License

This dataset is released under the **MIT License**. You are free to use, share, and modify it, with attribution.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, open issues, or submit pull requests to improve the dataset, add notebooks, or fix bugs.

If you're working on a project using this dataset and would like help, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/chris-jaimy-antony).


---

## 🚀 About

Created and maintained by [Chris Jaimy Antony](https://www.linkedin.com/in/chris-jaimy-antony) with the aim of democratizing access to clean energy data and enabling better analysis for sustainability research and policy.
