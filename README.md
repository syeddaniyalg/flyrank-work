# Predictive SEO and Content Decay Analysis 
**FlyRank AI Machine Learning Internship, Summer 2026**

## 1. Project Overview
This repository contains the ongoing analysis, experimentation, and final capstone research conducted as part of the Machine Learning track at FlyRank AI. 

The primary objective of this project is to address the issue of "content decay" in Search Engine Optimization (SEO). With the introduction of AI-generated search summaries, organic search traffic has become increasingly concentrated and volatile. Using a production-grade dataset comprising over 79 million rows of Google Search Console data, this project develops predictive machine learning models to identify web pages that are exhibiting early indicators of traffic loss. The goal is to flag these pages for content refreshes before significant traffic attrition occurs.

## 2. Technical Objectives
The project is structured to achieve the following technical milestones:
*   **Data Aggregation and Analysis:** Process and analyze large-scale, anonymized search data to identify statistical correlations between search volume, impression decay, and content age.
*   **Baseline Establishment:** Evaluate the efficacy of traditional, heuristic-based algorithms currently used for flagging decaying content.
*   **Predictive Modeling:** Engineer and deploy machine learning models, including Logistic Regression and Decision Trees, to surpass the precision and recall metrics of the baseline heuristic models.
*   **Deployment of Insights:** Generate an actionable, ranked output queue that prioritizes pages requiring immediate intervention based on predictive scoring.

## 3. Repository Architecture
The repository adheres to the structural requirements defined by the FlyRank engineering framework. The directories are organized as follows:
*   `notebooks/`: Contains the initial exploratory data analysis and baseline model execution files.
*   `work/`: **Primary execution directory.** This folder houses all completed weekly assignments, isolated experimental models, and the final capstone documentation.
*   `scripts/`: Contains the reference automated data pipelines for preparation, baseline scoring, and model training. These files remain unedited as per framework guidelines.
*   `data/`: Stores the localized, anonymized sample datasets used for initial testing.
*   `outputs/`: Stores generated markdown reports, output queues, and data visualizations.
*   `docs/`: Contains core architectural documentation and data dictionaries.

## 4. Execution Schedule
All assignment notebooks are processed and archived within the `work/notebooks/` directory in accordance with the established curriculum.

*   [x] Week 1: Initial Data Discovery and Setup
*   [x] Week 2: Framing the Machine Learning Task and Baseline Rule Analysis
*   [ ] Week 3: Data Contracts and Feature Leakage Checks
*   [ ] Week 4: Signal Audits and Baseline Scoring
*   [ ] Week 5: Model Training and Optimization
*   [ ] Week 6: Validation Audits
*   [ ] Week 7: Action Playbooks
*   [ ] Week 8: Capstone Finalization 

## 5. Technology Stack
*   **Programming Language:** Python
*   **Execution Environment:** Google Colaboratory, Jupyter Notebooks
*   **Data Processing and Querying:** Pandas, DuckDB
*   **Machine Learning Frameworks:** Scikit-Learn
*   **Data Infrastructure:** Hugging Face (FlyRank Internship Warehouse)

## 6. Data Compliance Notice
All data utilized within this repository is strictly anonymized and complies with the data usage and privacy terms established by FlyRank AI. No proprietary client data, personally identifiable search queries, or internal domain information is present or processed within this public repository.