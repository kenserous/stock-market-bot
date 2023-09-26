# **Creating a Machine Learning Model to Predict Stock Prices**

## **DISCLAIMER:**
**This project is created fully for informational and educational purposes. Predicting the stock market price is a highly complex task that involves great financial risks, and past performance is not indicative of future results. Please consult a qualified financial advisor before making any form of investment decisions, and I strongly discourage you from using my machine learning model as a basis for your financial decisions. All data gathered for this project's use is obtained from open-source websites, and no information used in this project is obtained through unauthorized means.**

## **Background**
The stock market has always been a fascinating topic to me, because its volatile environment acts as a double-edged sword, which has led to great financial losses for many, yet at the same time led to substantial gains for others. This project is based on the company Microsoft (NSDQ: MSFT). Microsoft is a technology giant found in 1975 by Bill Gates and Paul Allen. Microsoft is renowned for its software products, which includes the Windows operating system (OS) and the Microsoft Office suite among many others. Recently, Microsoft has dipped its toes in cloud computing with Azure, as well as artifical intelligence through significant investments in OpenAI. It is one of the world's most valuable companies, and is currently headed by CEO Satya Nadella.

## **Project Aim**
This project aims to create a machine learning algorithm that is capable of predicting stock market prices accurately, in order to minimise the financial risks of investing in the stock market and maximising profits. In this particular case, we will be attempting to predict the price movement of Microsoft. 
### **Approach**
This project consists of three phases:
1. Data Collection - gathering all forms of information that potentially can influence the stock price of Microsoft, such as market indices and economic indicators.
     - In this case, two datasets are required: the *training set,* the dataset where our model will learn from, and the *testing set*, used to test our model's performance.
2. Modeling - selecting the best machine learning algorithms and tuning them to obtain the best possible model

## **Files**
There are several files in this repository:
1. Three Jupyter notebook files:
   - **training_collection.ipynb**, where information is collected for the *training set*
   - **testing_collection.ipynb**, where information is gathered for the *testing set*
   - **bot.ipynb**, where the machine learning algorithm is developed and tested
2. Four CSV files located in the **data** folder:
   - **CPI_USA_Monthly.csv:** data on monthly inflation rate in the United States
   - **GDP_USA_Quarterly.csv:** data on quarterly GDP growth rate in the United States
   - **MSFT_data.csv and MSFT_data_test.csv:** the final training and testing datasets for the machine learning model
3. Three Excel files located in the **data** folder:
   - **FinancialStatementFY23Q3.xlsx:** financial statement of Microsoft up to FY2023 Quarter 3
   - **QuarterlyCashFlowStatementFY23_Modified.xlsx:** quarterly cash flow statement of Microsoft up to FY2023, obtained from the above Excel financial statement
   - **QuarterlyIncomeStatementsFY23_Modified.xlsx:** quarterly income statement of Microsoft up to FY2023, obtained from the above Excel financial statement

## **Blog Post**
The project is outlined in my blog post, in the Medium link I posted below. The Medium link also contains all of the sources used for this projecct.
(link here)
