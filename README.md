# 📊 Customer Support Data Analysis – Task 2 (Internship Project)

This project is part of a data analysis internship, aimed at analyzing customer support ticket data to identify common issues, improve service workflows, and enhance customer satisfaction.

## ✅ Task Objective

Analyze customer support tickets to:
- Identify the most frequently reported problems from ticket descriptions.
- Analyze ticket priority, channel usage, and satisfaction ratings.
- Extract keyword patterns from closed tickets.
- Recommend actionable improvements to reduce response and resolution times.

## 🛠️ Tools & Technologies Used

- **Python** (Pandas, Numpy, Matplotlib, Seaborn)
- **NLTK** for text preprocessing and keyword extraction
- **Google Colab** for analysis and visualization
- **CSV Export** and optional WordCloud visualization

## 📁 Dataset Overview

The dataset contains 8,469 support tickets with the following columns:
- `Ticket ID`, `Customer Name`, `Product Purchased`, `Ticket Description`, `Ticket Status`
- `Ticket Priority`, `Ticket Channel`, `First Response Time`, `Resolution`, `Customer Satisfaction Rating`, etc.

## 🔍 Key Analysis Steps

1. **Data Cleaning & Null Handling**  
   Addressed missing values in response times and satisfaction ratings.

2. **Filtering Closed Tickets**  
   Focused on resolved cases for meaningful analysis.

3. **Keyword Extraction with NLTK**  
   Preprocessed ticket descriptions to extract common keywords.

4. **Summary Table & WordCloud**  
   Created a keyword frequency summary and visualized common issues using WordCloud.

5. **Insightful Conclusion**  
   Highlighted major trends and recommended process improvements.

## 📌 Key Findings

| Keyword Group                  | Frequency | Insight                                                       |
|-------------------------------|-----------|---------------------------------------------------------------|
| issue, problem, unable, resolve | High      | Customers frequently face functional difficulties.            |
| please, assist, update         | High      | Many request help or report outdated systems.                 |
| product, device, software      | High      | Issues are tied to specific tools or technologies.            |
| account, data, time            | Moderate  | Access, privacy, and delay-related issues are common.         |
| step, noticed                  | Notable   | Customers describe anomalies or troubleshooting attempts.     |

## ✅ Conclusion

Customer support teams can benefit from:
- Automating common queries using chatbots.
- Prioritizing tickets based on text-driven trends.
- Improving product documentation to reduce repeat issues.

This analysis can guide business decisions to enhance customer support and build long-term loyalty.

---

## 📂 File Structure

