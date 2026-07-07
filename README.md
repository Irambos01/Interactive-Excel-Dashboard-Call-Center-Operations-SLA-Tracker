# Interactive Excel Dashboard: Call Center Operations & SLA Tracker

# 📌 Project Overview

Operating without clear visibility into daily performance can severely impact customer satisfaction and team efficiency. This project demonstrates how a robust, fully automated business intelligence solution can be engineered entirely within **Microsoft Excel** using raw, unorganized call logs. 

This interactive performance engine transforms messy operational data into a structured tracking system. It enables operations managers to monitor service level agreements (SLAs), isolate departmental bottlenecks, and evaluate agent performance in real-time.

---

 # 🛠️ Key Technical Features & Automation

   **Dynamic Weekly Time-Series Control:** Integrated native Form Controls (Scroll-bar) to allow users to instantly swap through weekly datasets (e.g., viewing `Week #12` metrics) without duplicating worksheets or manually filtering pivot data.
  **Agent KPI Scorecard:** Built a structured roster tracking critical employee metrics (Total Calls, Average Speed of Answer, Call Resolution %).
    **Trend Analysis:** Embedded micro-visualizations (**Sparklines**) to showcase continuous weekly resolution trajectories at a glance.
    *   *Conditional Logic Alerts:* Programmed data-driven indicators (color-coded dots) that dynamically flag agents dropping below baseline expectations.
  **Automated SLA Threshold Alerts:** Engineered a *Call Abandon Rate by Department* column chart with a strict **20% target threshold line**. The system automatically triggers a visual red alert flag when a department (e.g., Television at `21.3%`) breaches safety limits.
  **Customer Sentiment Tracking (CSAT):** Designed a clean gauge-style visual and a granular horizontal bar chart tracking individual *Satisfaction Scores by Agent* against benchmark goals to quickly spot coaching opportunities.
  **SLA Compliance Log:** Automated critical operational roll-ups, isolating high-risk records such as the count of calls answered past the 180-second mark or low-sentiment scores (CSAT less than or equal to 3).

---

#  📊 Dashboard Preview

Below is a snapshot of the final interactive interface built from raw log files:

<img width="1016" height="610" alt="Call_Center_Complete" src="https://github.com/user-attachments/assets/bd675749-1a80-43be-9e23-8beaaa90a6ff" />


---

 ⚙️ Core Excel Techniques Implemented

  **Dynamic Advanced Formulas:** Leveraged robust formulas including 'SUMIF', 'SUMIFS',`INDEX`, `MATCH`, `OFFSET`, and nested `IF` statements to link form controls to data tables dynamically.
  **Pivot Tables & Data Modeling:** Utilized Pivot Tables to aggregate and slice thousands of raw call logs into clean, structured backend data summaries that feed the front-end visualizations.
  **Advanced Conditional Formatting:** Programmed multi-tier, rule-based visual alerts (including color-coded status indicators and data-driven cell highlighting) to isolate underperforming agents and instantly flag SLA breaches.
  **Interactive Form Controls:** Integrated native developer tools like the Scroll-bar Control to build a seamless, single-page interactive user interface that swaps datasets dynamically without user filtering.
  **Strategic Data Visualization:** Constructed custom KPI scorecards, inline trend lines (Sparklines), target-line column charts, and gauge representations explicitly optimized for immediate executive scanning and decision-making.
