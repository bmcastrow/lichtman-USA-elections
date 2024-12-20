# ![LichtmanTrumpKamala](https://github.com/bmcastrow/lichtman-USA-elections/blob/main/LichtmanUSA.png)
## 🇺🇸 Data manipulation: U.S. Elections Historical Data (1976-2020) + Allan Lichtman Keys 🇺🇸

## 🗳️ Introduction

With the upcoming 2024 U.S. elections drawing global attention 🌍, the question of who will win the presidency has never been more pressing. This basic project focuses on creating and analyzing a new dataset **(debuting here, not on Kaggle (at least one part of it!))** that combines the **Lichtman Keys 🔑** — a renowned boolean system for predicting presidential election outcomes — with historical data from 1976 to 2020 📊. By doing so, it provides fresh insights that could potentially be used as baseline for future work leveraging ((ML|DL|GenAI), including this year's pivotal race 🏛️. 

🗒️ Note:

Please note that this dataset assumes that each state contributes a certain national level key, which may not strictly reflect the true state-level key contributions. However, due to limitations in available data, it is used a national-level assumption for the keys rather than state-level specifics. This approach serves the purpose of providing a broader national analysis for simulation purposes.

## 🔑 What are the Lichtman Keys?

The **Lichtman Keys** were developed by political historian Allan Lichtman 📚. They are a series of **13 true/false statements** designed to assess the likelihood of the incumbent party 🏛️ retaining the White House. The system has been remarkably and strangely accurate, correctly predicting the outcome of almost every U.S. presidential election.

If **six or more keys turn false**, the challenger party is likely to win the presidency 🎖️, whereas fewer than six suggest the incumbent party will win 🏆.

## 💻 Technologies Used:
- **Python** 🐍 for web scraping, data manipulation, and analysis. 
- **Pandas** for handling datasets and transformations 📊. 
- **BeautifulSoup** for web scraping 🕸️. 

## 📊 Results and Insights ⏳
-**PowerBI** for transformations, visualization reports and insights 🎨📊

## ✍🏻 Notes and future improvements 🔨
-***In the .ipynb script, the vote_percentage column is rounded to zero decimal places. Specifically, in Power BI, this loss of precision impacts the calculation of the DAX measure WinningPartyOriginal, potentially leading to incorrect identification of the winning party in the "filled map" visualization. To correct this issue, you should remove the line of code that performs the rounding.***

-***The data source incorrectly counted boolean keys. This discrepancy was identified during the development of the .pbix file. While no modifications were made to the .ipynb script, the issue was addressed directly in Power BI using the Power Query feature, ensuring accurate key identification in the final visualization.***


