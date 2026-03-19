<div align="center">

# 🛡️ GigShield — AI-Powered Parametric Income Protection for Food Delivery Partners

### *Because a rainstorm shouldn't mean an empty wallet.*

[![Phase](https://img.shields.io/badge/Phase-1%20%7C%20Ideation%20%26%20Foundation-blue)]()
[![Persona](https://img.shields.io/badge/Persona-Food%20Delivery%20(Zomato%2FSwiggy)-orange)]()
[![Coverage](https://img.shields.io/badge/Coverage-Loss%20of%20Income%20Only-green)]()
[![Pricing](https://img.shields.io/badge/Pricing-Weekly%20Model-purple)]()

</div>

---

## 📑 Table of Contents

1. [Problem Statement](#-problem-statement)
2. [Our Persona — The Food Delivery Partner](#-our-persona--the-food-delivery-partner)
3. [Persona-Based Scenarios](#-persona-based-scenarios)
4. [Application Workflow](#-application-workflow)
5. [Weekly Premium Model](#-weekly-premium-model)
6. [Parametric Triggers](#-parametric-triggers)
7. [Platform Choice — Web vs Mobile](#-platform-choice--web-vs-mobile)
8. [AI/ML Integration Strategy](#-aiml-integration-strategy)
9. [Fraud Detection Architecture](#-fraud-detection-architecture)
10. [Tech Stack](#-tech-stack)
11. [Development Roadmap](#-development-roadmap)
12. [Market Crash Compliance](#-market-crash-compliance)
13. [Team](#-team)

---

## 🔥 Problem Statement

India has over **10 million gig delivery workers** across platforms like Zomato, Swiggy, Amazon, Zepto, and Blinkit. These workers earn daily wages — typically **₹500–₹1,200/day** — and operate with **zero financial safety net**.

When external disruptions strike — a heavy monsoon downpour, an AQI spike above 400, a sudden curfew — these workers **cannot deliver**. No deliveries = **no income**. Unlike salaried employees, there is no paid leave, no sick days, no employer-backed insurance.

> **GigShield** solves this by providing **AI-powered parametric insurance** that automatically detects disruptions and instantly compensates delivery partners for lost income — **no claims forms, no delays, no middlemen.**

### What We Cover ✅
| Covered | Not Covered ❌ |
|---------|---------------|
| Loss of income due to extreme weather | Health insurance |
| Loss of income due to severe pollution (AQI) | Life insurance |
| Loss of income due to curfews/strikes | Accident coverage |
| Loss of income due to zone closures | Vehicle repair costs |

---

## 👤 Our Persona — The Food Delivery Partner

We have chosen **Food Delivery Partners (Zomato/Swiggy)** as our primary persona.

### Why Food Delivery?

| Factor | Justification |
|--------|--------------|
| **Largest gig workforce** | Zomato + Swiggy employ ~5M+ delivery partners across India |
| **Highest weather sensitivity** | Food delivery happens outdoors, on two-wheelers, and is directly impacted by rain, heat, and pollution |
| **Real-time data availability** | Weather APIs, AQI data, and traffic APIs provide rich, city-level data for parametric triggers |
| **Weekly earning cycle** | Most delivery partners track earnings weekly, aligning perfectly with the weekly premium model |
| **Underserved segment** | No existing insurance product addresses income loss for food delivery workers specifically |

### Delivery Partner Profile — "Ravi"

| Attribute | Details |
|-----------|---------|
| **Name** | Ravi Kumar |
| **Age** | 26 years |
| **Platform** | Zomato / Swiggy |
| **City** | Bengaluru |
| **Daily earnings** | ₹800–₹1,100 (avg ₹950) |
| **Weekly earnings** | ₹5,700–₹6,650 |
| **Working hours** | 10 AM – 10 PM (split shift) |
| **Vehicle** | Two-wheeler (personal) |
| **Key risks** | Monsoon rains (June–Sept), heat waves (March–May), city-level bandhs |
| **Financial buffer** | < ₹2,000 in savings |
| **Digital literacy** | Comfortable with apps; uses UPI daily |

---

## 🎬 Persona-Based Scenarios

### Scenario 1: Heavy Rainfall 🌧️
> **Date:** July 15, Bengaluru  
> **Event:** IMD issues a Red Alert — rainfall exceeds 65mm in 3 hours  
> **Impact on Ravi:** Cannot ride safely. Zomato shows "limited delivery zones." Ravi stays home.  
> **Income lost:** ₹950 (full day)  
> **GigShield Response:** Weather API detects rainfall threshold breach → Parametric trigger fires → ₹950 auto-credited to Ravi's UPI within 2 hours. **Zero claims filed.**

### Scenario 2: Extreme Heat Wave 🔥
> **Date:** May 3, Delhi  
> **Event:** Temperature exceeds 46°C. NDMA issues heat advisory.  
> **Impact on Aamir (Delhi delivery partner):** Platform reduces orders in afternoon slots. Aamir can only work 4 hours instead of 10.  
> **Income lost:** ₹570 (partial day — 6 hours lost)  
> **GigShield Response:** Temperature sensor data crosses threshold → Proportional payout calculated based on hours lost → ₹570 credited via UPI.

### Scenario 3: Unplanned Curfew / Bandh 🚫
> **Date:** September 22, Pune  
> **Event:** Sudden state-imposed curfew due to law-and-order situation. All movement restricted for 14 hours.  
> **Impact on Priya (Swiggy partner):** App shows "services suspended in your area." Full day lost.  
> **Income lost:** ₹850  
> **GigShield Response:** Government advisory API / news feed NLP detects curfew announcement → Auto-trigger fires for affected PIN codes → ₹850 credited.

### Scenario 4: Severe Air Pollution (AQI > 400) 🏭
> **Date:** November 10, Delhi-NCR  
> **Event:** AQI crosses 450. GRAP Stage 4 restrictions imposed. Outdoor work advisory issued.  
> **Impact:** Delivery partners in affected zones face order drops of 70%+.  
> **Income lost:** ₹665 (proportional to reduced orders)  
> **GigShield Response:** AQI monitor API detects breach → Proportional payout based on zone-level order reduction data.

---

## 🔄 Application Workflow

```
┌─────────────────────────────────────────────────────────────────────────┐
│                        GIGSHIELD WORKFLOW                              │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                       │
│  ┌──────────┐    ┌──────────────┐    ┌────────────────┐               │
│  │  STEP 1  │    │   STEP 2     │    │    STEP 3      │               │
│  │ Onboard  │───▶│ Risk Profile │───▶│ Policy Created │               │
│  │ (OTP +   │    │ (AI scores   │    │ (Weekly plan   │               │
│  │  Aadhaar)│    │  location,   │    │  auto-assigned │               │
│  │          │    │  history)    │    │  + payment)    │               │
│  └──────────┘    └──────────────┘    └───────┬────────┘               │
│                                              │                        │
│                                              ▼                        │
│  ┌──────────┐    ┌──────────────┐    ┌────────────────┐               │
│  │  STEP 6  │    │   STEP 5     │    │    STEP 4      │               │
│  │Dashboard │◀───│ Instant UPI  │◀───│ Auto-Trigger   │               │
│  │& History │    │   Payout     │    │ Fires (Weather │               │
│  │          │    │              │    │  API breach)   │               │
│  └──────────┘    └──────────────┘    └────────────────┘               │
│                                                                       │
└─────────────────────────────────────────────────────────────────────────┘
```

### Detailed Flow:

| Step | Action | Details |
|------|--------|---------|
| **1. Onboarding** | Delivery partner registers | Mobile number → OTP verification → Aadhaar-based KYC (DigiLocker API) → Platform ID linking (Zomato/Swiggy partner ID) |
| **2. AI Risk Profiling** | System generates risk score | ML model analyzes: delivery zone (historical weather data), working hours, city risk index, seasonal patterns → Assigns risk tier (Low/Medium/High) |
| **3. Policy Creation** | Weekly policy auto-generated | Based on risk tier → Premium calculated (₹49–₹99/week) → Coverage amount set (₹3,500–₹7,000/week) → Auto-debit via UPI mandate |
| **4. Trigger Monitoring** | Real-time parametric monitoring | Weather API, AQI API, Government advisories monitored 24/7 → When threshold breached in partner's PIN code → Trigger fires automatically |
| **5. Instant Payout** | Zero-touch claim processing | Trigger event validated → Payout amount calculated (full-day or proportional) → UPI instant transfer → Partner notified via SMS/push |
| **6. Dashboard** | Partner & admin visibility | Partner sees: active coverage, claim history, earnings protected. Admin sees: loss ratios, trigger frequency, fraud alerts |

---

## 💰 Weekly Premium Model

### Why Weekly?
Gig delivery workers are paid on a **weekly settlement cycle** by platforms like Zomato and Swiggy. Monthly premiums create cash flow mismatches — workers may not have ₹400 on Day 1 of the month but can comfortably pay ₹79 at the start of each week from their weekly settlement.

### Premium Structure

| Risk Tier | Weekly Premium | Weekly Coverage (Max Payout) | Daily Rate | Target Profile |
|-----------|---------------|------------------------------|------------|----------------|
| 🟢 **Low Risk** | ₹49/week | ₹3,500/week | ₹500/day | Partners in low-rain cities, non-monsoon months |
| 🟡 **Medium Risk** | ₹79/week | ₹5,500/week | ₹785/day | Partners in metro cities, mixed weather patterns |
| 🔴 **High Risk** | ₹99/week | ₹7,000/week | ₹1,000/day | Partners in flood-prone/high-AQI zones, monsoon season |

### Premium Calculation Logic
```
Weekly_Premium = Base_Rate × City_Risk_Multiplier × Season_Multiplier × Claims_History_Factor

Where:
  Base_Rate           = ₹49 (minimum viable weekly premium)
  City_Risk_Multiplier = 1.0 (Jaipur) to 1.8 (Mumbai monsoon zone)
  Season_Multiplier    = 1.0 (Oct-Feb) to 1.5 (Jun-Sep monsoon)
  Claims_History_Factor = 0.9 (no claims last 4 weeks) to 1.2 (2+ claims last 4 weeks)
```

### Financial Viability

| Metric | Value | Justification |
|--------|-------|---------------|
| Average premium/partner/week | ₹79 | Affordable at ~1.3% of weekly earnings (₹6,000) |
| Target loss ratio | 60-65% | Industry standard for parametric insurance |
| Expected claims frequency | 2-3 triggers/month (monsoon), 0.5/month (winter) | Based on IMD historical weather data for metros |
| Break-even pool size | ~5,000 partners per city | Sufficient risk pooling for actuarial stability |

---

## ⚡ Parametric Triggers

Parametric insurance eliminates the traditional claims process. Instead of the worker filing a claim and waiting weeks, **the system automatically detects the event and pays out instantly**.

### Defined Triggers

| # | Trigger | Data Source | Threshold | Payout Type | Justification |
|---|---------|------------|-----------|-------------|---------------|
| 1 | **Heavy Rainfall** | OpenWeatherMap API / IMD | > 50mm in 3 hours OR Red/Orange alert by IMD | Full-day payout | Historical data shows delivery drops 80%+ during heavy rain |
| 2 | **Extreme Heat** | OpenWeatherMap API | Temperature > 45°C (real-feel) | Proportional (based on hours above threshold) | NDMA advisories recommend avoiding outdoor work above 45°C |
| 3 | **Severe AQI** | CPCB AQI API | AQI > 400 (Severe+) | Proportional (50-100% based on duration) | Delhi govt restricts outdoor activities at AQI 400+ |
| 4 | **Curfew / Bandh** | News NLP + Govt Advisory API | Official curfew/bandh declared for partner's zone | Full-day payout | Legally cannot operate; platforms suspend service |
| 5 | **Flooding / Waterlogging** | Weather API + Crowd-sourced data | IMD flood warning + rainfall > 100mm/day | Full-day payout | Roads inaccessible; delivery physically impossible |

### Why These Triggers?

- **Objective & Verifiable**: Every trigger is backed by a **publicly available, tamper-proof data source** (government APIs, IMD data, CPCB readings). This eliminates subjectivity and prevents disputes.
- **Directly Correlated to Income Loss**: Each trigger maps to a documented scenario where delivery platforms either suspend service or orders drop drastically.
- **Automatable**: All data sources provide API-level access, enabling real-time monitoring without human intervention.

---

## 📱 Platform Choice — Web vs Mobile

### Our Choice: **Progressive Web App (PWA) — Mobile-First Design**

| Factor | Web App | Native Mobile | **PWA (Our Choice)** ✅ |
|--------|---------|--------------|----------------------|
| Installation barrier | None | High (app store download, 80MB+) | **None** (add to homescreen, <2MB) |
| Cross-platform | ✅ | ❌ (2 codebases) | **✅ Single codebase** |
| Offline access | ❌ | ✅ | **✅ Service workers** |
| Push notifications | Limited | ✅ | **✅ Web Push API** |
| Development speed | Fast | Slow | **Fast** |
| Cost to build | Low | High | **Low** |
| Access to UPI | Via redirect | Deep link | **Via redirect (works)** |
| Works on low-end phones | ✅ | ❌ (RAM/storage) | **✅** |

### Justification

1. **Delivery partners use low-end Android phones** (₹8,000–₹12,000 range). They already run Zomato/Swiggy/Google Maps — installing another 80MB app is a dealbreaker. A PWA is **< 2MB** and runs from the browser.
2. **Zero friction onboarding**: Share a link via WhatsApp (their primary communication channel) → Open → Register in 2 minutes. No Play Store needed.
3. **Single codebase**: With a team of 3-5 people and 6 weeks, maintaining iOS + Android + Web is unrealistic. PWA lets us ship one product that works everywhere.
4. **Offline capability**: Service workers cache the dashboard, policy details, and claim history — critical when partners are in areas with spotty internet.

---

## 🤖 AI/ML Integration Strategy

### AI Component 1: Dynamic Premium Calculation (ML-Based Pricing Engine)

**Model**: Gradient Boosted Decision Trees (XGBoost / LightGBM)

| Input Feature | Source | Why |
|--------------|--------|-----|
| Delivery zone PIN code | User registration | Hyper-local risk varies by neighborhood |
| Historical weather data (last 2 years) | OpenWeatherMap historical | Predicts future disruption probability |
| Seasonal pattern | Calendar | Monsoon months = higher risk |
| City-level claim frequency | Internal data | Cities like Mumbai have 3x more rain claims than Jaipur |
| Worker's past claim history | Internal data | Frequent claimants may indicate higher-risk zones or behavior |

**Output**: Personalized weekly premium (₹49–₹99) based on the worker's actual risk profile.

**Why XGBoost?**: Tabular data with mixed feature types → XGBoost consistently outperforms deep learning for this class of problems. Fast inference, interpretable (SHAP values for regulatory explainability), and proven in insurance industry pricing models.

### AI Component 2: Intelligent Fraud Detection

**Model**: Isolation Forest + Rule-Based Ensemble

| Fraud Vector | Detection Method | Details |
|-------------|-----------------|---------|
| **GPS Spoofing** | Location anomaly detection | Compare claimed location with cell tower / IP geolocation. If partner claims to be in a rain zone but GPS history shows a dry zone → flag |
| **Duplicate Claims** | Deduplication engine | Same partner, same trigger event, multiple claim attempts → auto-reject |
| **Fabricated Inactivity** | Activity cross-reference | Cross-check platform API (simulated) — if partner was actually completing deliveries during "disruption" period → flag |
| **Collusion Patterns** | Graph analysis | Multiple partners from same location filing claims for an event not detected by weather APIs → investigate |

**Why Isolation Forest?**: Unsupervised anomaly detection that doesn't require labeled fraud data (which we won't have initially). It isolates "odd" data points — perfect for catching fraud patterns we haven't seen before.

### AI Component 3: Predictive Risk Modeling

**Model**: Time-Series Forecasting (Prophet / LSTM)

- **Purpose**: Predict next week's disruption probability per zone to proactively adjust coverage and reserves.
- **Input**: Historical weather patterns, seasonal trends, city-level disruption frequency.
- **Output**: Zone-wise risk heatmap → Enables the insurer to maintain adequate reserves and offer pre-emptive coverage upgrades.

**Why Prophet?**: Facebook's Prophet handles seasonal time-series with missing data gracefully. Delivery disruptions are inherently seasonal (monsoon, summer heat, winter fog), making Prophet ideal.

---

## 🔒 Fraud Detection Architecture

```
┌──────────────────────────────────────────────────────────┐
│                FRAUD DETECTION PIPELINE                  │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  [Trigger Event] ──▶ [Layer 1: Rule Engine]              │
│                      ├── Duplicate check                 │
│                      ├── Threshold validation            │
│                      └── Time-window check               │
│                              │                           │
│                              ▼                           │
│                     [Layer 2: ML Anomaly Detection]      │
│                      ├── Isolation Forest score          │
│                      ├── GPS vs Weather cross-check      │
│                      └── Behavioral pattern matching     │
│                              │                           │
│                     ┌────────┴────────┐                  │
│                     │                 │                   │
│              [Score < 0.3]     [Score ≥ 0.3]             │
│              Auto-approve      Flag for review           │
│                  │                    │                   │
│                  ▼                    ▼                   │
│           [Instant Payout]    [Admin Dashboard]          │
│                               [Manual Review]            │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

### Why This Stack?

| Layer | Technology | Justification |
|-------|-----------|---------------|
| **Frontend** | React.js + PWA (Workbox) | Component-based, PWA-ready, massive ecosystem. Mobile-first responsive design. |
| **Backend** | Node.js + Express.js | Fast API development, async I/O for handling weather API polling, JS full-stack reduces context switching |
| **Database** | PostgreSQL | Relational data (policies, claims, users) with JSONB for flexible trigger configurations. ACID-compliant for financial data |
| **Cache** | Redis | Real-time trigger state caching, session management, rate limiting |
| **AI/ML** | Python (Flask microservice) — XGBoost, Scikit-learn, Prophet | Python is the standard for ML. Separate microservice keeps ML decoupled from the main API |
| **Weather API** | OpenWeatherMap (free tier) | 1,000 API calls/day free. Provides current weather, forecasts, and historical data |
| **AQI API** | CPCB / AQICN.org | Free, real-time AQI data for Indian cities |
| **Payment** | Razorpay Test Mode | UPI autopay mandates for weekly premium collection + instant UPI payouts. Sandbox available |
| **Auth** | Firebase Auth (OTP) | Phone-based OTP is the natural auth method for delivery partners. Firebase handles it at scale |
| **Hosting** | Vercel (frontend) + Railway/Render (backend) | Free tiers available. Auto-deploy from GitHub. CI/CD built-in |
| **CI/CD** | GitHub Actions | Automated testing, linting, and deployment on every push |
| **Monitoring** | Sentry (error tracking) | Free tier covers our needs. Real-time error monitoring |

### Architecture Diagram

```
┌─────────────────────────────────────────────────────────────────┐
│                        SYSTEM ARCHITECTURE                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   [Delivery Partner]                    [Admin/Insurer]         │
│        │                                     │                  │
│        ▼                                     ▼                  │
│   ┌──────────┐                        ┌──────────────┐         │
│   │ React PWA│                        │ Admin Portal │         │
│   │ (Mobile) │                        │   (React)    │         │
│   └────┬─────┘                        └──────┬───────┘         │
│        │                                     │                  │
│        └──────────────┬──────────────────────┘                  │
│                       ▼                                         │
│              ┌─────────────────┐                                │
│              │  API Gateway    │                                │
│              │  (Express.js)   │                                │
│              └───────┬─────────┘                                │
│         ┌────────────┼────────────┐                             │
│         ▼            ▼            ▼                             │
│  ┌────────────┐ ┌─────────┐ ┌──────────────┐                   │
│  │ Policy &   │ │ Trigger │ │ ML Service   │                   │
│  │ Claims API │ │ Monitor │ │ (Python/Flask)│                  │
│  └─────┬──────┘ └────┬────┘ └──────┬───────┘                   │
│        │              │             │                           │
│        ▼              ▼             ▼                           │
│  ┌──────────┐  ┌───────────┐  ┌──────────┐                     │
│  │PostgreSQL│  │  Redis    │  │ XGBoost  │                     │
│  │(Policies,│  │(Trigger   │  │ Prophet  │                     │
│  │ Claims)  │  │ State)    │  │ IsoForest│                     │
│  └──────────┘  └───────────┘  └──────────┘                     │
│        │              │                                         │
│        ▼              ▼                                         │
│  ┌───────────────────────────────────┐                          │
│  │         External APIs             │                          │
│  │  Weather │ AQI │ Razorpay │ News  │                         │
│  └───────────────────────────────────┘                          │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📅 Development Roadmap

### Phase 1: Ideation & Foundation (Weeks 1-2) — *Current Phase*
| Week | Deliverable | Status |
|------|------------|--------|
| W1 | Persona research, disruption analysis, premium model design | ✅ Complete |
| W1 | Tech stack finalization, repo setup, architecture design | ✅ Complete |
| W2 | README documentation (this document) | ✅ Complete |
| W2 | Minimal prototype — landing page + onboarding flow mockup | ✅ Complete |
| W2 | 2-minute strategy video | 🔄 In Progress |

### Phase 2: Automation & Protection (Weeks 3-4)
| Week | Deliverable | Priority |
|------|------------|----------|
| W3 | Registration system with OTP + KYC flow | P0 |
| W3 | Policy management — create, view, renew weekly policies | P0 |
| W3 | Dynamic premium calculation (XGBoost model v1) | P0 |
| W4 | Parametric trigger engine — integrate Weather + AQI APIs | P0 |
| W4 | Auto-claim initiation + payout system (Razorpay sandbox) | P0 |
| W4 | Claims management dashboard | P1 |

### Phase 3: Scale & Optimise (Weeks 5-6)
| Week | Deliverable | Priority |
|------|------------|----------|
| W5 | Advanced fraud detection (Isolation Forest + GPS validation) | P0 |
| W5 | Instant payout system (simulated UPI) | P0 |
| W6 | Intelligent dashboard — worker & admin views | P0 |
| W6 | Predictive analytics (next-week risk forecasting) | P1 |
| W6 | 5-minute demo video + final pitch deck | P0 |

---

## 🚨 Market Crash Compliance

*As per the Market Crash Scenario for Phase 1:*

This section will be updated based on the specific compliance requirements issued within 24 hours of the Phase 1 deadline. Our architecture is designed to be **modular** — any regulatory or compliance changes can be integrated without restructuring the core system, thanks to:

- **Microservice architecture**: Isolated services can be updated independently
- **Feature flags**: New compliance rules can be toggled without redeployment
- **Configurable trigger engine**: New parametric triggers or threshold changes can be added via config, not code

---

## 💡 Differentiators — Why GigShield Stands Out

| Feature | Traditional Insurance | GigShield |
|---------|----------------------|-----------|
| Claim filing | Manual, paper-based | **Zero-touch automatic** |
| Payout speed | 15-45 days | **< 2 hours** |
| Premium cycle | Monthly/Annual | **Weekly** (aligned with gig earnings) |
| Risk assessment | Generic demographics | **AI-driven, hyper-local** |
| Fraud detection | Post-claim manual review | **Real-time ML-powered** |
| Onboarding | Branch visit, 20+ documents | **2 minutes, phone + OTP** |
| Coverage trigger | Worker must prove loss | **Automated parametric verification** |

---

## 👥 Team

| Name | Role | Responsibility |
|------|------|---------------|
| TBD | Full Stack Lead | Frontend (React PWA), API development |
| TBD | Backend & DevOps | Express.js APIs, PostgreSQL, CI/CD, deployment |
| TBD | AI/ML Engineer | Premium model, fraud detection, predictive analytics |
| TBD | Product & Design | UX research, persona development, UI design, video |

---

## 📎 Links

| Resource | Link |
|----------|------|
| 📂 Repository | *[This Repository]* |
| 🎬 2-Minute Video | *[To be uploaded]* |
| 📄 Prototype | *[To be linked]* |

---

<div align="center">

### *Built with ❤️ for India's 10 million+ delivery heroes*

**DEVTrails 2026 — Guidewire University Hackathon**

</div>
