# California Housing ML Dashboard

This is a demo project for exploring and predicting housing prices in California using machine learning. It demonstrates a full-stack deployment using:

- **Frontend:** Static dashboard hosted on [GitHub Pages](https://ueceu.github.io/California-Housing-ML/)
- **Backend:** FastAPI served on AWS EC2 behind an Application Load Balancer (aws-ml-alb-1793301098.us-east-1.elb.amazonaws.com)
- **Machine Learning Model:** Pretrained model predicting median house values
- **Data:** California Housing dataset

---

## Features

- Interactive visualizations for housing statistics by region
- Feature importance analysis for the ML model
- Predict house price using input parameters via API

---

## Deployment Architecture

- **Frontend:** Static site served by GitHub Pages  
- **Backend:** FastAPI application deployed on EC2  
- **Load Balancer:** AWS ALB distributes traffic to backend  
- **Security:** HTTPS supported on backend via ALB (no custom domain)  

> Note: Frontend and backend are hosted separately. The frontend communicates with the backend via the AWS ALB URL.

---

## Project Purpose

- Showcase a full-stack ML deployment
- Experiment with AWS services (EC2, ALB, Security Groups)

---

## Notes

- This project is a **demo**, no custom domain purchased
- Frontend/backend separation is intentional to simplify deployment
- Focus is on ML + cloud deployment demonstration

---

## Photos

<img width="1262" height="835" alt="Ekran görüntüsü 2026-01-15 225452" src="https://github.com/user-attachments/assets/57d21555-d848-4cbe-ae87-fb3d61ec8e23" />
<img width="1262" height="537" alt="Ekran görüntüsü 2026-01-15 225519" src="https://github.com/user-attachments/assets/c61cf095-6bfe-4179-805d-cf4a7a93fc0b" />
<img width="1265" height="1241" alt="Ekran görüntüsü 2026-01-15 225537" src="https://github.com/user-attachments/assets/697da69e-0896-48b6-bb37-8bda74547573" />
<img width="1201" height="1264" alt="Ekran görüntüsü 2026-01-15 225609" src="https://github.com/user-attachments/assets/7c967ac4-558f-4d9a-b639-cf01dce236c8" />
<img width="1262" height="1235" alt="Ekran görüntüsü 2026-01-15 225627" src="https://github.com/user-attachments/assets/c5823824-b2e5-4c64-b964-b504d90fb874" />
