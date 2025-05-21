# 🌞 Solar Data Explorer

This repository provides comprehensive code, Jupyter notebooks, visualizations, and an interactive Streamlit dashboard for analyzing and comparing solar irradiance data from **Benin**, **Sierra Leone**, and **Togo**. The main objective is to identify optimal locations for solar energy investment.

---

## 🚀 Interactive Dashboard

Access the interactive dashboard online via Streamlit Cloud:

👉 [Solar Data Explorer Dashboard](https://yosi2020-solar-data-explorer-notebooksmain-w3u8gl.streamlit.app/)

---

## 📂 Project Structure

```
solar-data-explorer/
├── .github/
│   └── workflows/
│       └── unittests.yml
├── .vscode/
│   └── settings.json
├── app/
│   └── main.py                               # Streamlit dashboard application
├── data/
│   ├── benin-malanville-clean.csv
│   ├── sierraleone-bumbuna-clean.csv
│   └── togo-dapaong-clean.csv
├── notebooks/
│   ├── Cross-Country_Comparison.ipynb        # Cross-country comparative analysis
│   ├── Solar_EDA_for_Benin_SierraLeone_Togo.ipynb  # Data profiling & EDA
│   └── README.md                             # Notebook descriptions
├── scripts/
│   ├── README.md                             # Additional scripts documentation (optional)
│   └── __init__.py
├── tests/
│   └── __init__.py                           # Unit tests (optional)
├── .gitignore
├── requirements.txt                          # Python dependencies
└── README.md                                 # (This file)
```

---

## 🛠️ Installation and Setup

Follow these explicit steps to set up and run the project locally:

### **Step 1: Clone the Repository**

```bash
git clone https://github.com/Yosi2020/solar-data-explorer.git
cd solar-data-explorer
```

### **Step 2: Set Up a Python Virtual Environment**

Create and activate your environment explicitly:

```bash
python -m venv venv
```

Activate your virtual environment:

- **On Windows**:
```bash
venv\Scripts\activate
```

- **On macOS/Linux**:
```bash
source venv/bin/activate
```

### **Step 3: Install Python Dependencies**

Install required packages explicitly listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run the Project

### 📓 **Running Jupyter Notebooks**

Launch the Jupyter Notebook server explicitly from the repository root:

```bash
jupyter notebook
```

Then explicitly navigate to `notebooks/` and open the following notebooks:

- **`Solar_EDA_for_Benin_SierraLeone_Togo.ipynb`**  
*(Contains data profiling, cleaning, and exploratory analysis.)*

- **`Cross-Country_Comparison.ipynb`**  
*(Performs cross-country comparisons, statistical analysis, and visualizations.)*

### 📊 **Running the Streamlit Dashboard**

Launch the Streamlit dashboard explicitly:

```bash
streamlit run app/main.py
```

Your dashboard will explicitly launch at: [http://localhost:8501](http://localhost:8501)

---

## ✅ Project Implementation Details

This project explicitly implements:

- **Git and environment setup** (clearly documented steps)
- **Data profiling and cleaning** (explicitly detailed in notebooks)
- **Exploratory Data Analysis (EDA)** (explicit visualizations and clear insights)
- **Cross-country comparative analysis** (explicit statistical tests and results)
- **Interactive Streamlit dashboard** (explicitly built and deployed)

---

## 📈 Analysis Results & Strategic Recommendations

The analysis clearly ranks the solar potential of each country explicitly:

| Rank | Country          | Solar Potential        | Recommendation                             |
|------|------------------|------------------------|--------------------------------------------|
| 1    | **Benin**        | Highest and Stable     | Optimal; prioritize investment             |
| 2    | **Togo**         | Moderate               | Suitable for secondary projects            |
| 3    | **Sierra Leone** | Lowest and Variable    | Proceed with caution; anticipate variability|

---

## 📌 Access Dashboard Online (Streamlit Cloud)

👉 [Solar Data Explorer Dashboard](https://yosi2020-solar-data-explorer-notebooksmain-w3u8gl.streamlit.app/)

---

## 📝 Feedback & Issues

Clearly report any feedback, issues, or suggestions explicitly via:

👉 [GitHub Issues](https://github.com/Yosi2020/solar-data-explorer/issues)

---

## 📚 Project License

This project is explicitly licensed under the **MIT License**.

---

## 🧰 Requirements (`requirements.txt`):

```
pandas
numpy
matplotlib
seaborn
scipy
streamlit
```

---

**Happy Data Exploring! 🌞📊🌍**
