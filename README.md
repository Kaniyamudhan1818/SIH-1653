# Smart India Hackathon Workshop
# Date:21.03.2025
## Register Number:212224040148
## Name: KANIYAMUDHAN V
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

1.Virtual panel interface mimicking real-life boardroom discussions.
Sequential questioning from ice-breakers to in-depth technical/managerial queries.
AI-Driven Question Generator:

2.Dynamically generates relevant questions based on the candidate’s expertise and job role.
Categorizes questions into basic, intermediate, and advanced levels.
Response Evaluation & Scoring:

3.AI-based Natural Language Processing (NLP) to analyze candidate responses.
Scores responses based on correctness, depth, and relevance.
Provides feedback on strengths and areas of improvement.
Expert Panel Assistance:

4.Assists interviewers by suggesting follow-up questions based on candidate’s answers.
Detects and flags irrelevant or biased questions.
Comprehensive Scoring System:

5.Assigns scores based on:
Relevance of the questions to expertise.
Relevance and quality of candidate responses.
Overall subject knowledge and managerial capabilities.
Bias Reduction Mechanism:

6.Ensures objective assessment by eliminating interviewer biases.
Standardized evaluation rubrics for all candidates.

## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/75b5764b-c052-4b1e-bbb0-f5c8be77c189)


## Use Cases
Candidate Interview Process – AI-driven structured interview experience.
Expert Panel Assistance – AI-suggested questions and real-time response analysis.
Automated Question Generation – Dynamic, expertise-based question selection.
Response Evaluation & Scoring – NLP-powered assessment for relevance and correctness.
Bias Detection & Fairness Control – AI ensures objective and unbiased evaluation.
Final Report & Decision Support – Comprehensive candidate performance analysis.


## Technology Stack
1. Cloud & Deployment
Cloud Platforms: AWS / Google Cloud / Azure
Containerization: Docker / Kubernetes
Serverless Computing: AWS Lambda / Google Cloud Functions

2. Security & Compliance
Encryption: AES-256 / TLS 1.2+
Compliance: GDPR, ISO 27001
Access Control: Role-Based Access Control (RBAC)


## Dependencies
1. AI/ML & NLP Dependencies
TensorFlow / PyTorch / Scikit-learn – Machine learning models
spaCy / NLTK / OpenAI GPT / BERT – Natural Language Processing
SpeechRecognition / DeepSpeech / Google Speech API – Speech-to-text
Fairlearn / AI Fairness 360 – Bias detection
2. Database & Storage Dependencies
PostgreSQL / MySQL / MongoDB – Database management
SQLAlchemy / Mongoose – ORM for database interactions
AWS S3 / Google Cloud Storage / Firebase – File storage
Redis – Caching and session storage

