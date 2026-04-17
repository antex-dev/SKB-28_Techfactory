# SKB-28_Techfactory
## Team Members
- Aditya Yuvnate  
- Aniruddha Wadankar  
- Aman Wadichar  
- Jeshtha Suyavanshi  
- Kapindra Shetiye  
- Mayuri Patle  

## Problem Statement
Accurate Monitoring, Reporting, and Verification (MRV) in carbon markets is a major challenge. Traditional systems rely on optical satellite imagery, which fails under cloud cover, seasonal changes, and environmental noise.

## Description

This system addresses one of the biggest challenges in carbon markets — ensuring accurate and reliable Monitoring, Reporting, and Verification (MRV) at the farm level.

Traditional MRV systems depend heavily on optical satellite imagery, which becomes unreliable under cloud cover, seasonal variability, and noisy environmental conditions.

##  PPT / Project Presentation

[Click here to view/download PPT](./IDEA_FACTORY_SKB-28..pptx)

## Features
- Cloud-proof monitoring using SAR data  
- AI-based irrigation pattern detection (AWD)  
- Methane emission estimation  
- Automated carbon credit verification  
- Farmer-friendly and scalable system  

---

##  Impact
- Promotes sustainable farming  
- Reduces greenhouse gas emissions  
- Builds trust in carbon markets

##   Modal Chart/ Architecture Details

User → Frontend → Backend → AI Engine → Fusion Layer → Data Sources


                      USER LAYER
        ┌─────────────────────────────────────┐
        │  Farmers | Companies | Government   │
        └─────────────────────────────────────┘
                          │
                          ▼
                   FRONTEND (Next.js)
        ┌─────────────────────────────────────┐
        │  • Interactive Map (MapLibre)       │
        │  • Dashboards (Farmer/Company/Admin)│
        │  • Voice Chat UI                    │
        └─────────────────────────────────────┘
                          │
                          ▼
                  BACKEND (FastAPI)
        ┌─────────────────────────────────────┐
        │  • REST APIs                        │
        │  • Auth (JWT + RBAC)                │
        │  • Business Logic                   │
        └─────────────────────────────────────┘
                          │
                          ▼
                  AI ENGINE (Python)
        ┌─────────────────────────────────────┐
        │  • AWD Detection Model (LSTM/ViT)   │
        │  • Methane Estimation               │
        │  • Rain vs Irrigation Classifier    │
        │  • Voice NLP (Llama3)               │
        └─────────────────────────────────────┘
                          │
                          ▼
           MULTI-MODAL FUSION LAYER
        ┌─────────────────────────────────────┐
        │  Combine:                           │
        │  • SAR (Sentinel-1)                 │
        │  • Optical (Sentinel-2 NDWI)        │
        │  • Weather (IMD API)                │
        │  • Temperature (Sentinel-3)         │
        └─────────────────────────────────────┘
                          │
                          ▼
                    DATA LAYER
        ┌─────────────────────────────────────┐
        │  • PostgreSQL + PostGIS             │
        │  • Google Earth Engine              │
        │  • Farm Boundaries (BHUKOS)         │
        └─────────────────────────────────────┘
                          │
                          ▼
                    DEPLOYMENT
        ┌─────────────────────────────────────┐
        │  • Vercel (Frontend)                │
        │  • Railway (Backend)                │
        │  • Cloudflare (CDN/Security)        │
        └─────────────────────────────────────┘

## Progress Report

