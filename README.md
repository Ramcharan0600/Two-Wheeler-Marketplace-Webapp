# 𝐕𝐀𝐇𝐀𝐍 𝐁𝐀𝐙𝐀𝐑:𝐓𝐖𝐎-𝐖𝐇𝐄𝐄𝐋𝐄𝐑 𝐌𝐀𝐑𝐊𝐄𝐓𝐏𝐋𝐀𝐂𝐄 𝐒𝐔𝐁𝐌𝐈𝐒𝐒𝐈𝐎𝐍🏍️

## Problem Statement Reference
- **Problem Statement Chosen**: Build a two-wheeler marketplace web app where users can browse bikes, scooters, and EVs, search and filter by brand, price, or fuel type, view detailed specs with images, compare models side by side, use EMI and fuel cost calculators, check upcoming launches, explore showrooms, and book test rides or sell used bikes.🤯
  
- **Reason to Choose**: Aiyyo! We looked at the problem and said, "Why so much struggle, boss?" People are running everywhere online—one place for price, one place for loans, one place for specs! So, we decided: we must build one simple, powerful online shop—like a super-app for bikes! It brings all the main tools and the booking process into one spot. This makes the whole tension of buying a bike disappear, giving the customer full confidence.👍

---
## Solution Overview 💡
A futuristic marketplace web application to **buy new bikes, scooters, EVs, and bicycles**, as well as **sell used bikes**. The platform offers:🗺️

- Search and Filter Options: Comprehensive filtering by brand, price, fuel type, and mileage.🔍
- Product Visualization: Detailed specs and 3D model views for all new/upcoming bike launches.✨
- Model Comparison: Direct side-by-side model comparison table with highlighted differences.🗺️
- Finance Tools: Integrated EMI and fuel cost calculators for instant financial analysis.📱
- Analytics & Trust: Admin dashboard featuring units sold/views graphs and a customer feedback carousel for trust-building.📊
- AI Assistant: A movable chatbot bubble for handling user doubts and offering timely suggestions.🤖
- Navigation: Centralized Sidebar (Hamburger Menu) for accessing all tools (Calculators, Settings, Booking).

---

## System Architecture ⚙️

### 1. Landing Page📐
- Split view: Buy New Bike | Resell Bike
- Quick redirects and CTA buttons
- Trust Bar: Icons or logos showing key partnerships (e.g., "5,000+ Dealers," "Integrated Finance," "Verified").
- Upcoming Launches: A dedicated, concise banner or small card carousel promoting the newest models to generate excitement.
- Floating Chatbot: The Movable Chatbot bubble remains active in the bottom corner for immediate support.

### 2. Listings Pages⚡
- Cards for New and Used Bikes
- Featured Listings: A small, curated carousel showing 3-4 popular models (New and Used mixed).
- Filters: Brand, Price, Fuel, Calculators, Language, Comparison Side by side


### 3. Product Detail Pages🧠
- Primary Visual: Build trust and allow deep visual inspection.
- Key Status: Provide immediate, essential buying information.
- Action Icons: Drive user engagement and future follow-up.

### 4. Compare Models🔄
- Side-by-side comparison table
- Highlights differences
- Price Comparasion

### 5. Finance Tools🛡️
- EMI Calculator (CIBIL-based)
- Fuel Cost Calculator

### 6. Sidebar (Hamburger Menu)🌐
- Profile, Comparison, EMI Calculator, Test Ride Booking, Price Comparison, Dealer Network, Contact us, Language Settings.

### 7. Movable Chatbot💾
- Bubble remains active in the bottom corner for immediate support.
- Handles doubts and suggestions

---

## ⭐ Unique Features of Vahan Bazar

**The Decision Powerhouse**: 🧠
- - *Calculators Built Right Ins*: We figured buyers shouldn't have to leave the page to check their budget. Our EMI and Fuel Cost Calculators are right on the product page, giving you an instant, complete picture of what the bike will cost you every month. No more fiddling with spreadsheets!💰
  - *Smart Comparison, Not Just Lists:*: Tur Side-by-Side Comparison feature is genius. Instead of making you squint at two columns of numbers, we use smart logic to immediately highlight the key differences—like where one bike is superior to the other. 💡You decide faster.
    
**Intelligent Help & Accessibility**:🤝
- - *The Gemini AI Sales Assistant*: That movable chatbot bubble? That's your own personal sales rep. Powered by the Gemini API, it can answer any weird question you have about specs, finance terms, or even suggest the perfect bike for your daily commute. Help is always one tap away.
  - *Speak Your Language*: We know India is diverse! Our Native Language Preference setting means you can select your regional language for the entire app. The experience feels more comfortable, local, and trustworthy right away.
  - *The Business Brains*: For the people running Vahan Bazar, the chatbot is also a secret weapon. It lets administrators ask questions like, "How many scooters did we sell in Hyderabad last week?" and get instant analytical answers without having to run complex reports🤖.
    
**Modern Buying Experience**:🚀
- - *See It in 3D*: For new models, forget flat photos. Our 3D Model Viewer 🖼️ lets you spin, zoom, and look at the bike from every angle, making the virtual buying experience feel much closer to being in the showroom.
  - *Instant Action*: The main page is split into two clear paths: "Buy New Bike" or "Resell Bike. 🔄" This instant redirection means no wasted time and a perfectly tailored journey from the moment you land on Vahan Bazar🛒.

---

## Tech Stack

**Frontend (Website/App):** React / Next.js (for a fast, great-looking site that works on phones)⚛️

**Backend(Server):** Python (FastAPI) 🐍/ Node.js (Express) 🚀

**Databases (Data Storage):** PostgreSQL (Main storage for products and users) 🐘/ Redis (Super-fast temporary storage/caching)💨

**APIs / Libraries:** Tailwind CSS (for styling), Google Maps API (for Dealer Network location services).📍

**ML/AI Frameworks:** Gemini API (for the integrated Chatbot assistance and quick query handling). 🤖

---

## Algorithms & Models🧠
**Algorithm(s) Chosen**:
- - *Fast Search Index (Elasticsearch/Lucene)*: For super-fast, accurate search and filtering, even with thousands of bikes.🔎
  - *Rule-Based Comparison Logic*: Simple rules to identify and highlight key differences in specs between two chosen vehicles🔢
  - *Simple Rules for Suggestions*: A basic system that suggests bikes based on what's popular and what you've "Liked."⭐
    
**Reason for Choice**:✅ 	
See, Fast Search is mandatory! Otherwise, the site will hang when you filter—we can't have that 💨. The Comparison Logic provides the instant visual feedback (like the side-by-side view). The Simple Rules give immediate, good suggestions without needing massive data training right away.

**Model Training & Testing Approach**: We start with the Simple Rules. But later, we will grow the intelligence: we'll train a smarter Collaborative Filtering model using data on what people look at and buy.⚖️ We'll test it live (A/B testing) to see if it makes people click on the recommendations more often.📈 

---

## Data Handling📊
**Data Sources Used (APIs/Datasets)**: 
Manufacturer Specs (Product data)�, Dealer/Inventory Feeds🚚, Real-time User Clicks/Views (for analytics/recommendations)🖱️, External Geo-Location Data.🌍

**Preprocessing Methods**: 
- - *Normalization*:🏷️ Standardizing technical specs (e.g., converting engine power to a uniform unit).
  - *Feature Extraction*: Creating searchable indices for text-based filtering (Brand, Model, Type).
  - *Data Cleaning*: Ensuring mileage/price fields are valid numbers.🧼
    
**Storage / Pipeline Setup**:💾
- - *Data Ingestion*: Using Kafka for real-time capture of user events (clicks, searches) and ETL processes for batch data (inventory updates).
  - *Primary Storage*: PostgreSQL.
  - *Transient Storage*: Redis for managing high-velocity data and cached results.
---
## Implementation Plan

| Phase | Initial Setup & Environment | Core Module Development | Integration & Testing | Final Deployment-ready Build | 
| ----- | ----- | ----- | ----- | ----- | 
| **P1 (Foundation)** | Cloud provisioning, Auth service setup, **Frontend Shell**, and **Core Listings API**.🏗️ | **Search/Filter Logic**, API endpoints for product data. 🔍| Unit tests for authentication and data validation. 🔐|  | 
| **P2 (Feature Build)** |  | **Side-by-Side Comparison** logic, **EMI/Fuel Calculators** (Frontend). ⚖️| **Test Ride Booking API** and **Google Maps API** integration. 📍|  | 
| **P3 (Advanced & AI)** |  | **"Liked Vehicles"** persistence, **Admin Dashboard** setup. 📊| **Chatbot (Gemini API)** integration, end-to-end testing of core user flow. 🤖|  | 
| **P4 (Optimization)** |  | Final security review, performance testing (load testing). 🔒| Complete UAT sign-off and documentation. ✅| **Deployment** via containerization (Docker/Cloud Run). 🚀|

---
## Testing Strategy:
  
  - **Unit Testing:** Covering all calculator logic and backend API endpoints
  - **Integration Testing:** Ensuring seamless communication between Frontend, API, and Database
  - **User Acceptance Testing (UAT):** Real users validating the core buying journey (Search -> Compare -> Calculate -> Book).
  - Customer feedback carousel
  
---
## Performance & Validation🎯

- **Evaluation Metrics**:
- - API Latency (Target: < 200ms)⏱️
  - First Contentful Paint (FCP) (Target: ~ 2 seconds)🖼️
  - Conversion Rate (Search to Booking)💰
  - Chatbot Query Resolution Time.💬
  - 
- **Testing Strategy**:
- - *Unit Tests*: Verify individual functions (e.g., calculator formulas)🧪
  - *Integration Tests*: Confirm data flow between Frontend and Backend services🔗
  - *User Acceptance Testing (UAT)*: Real users validate core features like comparison and booking in a staging environment.🤝
---

## Deployment and Scalability
- **Deployment Plan**: Containerize the application using Docker. Deploy to a scalable environment like Azure App Service (using containers) ⚡or Azure Kubernetes Service (AKS). Use Azure CDN for lightning-fast delivery of static assets.🐳
- **Scalability**:
- - *Horizontal Scaling*: Backend services are stateless and designed to scale out automatically using Azure App Service scaling rules.📈
  - *Database*: Implement Azure Database for PostgreSQL Read Replicas to offload read-heavy traffic (listings, filtering).🐘
  - *Caching*: Aggressive use of Azure Cache for Redis to cache filter results and popular items, reducing database load.🚀

---
  
## How to Run Locally

### Frontend
```bash
cd frontend
npm install
npm start
