## **Trader Behaviour vs Market Sentiment Analysis**



People keep pointing out how trader behavior analysis just looks at the way folks buy and sell stuff in the markets. Market sentiment analysis goes broader though. It checks out the general mood and emotions from all the investors lumped together.



This project kind of ties those two things in. It looks at trader actions and how they link up with market feelings. The focus stays on those Fear and Greed patterns. All from the same set of market data and trading logs.





##### **Project structure**

ds\_Gudala\_Bharath\_Reddy/

├── notebook\_1.ipynb          # Main Colab notebook for code, analysis, visualizations

├── ds\_report.pdf             # Final report summarizing insights

├── csv\_files/                # Contains all data and processed outputs as CSVs

│   ├── aggregated\_metrics.csv

│   ├── merged\_trader\_sentiment.csv

│   ├── historical\_data.csv

│   └── fear\_greed\_index.csv

├── outputs/                  # All visual outputs and charts (PNG)

│   ├── trader\_profitability\_boxplot.png

│   ├── market\_sentiment\_trend\_over\_time.png

│   ├── distribution\_of\_closed\_PnL\_Market.png

│   ├── distribution\_fear\_greed\_index.png

│   ├── distribution\_closed\_Market\_proxy\_risk.png

│   ├── correlation\_matrix\_trader\_metrics.png

│   ├── average\_pnl\_by\_sentiment\_over\_time.png

│   └── average\_daily\_pnl\_over\_time.png

├── README.md







##### **Quick Start**



###### **Colab Notebook:** Open notebook\_1.ipynb in Google Colab for step-by-step code, data workflow, and all analyses.



###### **Data Files:** Place all CSV files in *csv\_files/*. These are required for running the notebook.



###### **Outputs:** All image results from Exploratory Data Analysis (EDA), charts, and final figures are saved in *outputs/*.



###### **Summary Report:** For concise project insights, findings, and explanations, refer to *ds\_report.pdf*.



##### **How It Works**

* ###### **Data Preparation:** Loads and merges market sentiment data and trader metrics.
* ###### **Analysis:** Explores closed PnL distribution, sentiment trends, correlation of metrics, and risk proxies.
* ###### **Visualization:** Generates boxplots, time series of sentiment and profitability, and correlation matrices.
* ###### **Reporting:** Insights and key results are summarized in the PDF report.



Colab notebook link for this project:

[Open in Google Colab](https://colab.research.google.com/drive/1aOgyhcfOdpHW-6La0LIL1Wcjubl8EHKu?usp=sharing)

##### **Dependencies**



All code runs on Google Colab with the following libraries:



* pandas
* numpy
* matplotlib, seaborn
* scikit-learn



##### **Usage Notes**

* All output charts are automatically saved to the *outputs* folder.
* CSVs in *csv\_files* include raw data, merged datasets, and aggregated results for transparency and reproducibility.
* The project is fully documented in the notebook and final report.



##### **Project Author**

* Gudala Bharath Reddy
* bharathgudalareddy@gmail.com



For any issues, please contact via email or raise a pull request.



\[README generated September 2025]

