# Beyond Just Hosting: Airbnb Superhost Success Analysis (Queenstown, NZ)

This project analyses the key factors that drive Airbnb Superhost status in Queenstown, New Zealand — one of the country’s most competitive short-term rental markets.  
Using a combination of statistical modelling, text analysis, and segmentation, the project provides actionable insights to help hosts improve performance, guest satisfaction, and market positioning.

---

## 🎯 Project Objective
Queenstown has one of the highest proportions of Airbnb Superhosts in New Zealand, making it a highly competitive environment for regular hosts.  
The objective of this project is to answer the core business question:

**How can regular Airbnb hosts improve their likelihood of achieving and maintaining Superhost status?**

To address this, the analysis focuses on three key dimensions:
1. Operational and listing factors influencing Superhost eligibility  
2. Guest sentiment and satisfaction drivers based on review text  
3. Market segmentation of Superhost listings based on pricing and demand patterns  

---

## 📊 Analytical Approach
The project integrates multiple analytical techniques to generate comprehensive insights:

- **Logistic Regression** — to identify which host and listing attributes significantly affect the probability of achieving Superhost status  
- **Sentiment Analysis** — to uncover what guests value most in Airbnb stays using English and Chinese guest reviews  
- **Clustering Analysis** — to segment Superhost listings into distinct market personas based on price, capacity, and demand  

This multi-method approach enables both **predictive insights** and **strategic interpretation**.

---

## 🔍 Key Insights

### Superhost Drivers (Logistic Regression)
- Enabling **Instant Booking** significantly increases the likelihood of achieving Superhost status  
- Higher **response and acceptance rates** are strong positive predictors  
- Listings with more **amenities** and stronger **review volume × rating** performance have higher odds of success  
- Managing too many listings and high future availability negatively impact Superhost probability  

### Guest Priorities (Sentiment Analysis)
- **Cleanliness, host responsiveness, location, and comfort** are the most frequently cited drivers of positive reviews  
- Chinese guests place greater emphasis on **kitchen facilities, breakfast options, balconies, and scenic views**, highlighting cultural preference differences  
- Adequate heating and warmth are particularly important due to Queenstown’s climate  

### Market Segmentation (Clustering Analysis)
Three distinct Superhost listing segments were identified:
- **Budget Stay** — private rooms with low prices and high turnover  
- **Comfort Homes** — mid-range entire homes balancing affordability and demand  
- **Luxury Escape** — premium properties with higher prices and lower booking frequency  

Each segment requires different pricing, marketing, and guest engagement strategies.

---

## 💡 Business Recommendations
Based on the findings, the project recommends that hosts:

- Enable **Instant Booking** to improve visibility and booking efficiency  
- Maintain consistently high **response and acceptance rates**  
- Prioritise **cleanliness and accurate listings** to manage guest expectations  
- Apply **dynamic pricing strategies** based on demand and listing type  
- Tailor offerings to different guest segments and cultural preferences  
- Actively manage reviews to sustain long-term Superhost status  

---

## 🧱 Project Structure
- `analysis.qmd` — Data analysis and modelling workflow  
- `presentation.pptx` — Final stakeholder-facing presentation  
- `README.md` — Project overview and insights  

---

## 🛠 Tools & Technologies
- R / Quarto  
- Logistic Regression  
- Text & Sentiment Analysis  
- K-Means Clustering  
- Data Visualisation  

---

## 📚 Data Sources
- Inside Airbnb  
- Airbnb City Portal  
- Public Airbnb listing and review datasets  

---

## ⚠ Disclaimer
This project was developed as part of academic coursework at the University of Auckland and is shared for educational and portfolio purposes only.
