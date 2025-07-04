# GTM
# 🧠 GTM Brain – Go-To-Market Operating System

Built using Snowflake + Cortex + Streamlit  
A full-stack AI-native assistant for Sales, Marketing, CS, and RevOps teams.

---

## 🔥 What is GTM Brain?

> Your first AI-powered GTM teammate.  
> It handles onboarding, predicts churn, plans campaigns, and tracks ROI — using real data, not just dashboards.

This isn’t just a project. It’s a *modular GTM brain* that integrates with your Snowflake environment and runs intelligence using Cortex-native AI models.

No-code teams can use it.  
Data teams don’t need to build it.  
Sales teams will just call it magic.

---

## 🚀 Use-Cases / Modules

### ✅ 1. *Onboarding Plan Generator*
- Creates personalized onboarding plans for new customers
- Integrates LLM + customer segmentation
- Outputs Notion-style checklists instantly

### ✅ 2. *Churn Risk Analyzer*
- Predicts which accounts are at risk
- Uses RISK_SCORE from Snowflake semantic model
- GPT recommends save actions

### ✅ 3. *Campaign ROI Tracker*
- Tracks marketing/sales campaign outcomes
- Auto-links cost → revenue across lifecycle
- Simulates what-if campaign models

### ✅ 4. *Prompt Audit & Logging*
- Stores every GPT call and response
- Enables reuse, debugging, and auditability
- AI becomes traceable like code

---

## 🧠 Tech Stack

| Layer        | Tech                              |
|--------------|-----------------------------------|
| AI Engine    | Snowflake Cortex (LLMs + ML)      |
| Backend      | Python (Snowpark)                 |
| UI Layer     | Streamlit                         |
| Data Source  | TBL_PATIENT_DETAILS_AGG in Snowflake |
| Model Input  | RISK_SCORE, demographics, billing, engagement |
| Hosting      | Localhost / Streamlit Cloud       |

