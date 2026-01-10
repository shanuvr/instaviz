# InstaviZ – AI Powered Data Visualization Platform

InstaviZ is an **AI-powered data visualization platform** that allows users to upload CSV datasets, explore them interactively, chat with their data using natural language, and generate charts dynamically.

The platform is split into two main parts:

- **Backend** – Handles data ingestion, AI analysis, chart logic, authentication, and storage  
- **Frontend** – Provides a clean, interactive UI for uploading data, chatting with AI, and visualizing insights  
    
---

## 🔗 Repository Links

- **Frontend Repository**  
  https://github.com/devxtra-community/nextjs-instaviz.git

- **Backend Repository**  
  https://github.com/devxtra-community/nodejs-instaviz.git

---

## 🚀 Platform Features

### 📂 CSV Upload & Parsing
- Upload large CSV files efficiently
- Streaming-based parsing for performance
- Automatic extraction of columns, rows, and sample data
- Upload state persists across page refresh

### 🗄️ Smart Data Storage
- Dataset metadata stored separately from dataset rows
- Dynamic schema support for any CSV structure
- MongoDB optimized for analytical queries

### 📊 AI-Driven Chart Generation
- Natural language → MongoDB aggregation pipelines
- Supports bar charts, pie charts, and summaries
- Automatic chart intent detection
- Fallback local chart generation if AI fails

### 🤖 AI Chat with Your Data
- Ask analytical questions about datasets
- Request charts directly via chat
- Natural language → structured data responses
- Cost-optimized AI model switching

### 👤 Guest & Authenticated Users
- JWT-based authentication for logged-in users
- Automatic guest user creation using cookies
- Token-based usage limits
- Refresh-safe session handling

### 🔁 Reliability & Scalability
- Gemini API key rotation on quota/rate-limit errors
- Middleware-based security
- Modular and scalable architecture
- Clean separation of concerns

---
 
## 🛠️ Tech Stack

### Backend
- **Runtime**: Node.js  
- **Framework**: Express.js  
- **Language**: TypeScript  
- **Database**: MongoDB (Mongoose)  
- **AI Models**: Google Gemini (1.5 / 2.5 Flash)  
- **Auth**: JWT + Guest Cookies  
- **Storage**: Cloud object storage (R2 / S3 compatible)  
- **CSV Parsing**: Streaming-based parser  

### Frontend
- **Framework**: Next.js (App Router)  
- **Language**: TypeScript  
- **UI**: React, Tailwind CSS  
- **State Management**: React Context  
- **HTTP Client**: Axios  
- **Charts**: Dynamic chart components (backend-driven)  
- **Authentication**: JWT & Guest Cookies  

---

