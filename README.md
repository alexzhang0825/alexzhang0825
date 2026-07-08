# Welcome
I'm Hongyang, a machine learning engineer based in Vancouver focused on building production-grade AI systems — RAG pipelines, LLM agents, and NLP applications that hold up outside a demo. Background in mathematics, statistics, and data science (UW, Haifa, UBC MDS).

# Education
**Bachelor of Arts in Mathematics**  
*University of Washington*  
*2016 - 2020*  
- Relevant coursework: Function Analysis, Topology, Modern Algebra, Probability

**Master of Science in Statistics**  
*University of Haifa*  
*2021 - 2022*  
- Relevant coursework: Statistical Learning, Mathematical Statistics, Markov Chain, Regression

**Master of Data Science**  
*University of British Columbia*  
*2023 - 2024*  
- Capstone project: Sentiment Analysis Model Development
- Relevant coursework: Supervised and Unsupervised Machine Learning, Regression, Inference, Causal Analysis, Development Workflow, Visualizations

# Programming Skills
<p>
  <img src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/git.svg" alt="Git" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/python.svg" alt="Python" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/r.svg" alt="R" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/postgresql.svg" alt="PostgreSQL" width="40" height="40"/>
</p>

# Contributions

## Venue Prioritization RAG Pipeline
Production-grade RAG pipeline that rebuilds a scrappy internship prototype (Make + Airtable + ChatGPT) into a proper agentic system — LangChain, LangGraph, and Pinecone, scoring and ranking venues via a 4-node multi-agent workflow.

My specific contributions were:
- Built the full LangGraph multi-agent scoring workflow (services, sentiment, products, fit nodes) producing weighted, explainable rankings
- Ingested 32 real venues via the Google Places API and chunked scraped content into 326 vectors for targeted semantic retrieval
- Migrated from local FAISS to Pinecone for persistent, environment-agnostic retrieval
- Added GitHub Actions CI/CD with mocked scraper tests

[![GitHub Repository](https://img.shields.io/badge/Repository-Visit-blue)](https://github.com/alexzhang0825/piko-venue-rag)

## Client Warmth Classification — Production Upgrade
Revisited a UBC MDS capstone project and identified that the original team had tuned hyperparameters directly on the test set, inflating reported accuracy — corrected the methodology and hardened the pipeline for production.

My specific contributions were:
- Corrected the evaluation methodology with a stratified 70/15/15 train/val/test split
- Fine-tuned DistilBERT with weighted CrossEntropyLoss, improving accuracy from 59% to 96.5% and hot-class recall from 33% to 100%
- Added FastAPI deployment, Docker containerization, MLflow experiment tracking, and SHAP explainability

[![GitHub Repository](https://img.shields.io/badge/Repository-Visit-blue)](https://github.com/alexzhang0825/side-client-warmth)

## Tactical Route Planner
AI-powered tactical navigation system built in a ~4-5 hour hackathon, dynamically rerouting ground units around threats detected from drone imagery on a real map of Vancouver.

My specific contributions were:
- Integrated Google Gemini 1.5 Flash Vision API to extract structured threat data from drone images
- Built a geospatial projection pipeline and live rerouting via OpenStreetMap/osmnx and NetworkX
- Built the FastAPI backend and React/Mapbox GL JS frontend, with graceful degradation on API failure

[![GitHub Repository](https://img.shields.io/badge/Repository-Visit-blue)](https://github.com/alexzhang0825/tactical-route-planner)

## Red Wine Quality Prediction
This repository is for a data analysis project on red wine quality prediction using different machine learning model. The project itself is nothing sophisticated as the primary focus was on creating a reproducible analysis report.

My specific contributions were:
- Fine-tuned parameters of different machine learning models for classification (Logistic Regression, SVM RBF, kNN, Decision Tree)
- Wrote multiple test functions for different functionalities
- Helped make the report reproducible using jupyter book
- Set up proper instructions for reproducing the report under virtual environment

[![GitHub Repository](https://img.shields.io/badge/Repository-Visit-blue)](https://github.com/UBC-MDS/Red-Wine-Quality-Prediction)

## World Happiness Tracker
This repository is for a visualization dashboard of a world happiness level data. The dashboard is interactive and allows the user to see trends and rankings based on user selections.

My specific contributions were:
- Developed dash module for a interactive `pandas` table in the dashboard
- Helped track different changes implemented as reflection

[![GitHub Repository](https://img.shields.io/badge/Repository-Visit-blue)](https://github.com/UBC-MDS/DSCI-532_2024_3_world-happiness-tracker)

# Social Media
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/hongyang-zhang-1943b916b/)
