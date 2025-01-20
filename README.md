#<a name="readme-top"></a>

<div align="center">
  <h1><b>CUSTOMER-RETENTION-ECOMMERCE-INDUSTRY </b></h1>
</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- Overview
- [🛠 Built With ](#-built-with-)
- [Tech Stack ](#tech-stack-)
- Packages and Libraries
- Cleaning The Data
- Exploratory Data Analysis
- Visualizations
- Analysis
- Findings
- [Key Insights ](#key-insights-)
- [💻 Getting Started ](#-getting-started-)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Install](#install)
- [Usage](#usage)
- [👥 Authors ](#-authors-)
- [🔭 Future Features ](#-future-features-)
- [🤝 Contributing ](#-contributing-)
- [⭐️ Show your support ](#️-show-your-support-)
- [🙏 Acknowledgments ](#-acknowledgments-)
- [📝 License ](#-license-)

<!-- PROJECT DESCRIPTION -->

#  CUSTOMER-RETENTION-ECOMMERCE-INDUSTRY <a name="about-project"></a>

## Overview 

Customer retention is a critical aspect of the e-commerce industry. In a highly competitive market, retaining existing customers is often more cost-effective than acquiring new ones. Companies need to understand customer behaviors, preferences, and buying patterns to minimize churn and foster loyalty. Customer retention analysis helps identify at-risk customers, improve marketing strategies, and enhance customer experience.

E-commerce businesses face several challenges related to customer retention:

- High Customer Churn Rates
- Lack of Insights
- Increasing Acquisition Costs
- Personalization Challenges
- Market Saturation

## Data Sources 📊
- The dataset was provided in Amdari.io in a CSV format for transparency and reproductibility.


## Topical Questions and Hypotheses
#### Questions 🤔:

ANALYTICAL QUESTIONS
The following analytical questions will help us gain insight and as well as confirm our hypothesis

- Who are the most valuable customers?

- What is the average order size (in terms of quantity) per customer?

- What is the frequency of repeat purchases across customers?

- What are the top-performing products in terms of sales quantity and revenue? Which product categories (based on Description) have the highest revenue and sales quantity?

- What is the revenue trend over time (daily, weekly, or monthly)?

- How does customer behavior differ on weekdays vs. weekends?

- What is the average unit price for each product?

- Which countries generate the highest average revenue per order?

- Which countries have the highest concentration of unique customers?

### Hypotheses 🔬:
#### A significance level (α) of 5% will used to perform all the hypothesis testing

The following hypothesis will be tested

1. The average spending of customers from Mozambique is equal to that of customers from other countries.

2. Lower unit prices do not significantly increase the quantity sold.

'InvoiceNo', 'InvoiceDate', 'CustomerID', 'StockCode', 'Description',
       'Quantity', 'UnitPrice', 'Country'

###Data Dictionary
- InvoiceNo - Uniquely identify each invoice
- InvoiceDate - The time the invoice was issued
- CustomerID - uniquely identifies the customer
- StockCode- identifies the stock code
- Description - identifies what category of the product sold
- Quantity - The number of item sold
- UnitPrice - The unit price of the item sold
- Country - location to which the product were sold



## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>


<details>
<summary>Language</summary>
  <ul>
    <li><a href="https://www.python.org/">Python</a></li>
  </ul>
</details>



## Packages and Libraries 📚
#### Collection of significant Python Libraries:
- Pandas
- Numpy
- Seaborn
- Scipy
- Matplotlib


## Cleaning the Data 🧹
#### We begin by thoroughly cleaning our data.
- Changing data types 
- Dealing with Nan values


## Analysis 🔍
- Utilizing Python and data analysis libraries such as Pandas, Matplotlib, and Seaborn, we performed exploratory data analysis (EDA) to uncover trends and insights.
- We analyzed revenue trends by month, order trends, geographical distribution.


## Key Files 📂
- `Ecommerce.ipynb`: Jupyter Notebook containing the code for data cleaning, EDA, and visualization.
- Raw data used for analysis.
>Dataset_ecommerce.csv
-`README.md`: This file providing an overview of the project.



<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- Features -->

## Key Insights <a name="key-features"></a>

- We noticed that there are no outliers detected in the distribution of quantity and unit price.

- Both quantity and unit price distributions appear symmetrical and bell-shaped, indicating they are approximately normally distributed.

- Côte d’Ivoire recorded the highest number of items purchased, followed by Sierra Leone and Benin, while Mali had the lowest purchase count.

- we also noticed that Sports equipment emerged as the most purchased category, followed by the jewelry section, with the books section having the fewest purchases.

- We observed a positive correlation between quantity and unit price; however, the relationship is not strong.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Python


### Setup

Clone this repository to your desired folder:


```sh
  cd my-folder
  git clone https://github.com/bamzyyyy/CUSTOMER-RETENTION-ECOMMERCE-INDUSTRY
```

Change into the cloned repository

```sh
  cd CUSTOMER-RETENTION-ECOMMERCE-INDUSTRY
  
```

Create a virtual environment

```sh

python -m venv env

```

Activate the virtual environment

```sh
    env/Scripts/activate
```


### Install

Here, you need to recursively install the packages in the `requirements.txt` file using the command below 

```sh
   pip install -r requirements.txt
```



<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

- 🕵🏽‍♀️ **Aminu Oluwarotimi Desmond**                  [GitHub Profile](https://github.com/bamzyyyy?tab=repositories)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

We acknowledge the Amdari team for providing data for me to deliver this real-life project.

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
