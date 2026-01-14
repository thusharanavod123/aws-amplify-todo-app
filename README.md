# AWS Amplify Serverless Todo App 

A hands-on **full-stack serverless Todo application** built with **AWS Amplify Gen 2** (or Gen 1 compatible), React, Cognito (auth), AppSync (GraphQL API), and DynamoDB (NoSQL DB).  

Perfect for DevOps / Cloud Architecture learning:  
- Serverless architecture (no servers to manage)  
- Secure user authentication  
- Real-time data sync  
- Auto CI/CD + hosting  
- Stays in **AWS Free Tier** for personal use

## Features
- User sign-up / login (email-based)  
- Create, read, update, delete personal Todos (owner-only access)  
- Real-time updates (optional subscription)  
- Deployed globally via Amplify Hosting (CDN)  

## Tech Stack
- **Frontend**: React (Vite or CRA) + Amplify UI  
- **Backend**: AWS Amplify (Auth + Data)  
- **Auth**: Amazon Cognito  
- **API**: AWS AppSync (GraphQL)  
- **Database**: Amazon DynamoDB  
- **Hosting**: Amplify Hosting + GitHub CI/CD  

## Quick Start (Local Dev)
1. Clone repo:
   ```bash
   git clone https://github.com/thusharanavod123/aws-amplify-todo-app.git
   cd aws-amplify-todo-app