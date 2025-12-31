# 🏏 IPL Analytics: End-to-End Power BI Data Storytelling

![IPL Banner](https://upload.wikimedia.org/wikipedia/en/thumb/8/84/Indian_Premier_League_Official_Logo.svg/1200px-Indian_Premier_League_Official_Logo.svg.png)

## 📌 Executive Summary
This project transforms raw IPL cricket data (2008–2024) into a strategic decision-making tool. By leveraging **DAX**, **Power Query**, and **Data Modeling**, this dashboard provides actionable insights into team dynamics, player efficiency, and match-winning trends. 

🔗 **[Interact with the Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMzZkYWE3ZDctY2M5Mi00YjZhLWI4ZGYtNzQxOTEzODgwNTk5IiwidCI6ImI1M2FmNGY3LTE2ZTUtNGJjOC1iNjM5LWZjNTE0YTA0ZDllYiJ9)**

---

## 🚀 Key Business Questions Addressed
* **Performance Consistency:** Which teams maintain a high win-rate regardless of venue?
* **High-Impact Players:** Who are the most efficient "Face-off" winners (Batsman vs. Bowler)?
* **Match Strategy:** How do scoring patterns change over different segments of the 20 overs?
* **Tournament Trends:** How have average first-innings scores evolved over 17 seasons?

---

## 🛠️ Technical Stack & Workflow
* **Data Transformation (Power Query):** Handled missing values, standardized team names (e.g., Kings XI Punjab to PBKS), and normalized player names.
* **Data Modeling:** Implemented a **Star Schema** to optimize performance and ensure accurate filtering across 1,100+ matches and 200,000+ ball-by-ball records.
* **DAX Measures:** Developed custom measures for Strike Rate, Economy, Boundary %, and dynamic "Face-off" metrics.
* **Visualization:** Utilized dark-themed UI for readability, custom navigation bars, and interactive slicers for a seamless UX.

---

## 🖼️ Dashboard Architecture

### 1. 📊 League Overview (The Big Picture)
Provides macro-level trends including venue popularity, umpire frequency, and seasonal scoring trajectories.
![Overview](https://raw.githubusercontent.com/vk18chiku/IPL-ANALYSIS/main/Screenshot%202025-12-31%20130312.png)

### 2. 🧢 Team Strategic Profile
Enables franchise owners or analysts to drill down into over-by-over performance and venue-specific win probabilities.
![Team Profile](https://raw.githubusercontent.com/vk18chiku/IPL-ANALYSIS/main/Screenshot%202025-12-31%20130342.png)

### 3. 🧍‍♂️ Player Performance & Face-offs
A deep dive into individual excellence. Features a unique **Head-to-Head tool** to predict outcomes based on historical player matchups.
![Player Profile](https://raw.githubusercontent.com/vk18chiku/IPL-ANALYSIS/main/Screenshot%202025-12-31%20130352.png)

### 4. 🏠 Intuitive Navigation
User-centric design allowing non-technical stakeholders to navigate complex data easily.
![Homepage](https://raw.githubusercontent.com/vk18chiku/IPL-ANALYSIS/main/Screenshot%202025-12-31%20130258.png)

---

## 📈 Key Insights & Data Discoveries
* **Venue Bias:** Analysis shows a significant variance in average scores between stadiums like Wankhede (high scoring) vs. others, impacting toss decisions.
* **Efficiency vs. Volume:** Identified players who have lower total runs but higher "Impact Ratings" during the death overs (Overs 16-20).
* **Evolution of the Game:** The "Average Runs per Innings" visual shows a steady climb, reflecting the shift toward more aggressive batting styles in recent years.

---

## 📂 Project Structure
* `Data/`: Contains raw CSV/Excel files (Ball-by-ball and Match data).
* `Dashboard/`: The `.pbix` file.
* `Scripts/`: Any custom DAX or M-code snippets used for complex calculations.

---

## 🧑‍💻 Author
**Uttam Kumar Mahato** *Data Analytics Enthusiast* 📧 [uttammahato379@gmail.com](mailto:uttammahato379@gmail.com)  
🔗 [LinkedIn Profile](your-linkedin-link-here) | [Portfolio Site](your-portfolio-link-here)

---
*If you find this project useful, feel free to ⭐ the repository!*
