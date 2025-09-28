# Build a Two-Wheeler Marketplace Web App - VAHAN BAZAR

## Project Overview
A futuristic marketplace web application to **buy new bikes, scooters, EVs, and bicycles**, as well as **sell used bikes**. The platform offers:

- Search and Filter Options: Comprehensive filtering by brand, price, fuel type, and mileage.
- Product Visualization: Detailed specs and 3D model views for all new/upcoming bike launches.
- Model Comparison: Direct side-by-side model comparison table with highlighted differences.
- Finance Tools: Integrated EMI and fuel cost calculators for instant financial analysis.
- Analytics & Trust: Admin dashboard featuring units sold/views graphs and a customer feedback carousel for trust-building.
- AI Assistant: A movable chatbot bubble for handling user doubts and offering timely suggestions.
- Navigation: Centralized Sidebar (Hamburger Menu) for accessing all tools (Calculators, Settings, Booking).

---

## Tech Stack

**Frontend (Website/App):** React / Next.js (for a fast, great-looking site that works on phones)

**Backend(Server):** Python (FastAPI) / Node.js (Express) 

**Databases (Data Storage):** PostgreSQL (Main storage for products and users) / Redis (Super-fast temporary storage/caching)

**APIs / Libraries:** Tailwind CSS (for styling), Google Maps API (for Dealer Network location services).

**ML/AI Frameworks:** Gemini API (for the integrated Chatbot assistance and quick query handling).

---

## Features

### 1. Landing Page
- Split view: Buy New Bike | Resell Bike
- Quick redirects and CTA buttons
- Trust Bar: Icons or logos showing key partnerships (e.g., "5,000+ Dealers," "Integrated Finance," "Verified").
- Upcoming Launches: A dedicated, concise banner or small card carousel promoting the newest models to generate excitement.
- Floating Chatbot: The Movable Chatbot bubble remains active in the bottom corner for immediate support.

### 2. Listings Pages
- Cards for New and Used Bikes
- Featured Listings: A small, curated carousel showing 3-4 popular models (New and Used mixed).
- Filters: Brand, Price, Fuel, Calculators, Language, Comparison Side by side


### 3. Product Detail Pages
- Primary Visual: Build trust and allow deep visual inspection.
- Key Status: Provide immediate, essential buying information.
- Action Icons: Drive user engagement and future follow-up.

### 4. Compare Models
- Side-by-side comparison table
- Highlights differences
- Price Comparasion

### 5. Finance Tools
- EMI Calculator (CIBIL-based)
- Fuel Cost Calculator

### 6. Sidebar (Hamburger Menu)
- Profile, Comparison, EMI Calculator, Test Ride Booking, Price Comparison, Dealer Network, Contact us, Language Settings.

### 7. Movable Chatbot
- Bubble remains active in the bottom corner for immediate support.
- Handles doubts and suggestions

### 8. Performance & Validation
- Evaluation Metrics:
  
  a. Page Load Time (Target: ~ 1 seconds)
  
  b. API Latency (Target: < 200ms)
  
  c. Conversion Rate (Search to Booking)
  
  d. Chatbot Query Resolution Rate.
- Testing Strategy:
  
  a. Unit Testing: Covering all calculator logic and backend API endpoints
  
  b. Integration Testing: Ensuring seamless communication between Frontend, API, and Database
  
  c. User Acceptance Testing (UAT): Real users validating the core buying journey (Search -> Compare -> Calculate -> Book).
  
- Customer feedback carousel

---

## How to Run Locally

### Frontend
```bash
cd frontend
npm install
npm start
