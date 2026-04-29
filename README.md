
# FUTURE_DS_02 CUSTOMER RETENTION AND CHURN ANALYSIS.

DATA SCIENCE AND ANALYTICS TASK 2.

In this task I will be working on customer and subscription data in order to perform a study or an analysis into how certain factors affect the retention of customers and at the end of our study we will be able to understand why customers leave or remain engaged and we will also be able to reduce churn in order to improve revenue.

## Task objectives :
in this project we will use data froman online source(kaggle) which can be accessible through this link [https://www.kaggle.com/datasets/blastchar/telco-customer-churn] so we will use our data to uncover hidden relationships, generate insights and also suggsest logical business recommendations which can help reduce churn 
and improve customer retention. 


## Tools to be used
* we will use pandas and numpy for our dataframes and to load our data into a working environment.
*  We will use jupyter notebook for exploratory data analysis.
*  we will use Seaborn, Matplotlib, and pyplot for ou data visualisation
* Power Bi for our report or live dashboard.
* Github for continous intergration and documentation.

## KEY FINDINGS AND RECOMMENDATIONS.

<details>
<summary><strong>📊 Churn vs Contract Type</strong></summary>

<br>

<p align="center">
  <img src="Data Visualization/churn_by_contract.png" width="600"/>
</p>

---

### 🔍 Findings
- Customers on month-to-month contracts have the highest churn rate  
- Long-term contracts (1–2 years) show strong retention  
- Indicates commitment reduces churn  

---

### 💡 Recommendations
- Introduce incentives for long-term subscriptions  
- Offer discounts for annual plans  
- Improve value perception for short-term users  

</details>

<details>
<summary><strong>📊 Churn vs Payment Method Type</strong></summary>

<br>

<p align="center">
  <img src="Data Visualization/churn_by_payment.png" width="600"/>
</p>

---

### 🔍 Findings
- Customers who use electronic check payment method have a higher churn rate.
- Customers whos uses Mailed Check, Bank Transfer(automatic), and Credit Card (automatic) have the least churn rate compared to Electronic Check.
- Customers who pay using credit card (automatic) have the least churn rate.


---

### 💡 Recommendations
- Discard the use of Electronic Check.
- Reduce paayment methods to mailed check, Bank Transfer, and credit card.
- Introduce monthly discounts fro customers using credit card ths can easily amplify the transition from the other payment methods to the credit card payment method.

</details>


<details>
<summary><strong>📊 Churn vs Tenure </strong></summary>

<br>

<p align="center">
  <img src="Data Visualization/churn_by_tenure.png" width="600"/>
</p>

---

### 🔍 Findings
- Inversely proportional relationship between Tenure and Churn rate which means the increase in tenure(number of years the customer has with us) simply leads to a dicrease in the churn rate.
- Long-term contracts (2-5 years) show strong retention.
- Indicates commitment reduces churn.
---

### 💡 Recommendations
- Introduce penalties for customers who intend to churn in the first two years (Cancelation fee).
- promote the use of long term contacts and offer loyalty rewards.


</details>

<details>
<summary><strong>📊 Churn Rate: Senior vs Non-Senior Type</strong></summary>

<br>

<p align="center">
  <img src="Data Visualization/churn_by_senior.png" width="600"/>
</p>

---

### 🔍 Findings
- Senior citizens  have the highest churn rate(41.7%)  
- Non-Senior citizens have the lowest churn rate which is at (23.6%)

  
---

### 💡 Recommendations
- Introduce educational programs for senior citizens for brtter understanding of how thig=ngs work.
- Senior citizen package:
 * Free TechSupport (normally $10-15/month)
 * Dedicated senior support line
 * Quarterly check-in calls  
 

</details>

<details>
<summary><strong>📊 Churn vs Internet service </strong></summary>

<br>

<p align="center">
  <img src="Data Visualization/churn_by_service.png" width="600"/>
</p>

---

### 🔍 Findings
- Our service analysis reveals a clear pattern: security services retain customers, streaming services attract churn, and fiber optic is our biggest problem. 
- Customers with OnlineSecurity churn at half the rate of those without (20% vs 35%). Yet only 30% of customers have it. 
- Fiber optic customers churn at 42% - our highest risk segment.
- Streaming services increase churn by 5%.Customers who sign up for streaming are more price-sensitive. 

---

### 💡 Recommendations
- Introduce incentives for long-term subscriptions  
- we should use streaming as loyalty rewards, not acquisition hooks [Month 12: Free StreamingMovies for 6 months].  
- Bundling free security services with fiber could cut that churn in half.
- Create mandatory bundle: Fiber optic internet + FREE OnlineSecurity + FREE TechSupport

</details>

## DASHBOARD

PowerBI Dashboard link: https://app.powerbi.com/groups/me/reports/385c0d65-2ee8-4f0e-9401-80e622603c11?ctid=bc5fec91-045a-4917-906e-43922049f31d&pbi_source=linkShare

### General Recommendations.
## 📧 Contact
FOR QUESTIONS OR COLLABORATION:

GitHub: @SupriseMahlalela

Email: mahlalelasuprise57@gmail.com

LinkedIn: Suprise Mahlalela.
