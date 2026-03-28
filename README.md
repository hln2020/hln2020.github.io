# Senior Data Scientist

### Technical Skills
Python (PyTorch, NumPy, Pandas, SciPy, scikit-learn, Matplotlib, Seaborn), LangGraph, Hugging Face, Prompt Engineering, In-Context Learning, SQL, MongoDB, S3, ChromaDB, Tableau, Git, Rancher, VSCode, PyCharm, WSL

# Education						       		
- M.S., Data Science | New York University (_May 2024_)	 			        		
- B.A., Economics | Lawrence University (_Jun 2016_)
- B.A., Mathematics | Lawrence University (_Jun 2016_)

# Data Science Projects

## **Fine-Tuning vs. Retrieval-Augmented Generation: Choosing the Right Approach for LLM Applications**

- Developed end-to-end RAG and fine-tuning pipelines for a domain-specific chatbot built on **Phi-3.5 Mini Instruct**, incorporating 55,625 pages of post–knowledge cutoff documentation.
- Architected and optimized retrieval pipelines using **e5-large-v2** and **all-mpnet-base-v2** embeddings, selecting the optimal strategy through top-k evaluation, metadata filtering, and latency profiling.
- Conducted comparative benchmarking of RAG vs. LoRA-based fine-tuning (continued pretraining and instruction tuning), evaluating factual accuracy, inference latency, and deployment complexity; recommended RAG as the primary strategy due to higher precision and lower operational overhead.
- Further improved RAG performance by implementing hybrid retrieval (BM25 + dense semantic search) that improved factual accuracy by 50% compared to a baseline dense-only RAG system.

![Visualization](/img/mpnet-false.png)
![Visualization](/img/mpnet-true.png)
![Visualization](/img/e5-false.png)
![Visualization](/img/e5-true.png)
![Visualization](/img/overall.png)
![Visualization](/img/dense_hybrid.png)


## **Credit Default Prediction: Machine Learning Approaches with Benchmark Comparisons**

- Trained and compared three models (Logistic Regression, XGBoost, Neural Network) on the UCI Credit Card Default dataset to predict borrower default risk
- Engineered 15+ features from raw payment/billing history (utilization ratios, delay counts, bill trends) and applied class-weighting to address imbalance without altering data distribution
- Ran Optuna Bayesian hyperparameter search to tune both neural network architecture and XGBoost across 50 trials, optimizing for AUC-PR to handle class imbalance
- Identified XGBoost to have the best performance (AUC-ROC: 0.783, AUC-PR: 0.560) against a 22% precision-recall baseline, with Neural Network close behind (AUC-PR: 0.559)
- Optimized classification thresholds per model via F1 scoring
- Used SHAP to identify number of late payments in the past 6 months, most recent repayment status, and maximum months overdue as the top predictors of credit default in XGBoost

![Visualization](/img/class_imbalance.png)
![Visualization](/img/credit_limit_by_default_status.png)
![Visualization](/img/default_rate_by_educ.png)
![Visualization](/img/pr_comparison.png)
![Visualization](/img/logistic_regression_classification_report.png)
![Visualization](/img/xgboost_classification_report.png)
![Visualization](/img/neural_network_classification_report.png)
![Visualization](/img/mean_shap.png)


## **State-Backed Information Operations Analysis Using Pre-trained Transformer-Based Models**
[GitHub Repo](https://github.com/hln2020/state-backed-io)  
- Utilized **Matplotlib**, **Pandas**, **Numpy** in Python to drive understanding of Twitter’s user behavior such as location, language, percentage of tweets by user ID.
- Created tweet embeddings using **OpenAI’s API** and applied **K-means clustering** to identify themes and extract narratives within state-backed information operations.
- Fine-tuned a pre-trained **LLM** to classify tweets belonging to such operations, achieving a 97% validation accuracy.

![Visualization](/img/tweet_language.png)

![Visualization](/img/tweet_location.png)

![Visualization](/img/Theme_extraction.png)


## **Predicting Obesity from Lifestyle Characteristics of Latin American Population**
[Link to Project](https://github.com/hln2020/Predicting-Obesity-Lifestyle/blob/master/Final%20Project.ipynb)
- Conducted data preprocessing and exploratory analysis using **Pandas**, **Matplotlib**, and **Seaborn** to visualize factors affecting obesity such as age, sex, caloric consumption, physical activities.
- Applied hypothesis testing using **Chi-Square** and **Mann-Whitney U** tests to perform feature selection.
- Achieved a 79% accuracy in identifying critical factors contributing to obesity using **logistic regression**.

![Visualization](/img/age.png)

![Visualization](/img/gender.png)

![Visualization](/img/hist_weight.png)



## **Large Language Models’ Cognitive Capabilities: A Study on OpenAI’s GPT Models**
[Github Repo](https://github.com/hln2020/gpt-cognitive-capabilities)  
- Conducted vignette-based investigations on **GPT-3.5** and **GPT-4’s** cognitive capabilities in decision-making, information search, deliberation, and causal reasoning using canonical scenarios from cognitive psychology.
- Applied prompt engineering on **GPT-3.5** and evaluated **GPT-3.5** and **GPT-4’s** performance compared to GPT-3.
- Identified the ability to handle adversaries as a weakness for current GPT models for future research purposes.

# Work Experience

## **Senior Data Scientist @ US AI, North Bethesda, MD (Sep. 2024 – Present)**
- Developed and deployed end-to-end AI solutions for cybersecurity automation using Hugging Face Transformers, prompt engineering & templating, custom data pipelines, and MongoDB.
- Integrated Retrieval-Augmented Generation (RAG) into US AI’s codeless platform with pgvector and LlamaIndex, leveraging object-oriented Python for scalable architecture.
- Led analytics and beta testing of Metabase dashboards, creating interactive reports with custom MongoDB queries.
- Collaborated with developers and the design team to design and implement AI-driven platform features, enhancing functionality and system integration.

## **International Data Team Manager @ Haver Analytics, New York, NY (Mar. 2020 – Sep 2024)**
- Lead a team of 4 data managers to manage 22 macroeconomic and financial databases covering Asia-Pacific.
- Utilized **OpenAI’s API** and **MySQL** to create a Q&A program on internal knowledge using embeddings-based search.
- Developed custom datasets for institutional clients, driving business decisions with accurate data.
- Directed the team’s automation effort, raising automation level from **3% to 42%** of ETL processes.
- Reviewed data additions, cleanups, methodology change implementations, and automation.

## **Senior International Data Manager @ Haver Analytics, New York, NY (Mar. 2019 – Mar. 2020)**
- Undertook team management responsibilities, including assigning and distributing workflow among members.
- Guided the team on complex client inquiries and projects requiring deep macroeconomic subject matter expertise.
- Researched documentation published by economic institutions, leading to increased insight in economic data-reporting procedures and changes in statistical classifications and methodologies.
- Collaborated closely with the Development team to provide product and program improvement recommendations.

## **International Data Manager @ Haver Analytics, New York, NY (Nov. 2016 – Mar. 2019)**
- Integrated 180+ macroeconomic datasets covering emerging economies in the Asia-Pacific region.
- Ensured data integrity and update timeliness through statistical analysis and automation.
- Created, implemented, and streamlined ETL procedures for data acquisition and updates.
- Utilized **Excel**, **EViews**, **Python**, and proprietary software to process and manipulate time series data.
- Provided clients with technical support and advised them on data analysis functions and optimal methods of tracking data.
