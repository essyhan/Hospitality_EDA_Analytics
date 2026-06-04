# 🏨 Hotel Reservation Analytics: Mitigating Cancellations & Maximizing Revenue

## 📌 Project Overview
In the post-pandemic era, the hospitality industry faces a surge in demand, accompanied by a problematic rise in booking cancellations . This project, completed at Sungkyunkwan University, analyzes a comprehensive dataset of hotel reservations to uncover the hidden drivers behind cancellations and long-term stays . 

The ultimate objective is to translate Exploratory Data Analysis (EDA) into actionable business strategies that protect profitability, optimize room pricing, and improve customer retention .

## 📊 Dataset & Preprocessing
* **Data Source:** `Hotel_reservation.csv` (Kaggle), containing over 36,000 reservation records .
* **Data Cleansing:** Filtered out invalid bookings (e.g., zero-night stays with zero payments) and removed irrelevant metadata to focus on high-impact variables .
* **Feature Engineering:** Created derived metrics such as `total_nights` and dummy-encoded categorical features (Meal Plans, Booking Status, Market Segments) for correlation analysis .

## 💡 Key Business Insights
Through rigorous correlation analysis and data visualization, several critical trends were identified :
* **Customer Loyalty:** First-time visitors exhibit a cancellation rate significantly higher (34%) compared to returning guests (0.02%), highlighting the immediate need for automated retention programs .
* **Service Impact:** Bookings with meal plans show lower cancellation rates. Conversely, requests for parking spaces correlate with a 3x higher cancellation rate, potentially due to hidden fees .
* **Platform Behavior:** Online bookings face the highest cancellation rates due to the ease of comparison shopping and cancellation policies .
* **Long-term Stays & The Veblen Effect:** While most stays are short (under 7 days), long-term stays showed a unique trend. Demand is highest for budget-friendly rooms, but surprisingly rebounds in the "Very Expensive" category, suggesting a Veblen effect among luxury consumers .

## 🙋‍♀️ Strategic Recommendations & My Role
As a Data Analyst for this project, I bridged the gap between raw data and business operations . I formulated strategic recommendations based on our findings, such as:
1. Designing targeted promotions for high-cancellation months like July .
2. Restructuring parking fee policies into a loyalty reward system .
3. Adopting a strict "no-discount" policy for premium rooms targeting long-term luxury guests .

*Team Members: Seoyeon Han, Junhyeok Moon, Seyoung Park* 
