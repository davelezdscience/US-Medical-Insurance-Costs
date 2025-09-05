# 🏥 U.S. Medical Insurance Costs – Data Analysis  

This project explores the **U.S. medical insurance dataset** (`insurance.csv`) using **Python** fundamentals.  
The goal is to extract meaningful insights about patients, such as average age, smoking habits, yearly medical charges, gender distribution, and geographical regions.  

---

## 📊 Project Objectives  

✔️ Import and organize data from a CSV file.  
✔️ Explore dataset columns: age, sex, BMI, children, region, smoking status, and insurance charges.  
✔️ Build a Python class to:  
- Calculate the **average patient age**.  
- Analyze **male vs. female distribution**.  
- Identify **geographical regions**.  
- Calculate **average yearly medical charges**.  
- Find the **average number of children per patient**.  
- Compare **smokers vs. non-smokers**.  
- Create a **dictionary with complete patient information**.  

---

## 📂 Repository Structure  

```
📁 insurance-analysis
│── insurance.csv        # Dataset (not included due to licensing, use your own copy)
│── main.py              # Main script with the analysis
│── README.md            # This file
```

---

## 🛠️ Technologies Used  

- **Python 3.9+**  
- Standard libraries only:  
  - `csv` (for handling CSV files)  

No additional dependencies required.  

---

## ▶️ How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/insurance-analysis.git
   cd insurance-analysis
   ```
2. Make sure the file **insurance.csv** is in the same folder as `main.py`.  
   (Dataset available on [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)).  

3. Run the script:  
   ```bash
   python main.py
   ```

---

## 📈 Example Results  

When running the analysis, you will get results such as:  

- **Average patient age:** `39.21 years`  
- **Smokers vs. non-smokers:**  
  ```
  Count for smokers: 274
  Count for non-smokers: 1064
  ```
- **Average yearly medical charges:** `13270.42 USD`  
- **Regions included:** `['southwest', 'southeast', 'northwest', 'northeast']`  

---

## 🧩 Future Improvements  

- Add **data visualizations** with `matplotlib` or `seaborn`.  
- Perform **statistical analysis** (correlation between BMI, age, and charges).  
- Export results to **Excel or PDF reports**.  

---

## ✨ Author  

👤 **Daniel Vélez**  
📌 Portfolio project – Python data analysis.  
