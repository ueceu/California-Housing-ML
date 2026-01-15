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
