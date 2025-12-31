# TikTok Claims Classification Project Proposal

## Project Overview
**Business Problem**  
TikTok receives a high volume of user reports flagging potentially misleading or harmful videos. Manually reviewing every report is resource-intensive. Many reports involve opinion-based content (personal views), while others involve factual **claims** that may require verification.

**Objective**  
Build a machine learning model to automatically classify TikTok videos as either **claim** (factual assertion) or **opinion** (personal viewpoint) using video metadata, transcriptions, engagement metrics, and associated comments.

**Expected Outcome**  
Enable automated prioritization of user reports: route high-risk "claim" videos to moderators faster while deprioritizing low-risk "opinion" videos. This will reduce review backlog, improve moderation efficiency, and help combat misinformation.

**Success Metrics**  
- Model performance: AUC-ROC ≥ 0.85, high recall on "claim" class  
- Actionable insights into key drivers (e.g., engagement patterns, keywords)

**Dataset**  
Synthetic TikTok user report data provided in the course, including:  
- Video transcription and text  
- Engagement metrics (views, likes, shares, comments)  
- Binary target: `claim` vs. `opinion`

*This is the capstone project from the Google Advanced Data Analytics Professional Certificate.*

## Project Approach: PACE Framework
The project follows Google's **PACE** workflow (Plan → Analyze → Construct → Execute) to ensure structured progress and clear stakeholder communication.

## Milestones & Timeline

| Milestone | Tasks | PACE Stage | Deliverables | Key Stakeholder |
|-----------|-------|------------|--------------|-----------------|
| 1 | Establish workflow & write proposal | Plan | Project proposal & plan | Rosie Mae Bradshaw (Data Science Manager) |
| 2 | Compile and explore data | Analyze | Clean dataset ready for EDA | Orion Rainier (Data Scientist) |
| 3 | Data exploration, cleaning & visualization | Plan / Analyze / Construct | EDA report & Tableau executive dashboard | Mary Joanna Rodgers (Project Manager) |
| 4 | Descriptive statistics & hypothesis testing | Analyze / Construct | Statistical analysis results | Willow Jaffey (Data Science Lead) |
| 5 | Build and evaluate regression baseline | Construct / Execute | Regression model & evaluation | Rosie Mae Bradshaw (Data Science Manager) |
| 6 | Build final machine learning model & communicate insights | Construct / Execute | Final classification model, performance report, stakeholder presentation | Willow Jaffey (Data Science Lead) |

**Realistic Timeline (Professional Context)**  
In a real client engagement, timelines would be compressed:  
- Milestone 1: 1–2 days  
- Milestone 2: 2–3 weeks  
- Milestone 3: 1 week  
- Milestone 4: 1 week  
- Milestone 5–6: 1–2 weeks  

## Relevance to My Freelance Expertise
This binary classification project showcases end-to-end predictive modeling — skills directly applicable to **lead scoring and qualification** (e.g., predicting lead conversion probability based on behavioral signals and engagement data).

---
*Google Advanced Data Analytics Professional Certificate – Guided Capstone Project*

