#  Digital Banking Growth After COVID  
**A SQL-Powered Case Study by Prosenjit Majumder**

This project analyzes how digital banking evolved post-COVID using SQL, focusing on user signups, transactions, logins, support requests, and retention.  
It answers 8 real-world business questions based on synthetic datasets across users, transactions, and support data.

---

##  Objective  
To uncover key behavioral shifts and strategic insights in banking by analyzing:
-  Post-COVID digital adoption  
-  Channel usage trends (digital vs. branch)  
-  User engagement and retention  
-  Support preference evolution  

---

##  Business Questions Answered

| # | Business Question |
|---|--------------------|
| 1 | How did user sign-up trends change post-COVID? |
| 2 | Did branch-only users adopt digital channels? |
| 3 | How did monthly transaction volume shift? |
| 4 | What is the share of digital vs. physical transactions? |
| 5 | How consistent is login behavior? |
| 6 | What is the 6-month retention rate after first login? |
| 7 | How did support requests change post-COVID? |
| 8 | Are users shifting from branch to Chat/App support? |

---

##  Dataset Summary

| Table              | Description |
|-------------------|-------------|
| `users`           | 500 rows — signup date, channel, demographics |
| `transactions`    | 3,000 rows — date, amount, channel |
| `logins`          | 1M+ rows — login_date, device_type |
| `support_requests`| 1,500 rows — request type, channel, resolved status |

---

##  SQL Skills Applied

- Complex `JOINs` across behavior tables  
- `CTEs`, `CASE`,`Window` and date functions  
- Time-series analysis  
- Retention calculations  
- Channel segmentation and cohort comparisons  

---

##  Sample Insights

 71% of users signed up post-COVID  
 100% of branch users adopted digital platforms  
 Digital transactions grew from 21% to 45.5%  
 100% of users returned within 6 months  
 Support requests increased post-COVID  
 Branch support saw a rebound in 2024  

---

##  Tools Used

| Tool        | Purpose                             |
|-------------|-------------------------------------|
| SQL         | Data extraction & transformation    |
| Excel       | Tabular insights, calculations      |

---

##  Project Files

| File                              | Description                              |
|-----------------------------------|------------------------------------------|
| `Prosenjit_SQL_DigitalBankingCaseStudy.pdf` | Full case study presentation (designed in Canva) |
| `queries.sql`                     | All SQL queries used in analysis         |
| `summary_table.xlsx`              | Tabular outputs of results (optional)    |

---

##  Thank You

If you found this project insightful, feel free to explore more or connect with me!

**Name:** Prosenjit Majumder  
**Email:** prosenjitmajumder500@email.com  
**LinkedIn:** [linkedin.com/in/prosenjitmajumder](https://linkedin.com/in/prosenjitmajumder)  

