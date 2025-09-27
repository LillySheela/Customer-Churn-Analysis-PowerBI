# Customer-Churn-Analysis-PowerBI

**Project Type:** Data Analysis & Visualization  
**Tools Used:** Power BI, Power Query  
**Dataset:** 7,043 customer records with service usage, contracts, payments, and demographics  

---

## **Project Overview**
This project analyzes customer churn patterns to uncover the key drivers of attrition and identify high-risk segments. Using **Power Query** for data cleaning and **Power BI** for interactive dashboards, the analysis provides actionable insights to improve retention and inform business strategies.

- Total customers: 7,043  
- Churned customers: 1,869 (Churn rate: 26.54%)  
- Focus areas: Service type, contract duration, payment method, internet service, demographics  

---

## **Project Structure**

```
data/                # Dataset files  
powerbi/             # Power BI files & dashboards
insights/            # Final insights & recommendations (PDF)  
```

---

## **Key Insights**

- **Service-wise Churn:** Highest churn in *Online Security* and *Tech Support* services; lower churn in *Phone Service* and *Internet Service*.  
- **Payment Methods:** Electronic check users showed the highest churn (1,071 customers), followed by mailed checks (308) and credit cards (232).  
- **Contract Influence:** Month-to-month contracts had a 42.71% churn rate, compared to 11.27% (1-year) and 2.83% (2-year) contracts.  
- **Internet Service Type:** Fiber optic users faced 41.89% churn versus 18.96% for DSL users.  
- **Demographics:** Customers with dependents and those avoiding paperless billing had lower churn rates, highlighting the importance of personalization.  
- **Customer Profiling:** High-risk segments were identified to enable targeted retention campaigns and service-specific interventions.  

---

## **Actionable Recommendations**

- Implement **retention strategies** for high-risk services (Online Security, Tech Support).  
- Introduce **contract incentives** to convert month-to-month users to longer-term plans.  
- Target **electronic check users** with personalized communication to reduce churn.  
- Use **demographic insights** to design personalized offers for customers with dependents or paperless billing preferences.  
- Monitor churn trends via **interactive Power BI dashboards** to support real-time decision-making.  

---

## **How to Use**

1. Clone the repository:  
```bash
git clone https://github.com/yourusername/Customer-Churn-Analysis.git
```
2. Explore the Power BI dashboard in the powerbi/ folder.

