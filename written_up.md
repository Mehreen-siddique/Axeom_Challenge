# Project Writeup: Axeom Business Analysis & Dashboard Solution

## 1. How Each Answer Was Found
* **Lead Conversion Funnel:** Processed and audited raw transaction and interaction logs to identify 102 total incoming leads. Cross-referencing confirmation statuses yielded 20 successful bookings and 82 lost/unclosed inquiries, establishing an exact conversion rate of **19.61%**.
* **Financial Integrity:** Verified payment logs against booking records, confirming **$0.00 in overdue payments**, indicating robust upfront collection practices though highlighting a lack of structured upsell tiers.
* **Root Cause Diagnosis:** Mapped lead drop-offs against response timestamps, discovering that uncentralized multi-channel communications and lack of automated follow-ups accounted for the majority of lost requests.

## 2. How the System Works
* **Interactive Dashboard (`app.py`):** Built using Python, Streamlit, Pandas, and Plotly. It provides a real-time visual breakdown of the conversion funnel, lead status distribution, and financial health metrics.
* **Operational Fix ("Monday Top 3"):** 
  1. *Centralized Inbox:* Consolidating all multi-channel inquiries into a unified CRM pipeline.
  2. *SLA Response Protocol:* Enforcing a strict 15-minute response window for inbound leads.
  3. *Automated Follow-ups:* Deploying scheduled touchpoints at 24h and 72h intervals.

## 3. What Doesn't Work Yet / Limitations
* **Real-time CRM Integration:** The current prototype relies on static batch CSV/JSON data ingestion rather than live webhook synchronization with active telephony or live-chat gateways.
* **Automated Lead Scoring:** Predictive scoring based on historical behavioral attributes is currently rudimentary and requires advanced machine learning classification pipelines.

## 4. Jev Job (Job Evaluation / Role Fit)
This challenge highlights my capability to transition fluidly from rigorous data engineering and exploratory data analysis to rapid full-stack prototyping (Streamlit/Python) and production deployment. By combining empirical data auditing with clean operational strategies, I bridge the gap between raw data insights and executive decision-making.

## 5. Next 2 Weeks Roadmap
* **Week 1:** Integrate live webhook connections to capture incoming leads in real-time and refine the automated follow-up sequence triggers.
* **Week 2:** Implement advanced predictive lead-scoring models using machine learning to prioritize high-intent inbound prospects automatically.
