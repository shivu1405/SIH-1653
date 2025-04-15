# Smart India Hackathon Workshop
# Date: 15.04.2025
## Register Number: 212224220098
## Name:
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
To create an automated, scalable, and objective interview platform that enhances the recruitment process by combining advanced AI, machine learning, and real-time analytics. This system would improve the overall candidate evaluation process, make it more efficient, unbiased, and data-driven, while simulating a real-world boardroom experience for both interviewers and candidates.

## Proposed Solution / Architecture Diagram
Transform DRDO’s recruitment with an AI-driven platform that delivers efficient, unbiased, and data-driven interviews, providing both interviewers and candidates a seamless, real-time boardroom experience.

Key Features:
Smart Questioning:

AI generates role-specific and relevant questions based on the candidate’s profile and job requirements, starting with ice-breakers and progressing to in-depth technical/managerial questions.

Real-Time Response Evaluation:

AI evaluates candidate responses using NLP to measure relevance, depth, and clarity, providing instant feedback on each answer.

Dynamic Scoring:

Combines AI-driven scores for knowledge and human feedback for soft skills to generate an overall suitability score.

Interactive Boardroom:

A virtual, immersive interview environment with video conferencing, real-time feedback, and a smooth interview flow.

Scalability & Adaptability:

Handle large-scale recruitment for multiple roles with tailored questions and adaptive scoring to match evolving job requirements.

Actionable Insights:

The system generates real-time analytics on candidate performance, interview trends, and recruitment metrics, helping DRDO make data-driven hiring decisions.

Impact:
Unbiased Assessments: AI ensures fair, objective evaluations.

Efficient & Scalable: Automates key tasks, enabling faster recruitment for high-volume hiring.

Informed Decisions: AI insights and real-time scoring help DRDO select the best candidates quickly and accurately.

This solution revolutionizes the interview process, combining AI technology with expert feedback to find the best talent for DRDO’s critical roles.
![Uploading architecture.png…]()



## Use Cases
Use Cases for DRDO's AI-Powered Recruitment System
Candidate Profile Setup:

What happens: Candidates create their profile by submitting personal info, skills, and resumes.

Why it matters: The system tailors questions to each candidate’s expertise and experience.

Interview Panel Setup:

What happens: Admin assigns interviewers based on the candidate's role and expertise.

Why it matters: Ensures the right experts are assessing the right candidate.

Smart Question Generation:

What happens: AI dynamically generates relevant, role-specific questions for the interview.

Why it matters: Keeps questions aligned with the candidate's experience and the job's needs.

Real-Time Response Evaluation:

What happens: The system evaluates each candidate response for relevancy and depth using AI.

Why it matters: Provides instant feedback on the candidate’s suitability, without human bias.

Scoring & Feedback:

What happens: The AI scores the candidate's answers, and interviewers provide subjective feedback.

Why it matters: Combines AI objectivity with expert insights for a well-rounded evaluation.

Admin Review & Shortlisting:

What happens: Admin reviews final candidate scores and feedback, then shortlists candidates.

Why it matters: Streamlines the decision-making process and improves hiring efficiency.

Performance Analytics:

What happens: The system generates real-time data on recruitment metrics and trends.

Why it matters: Helps optimize the hiring process and track improvements over time.

Continuous Learning:

What happens: The system learns from past interviews to improve its AI models.

Why it matters: Ensures the system keeps evolving for better results with each interview cycle.




## Technology Stack
Frontend:
React.js or Angular for dynamic web UI

React Native or Flutter for cross-platform mobile apps

WebRTC for real-time video conferencing

Backend:
Python (Django) or Node.js (Express.js) for APIs

Socket.io for real-time communication

Databases:
PostgreSQL for structured data

MongoDB for unstructured data

Elasticsearch for fast search queries

AI/ML & NLP:
SpaCy or NLTK for NLP tasks (question matching, response evaluation)

TensorFlow or PyTorch for ML models (candidate scoring)

BERT for advanced text analysis

Cloud & Infrastructure:
AWS or Azure for cloud hosting and scalability

Docker and Kubernetes for containerization and orchestration

Security:
OAuth 2.0 or JWT for authentication

SSL/TLS for encryption

Analytics & Reporting:
Power BI or Tableau for recruitment metrics

Grafana for real-time dashboards

CI/CD & Version Control:
Git for version control

Jenkins or GitLab CI for continuous integration/deployment

Third-Party Integrations:
Twilio for notifications

Zoom API or Google Meet API for video conferencing



## Dependencies

1. Development Time:
Frontend Development: 2-3 months (React.js, WebRTC, mobile app)

Backend Development: 3-4 months (Django/Express.js, real-time features, API)

AI/ML Integration: 2-3 months (TensorFlow/PyTorch, NLP setup)

Cloud & Infrastructure Setup: 1-2 months (AWS/Azure, Docker, Kubernetes)

Security & Authentication: 1 month (JWT, OAuth 2.0, SSL/TLS)

Testing & Deployment: 1-2 months (Unit, integration, and end-to-end testing)

Total Estimated Time: 6-8 months for complete system setup and deployment.

2. Cost Estimation:
Development Team:

Frontend Developers: $60,000 - $90,000 (per developer/year)

Backend Developers: $70,000 - $100,000 (per developer/year)

AI/ML Engineers: $80,000 - $120,000 (per engineer/year)

Cloud & Infrastructure Engineers: $70,000 - $100,000 (per engineer/year)

UI/UX Designers: $50,000 - $80,000 (per designer/year)

QA Engineers: $50,000 - $70,000 (per engineer/year)

Software & Tools:

Cloud Hosting (AWS/Azure): $500 - $2000/month (depending on traffic)

AI/ML Model Training Costs: $1000 - $5000 (depending on data processing requirements)

API Integrations (Zoom, Twilio): $200 - $1500/month (based on usage)

Licensing:

Power BI/Tableau: $10 - $35/month per user (for reporting & dashboards)

Other Costs:

Security Setup: ~$2000 - $5000 for implementation (SSL/TLS, encryption)

Development Tools (IDEs, version control): ~$5000 for the entire team

Total Estimated Initial Cost: $200,000 - $350,000 (depending on scale, features, and team size)

3. Technology and Tools:
Frontend: React.js, React Native, WebRTC

Backend: Django (Python) or Express.js (Node.js), Socket.io

AI/ML: TensorFlow, PyTorch, SpaCy, BERT

Database: PostgreSQL, MongoDB, Elasticsearch

Cloud: AWS or Azure (with Docker & Kubernetes for deployment)

Security: JWT/OAuth 2.0, SSL/TLS

Analytics: Power BI/Tableau, Grafana

CI/CD: Jenkins, Docker, Git
