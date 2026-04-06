# 🛒 Market Basket Analysis (SE 412)

This project performs **Market Basket Analysis** using the Apriori algorithm in R to discover patterns in transaction data as part of the SE 412 Software Engineering class.

---

## 📌 Objective

The goal of this project is to:

* Identify frequently purchased item combinations
* Generate association rules using the Apriori algorithm
* Compare purchasing patterns across different datasets (France vs Other regions)

---

## 🧰 Tools & Technologies

* **R**
* `arules` (for association rule mining)
* `arulesViz` (for visualization)
* `tidyverse`

---

## 📊 Dataset

The project uses transaction data from multiple sources:

* `transactions_basket.csv`
* `france_basket.csv`
* `other_basket.csv`
* `Assignment-1_Data.csv`

These datasets represent customer purchase behavior and are used to analyze item co-occurrence.

---

## ⚙️ Methodology

1. Data preprocessing and transformation into transaction format
2. Frequent itemset generation using Apriori
3. Rule generation based on:

   * Support
   * Confidence
   * Lift
4. Visualization of association rules
5. Comparison between France and other regions

---

## 📈 Key Insights

* Certain items frequently appear together in transactions
* Strong association rules highlight customer purchasing patterns
* Differences exist between regional buying behaviors (France vs others)

---

## 📄 Output

The full analysis and results can be viewed here:
👉 **[View HTML Report](market_basket_analysis.html)**

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/market-basket-analysis.git
   ```

2. Open the `.Rmd` file in RStudio

3. Install required packages:

   ```r
   install.packages(c("arules", "arulesViz", "tidyverse"))
   ```

4. Knit the file to HTML

---

