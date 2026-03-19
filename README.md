<div align="center">

# GigShield

### AI-Powered Parametric Income Protection for Grocery & Delivery Partners

*When the city shuts down, your earnings don't .*

</div>

<div align="center">

[![Phase](https://img.shields.io/badge/Phase-1%20%7C%20Ideation%20%26%20Foundation-blue)](https://github.com/your-team/gigshield)
[![Persona](https://img.shields.io/badge/Persona-Q--Commerce%20Delivery%20(Delhi--NCR)-DR9750)]()
[![Coverage](https://img.shields.io/badge/Coverage-Loss%20of%20Income%20Only-green)]()
[![Pricing](https://img.shields.io/badge/Pricing-Weekly%20Model-purple)]()
[![City](https://img.shields.io/badge/City-Delhi--NCR-red)]()
[![Triggers](https://img.shields.io/badge/Triggers-4%20Parametric%20Events-orange)]()
[![AI](https://img.shields.io/badge/AI-Powered%20Pricing%20%2B%20Fraud%20Detection-yellow)]()
[![Stack](https://img.shields.io/badge/Stack-React%20PWA%20%2B%20Node.js%20%2B%20SQLite-blue)]()

</div>

---


## Problem Statement

India has **10 million+ gig delivery workers** across Blinkit, Zepto, Instamart, Zomato, and Swiggy. These workers earn ₹500–₹1,200 daily with **zero financial safety net**.

When external disruptions strike — extreme heat, severe pollution, heavy rain, or sudden zone restrictions — these workers **cannot work. No work = no income.**

> **GigShield** provides **AI-powered parametric insurance** that automatically detects disruptions and instantly compensates delivery partners for lost income — **no claims forms, no delays, no middlemen.**

---

##  What We Cover vs. What We Don't

| Covered | Not Covered |
|-----------|---------------|
| Loss of income from extreme weather | Health or medical insurance |
| Loss of income from severe pollution (AQI) | Life insurance |
| Loss of income from curfews / bandhs | Accident or injury coverage |
| Loss of income from zone closures | Vehicle repair or breakdown |

---

##  Our Persona — Q-Commerce Delivery Partner (Delhi-NCR)

### Why Q-Commerce, Why Delhi-NCR

| Factor | Justification |
|--------|---------------|
| **Highest hyperlocal sensitivity** | Blinkit/Zepto/Instamart deliver within 10-20 minutes per order. Weather events collapse this model faster than any other delivery type — one heavy rain burst empties the queue instantly. |
| **Short, intense shifts** | Riders work 2-4 hour shifts, often evening peak. A disruption during a 3-hour shift wipes out a large % of daily income — the payout calculus is clearer and more credible. |
| **Delhi-NCR has all 4 major disruptions** | Extreme heat (March–June), severe AQI (Oct–Jan), monsoon rain (July–Sept), and frequent zone restrictions / VVIP movements. Every trigger fires here at least once per season. |
| **Dense, small delivery zones** | A single neighborhood can have drastically different weather or pollution than a neighboring one. This makes hyperlocal parametric triggers real and meaningful, not abstract. |
| **Earnings volatility is highest here** | Delhi-NCR delivery partners report income swings of ₹300–₹1,100 per day depending on conditions. The pain gap is biggest. |

### Persona Profile — "Ankit"

| Attribute | Detail |
|-----------|--------|
| **Name** | Ankit Sharma |
| **Age** | 24 years |
| **Platform** | Blinkit / Zepto |
| **City** | South Delhi (Pin Codes: 110017, 110049, 110065) |
| **Daily earnings** | ₹650–₹1,100 (avg ₹850) |
| **Weekly earnings** | ₹4,550–₹7,700 |
| **Shift pattern** | 4 PM – 9 PM (evening peak, 5 days/week) |
| **Vehicle** | Two-wheeler (personal) |
| **Key risks** | Heat waves (April–June), AQI spikes (Nov–Jan), sudden VVIP movements |
| **Financial buffer** | < ₹1,500 in savings |
| **Digital literacy** | Comfortable with UPI, Google Maps, WhatsApp. Uses phone for all work communication. |

---

##  Day in the Life — Pain Scenario

> **Monday, June 15 — Delhi-NCR**
>
> Ankit starts his evening shift at 4 PM. By 6 PM, a sudden dust storm hits South Delhi. The sky goes dark. Blinkit app shows "Limited slots available in your area." Orders dry up. He rides through the storm for 2 hours and makes ₹120 instead of his usual ₹700. He goes home frustrated, knowing there's nothing he can do for the lost ₹580.
>
> **GigShield fixes this.** When the weather API detects storm conditions in Ankit's PIN code during his insured shift window, the system fires a trigger. It validates his shift eligibility, calculates his estimated lost income, and sends a UPI payout — all without Ankit filing a single claim.

---

## Real-World Persona Scenarios

These scenarios are based on real conditions that delivery partners across India face every year. Each one maps directly to a GigShield parametric trigger.

### Scenario 1: Heavy Monsoon Rainfall 🌧️

> **Who:** Ravi Kumar — Food Delivery Partner, Zomato
> **City:** Bengaluru | **Date:** July 15
>
> **The Situation:**
> IMD issues a Red Alert — rainfall exceeds 65mm in 3 hours across South Bengaluru. Roads flood. Ravi's usual delivery route through Indiranagar becomes impassable. The Zomato app shows "Limited delivery zones available." Ravi tries for 2 hours, completes 3 orders instead of his usual 18, and earns ₹120 instead of ₹950.
>
> **Income Lost:** ₹830 (full day of potential earnings)
>
> **GigShield Response:**
> OpenWeatherMap API detects rainfall threshold breach in Ravi's declared delivery zones → Parametric trigger fires → GigShield validates Ravi's active shift window and coverage tier → ₹850 credited to Ravi's UPI within 2 hours. **Zero forms. Zero calls. Zero waiting.**

---

### Scenario 2: Extreme Heat Wave 🔥

> **Who:** Aamir Khan — Food Delivery Partner, Swiggy
> **City:** Delhi | **Date:** May 3
>
> **The Situation:**
> Temperature hits 47°C in Delhi-NCR. NDMA issues a heat advisory recommending avoidance of outdoor work between 12 PM and 5 PM. Swiggy platform reduces order assignments in afternoon slots. Aamir, who normally works 10 AM to 10 PM split shifts, can only operate 4 hours safely — from 6 AM to 10 AM and 7 PM to 9 PM. He loses 6 hours of income.
>
> **Income Lost:** ₹570 (6 hours of estimated earnings lost)
>
> **GigShield Response:**
> OpenWeatherMap real-feel temperature crosses 45°C threshold during Aamir's afternoon shift window → GigShield calculates proportional payout based on hours lost → ₹570 credited via UPI. GigShield also sends a push notification: *"Heat advisory active. Your coverage is active. Rest safe — we've got you covered."*

---

### Scenario 3: Sudden Curfew / Zone Restriction 🚫

> **Who:** Priya Sharma — Delivery Partner, Instamart
> **City:** Pune | **Date:** September 22
>
> **The Situation:**
> A law-and-order situation emerges in Hinjewadi. The state government imposes a sudden 14-hour curfew from 8 PM. All movement is restricted. Priya's delivery zone falls within the restricted area. The Instamart app immediately shows "Services suspended in your area." Priya cannot work at all that day.
>
> **Income Lost:** ₹850 (full day)
>
> **GigShield Response:**
> Curfew alert is detected via government advisory feed (mocked in Phase 1) → GigShield identifies all active policies covering PIN codes in the Hinjewadi zone → For each insured partner, the zone restriction trigger fires → Full-day payout of ₹850 sent via UPI. Priya wakes up to a payment notification, not a loss.

---

### Scenario 4: Severe Air Pollution (AQI > 400) 🏭

> **Who:** Suresh Patel — Grocery Delivery Partner, Blinkit
> **City:** Delhi-NCR | **Date:** November 10
>
> **The Situation:**
> AQI in Gurugram crosses 450 — GRAP Stage 4 restrictions are imposed. The Delhi government issues an advisory urging residents to avoid outdoor exertion. Blinkit reduces delivery slots across affected zones. Suresh, who works a 4 PM to 9 PM evening shift, sees order volume drop by 70%. He earns ₹180 instead of his usual ₹800.
>
> **Income Lost:** ₹620 (proportional to reduced shift productivity)
>
> **GigShield Response:**
> CPCB AQI API detects AQI breach above 400 in Suresh's delivery zone for 3+ consecutive hours → GigShield trigger fires during his 4 PM–9 PM shift → Proportional payout calculated based on estimated productivity drop → ₹620 credited via UPI. GigShield sends a notification: *"Your zone had severe air quality today. A payout of ₹620 has been credited to protect your earnings."*

---

### How These Scenarios Map to Our Triggers

| Scenario | Persona | Trigger | Data Source | Payout |
|----------|---------|---------|-------------|--------|
| Heavy Rain | Ravi (Bengaluru) | Heavy Rainfall | OpenWeatherMap | Full shift |
| Heat Wave | Aamir (Delhi) | Extreme Heat | OpenWeatherMap | Proportional |
| Curfew | Priya (Pune) | Zone Restriction | Advisory Feed | Full day |
| AQI Spike | Suresh (Delhi-NCR) | Severe AQI | CPCB/AQICN | Proportional |

---

## Product Workflow

```
[Ankit Registers] → [AI Risk Profile] → [Weekly Policy Created] → [Active Monitoring]
                                                                              ↓
                                                               [Trigger Detected]
                                                                     ↓
                                                         [Fraud Validation]
                                                                   ↓          ↓
                                                           [Auto Payout]  [Flag for Review]
                                                                   ↓
                                                         [Dashboard Updated]
```

### Step-by-Step Flow

| Step | What Happens | Who's Involved |
|------|-------------|----------------|
| **1. Registration** | Delivery partner signs up via phone + OTP. Links Blinkit/Zepto partner ID (mocked for Phase 1). Declares delivery zones and shift pattern. | Partner |
| **2. AI Risk Profiling** | System scores the partner based on: delivery PIN code (historical disruption data), declared shift hours, city risk index, seasonal factor. Assigns a risk tier. | GigShield AI |
| **3. Policy Creation** | Weekly policy auto-generated. Premium calculated (₹49–₹99/week). Coverage cap set based on declared earnings band. Auto-debit scheduled via UPI. | GigShield |
| **4. Active Monitoring** | Weather API, AQI API, and government advisory feeds are monitored in real time for the partner's PIN codes and shift windows. | GigShield Engine |
| **5. Trigger Fires** | A defined disruption threshold is breached during an insured shift. System checks: is this partner in the affected zone? Is it during their active window? | GigShield Engine |
| **6. Fraud Validation** | Quick check: is this a duplicate claim? Is the location consistent? Was the partner actually inactive? | Fraud Engine |
| **7. Instant Payout** | If valid, payout is calculated (full-day or proportional) and sent via UPI. Partner gets SMS/push notification. | GigShield + Payment |
| **8. Dashboard** | Partner sees: active coverage, today's risk level, payout history, protected earnings total. | Partner + Admin |

---

## Weekly Premium Model 💰

### Why Weekly

Gig delivery partners track and receive earnings on a **weekly settlement cycle**. Weekly premiums match their mental model of money — they can pay ₹79 every Sunday from the previous week's earnings without cash-flow stress.

### Coverage Tiers

| Tier | Weekly Premium | Coverage Cap (Max Payout/Week) | Daily Protected Earnings | Who It's For |
|------|---------------|--------------------------------|-------------------------|-------------|
|  **Basic** | ₹49/week | ₹3,500/week | ₹500/day | Low-risk zones, non-monsoon months, stable neighborhoods |
|  **Standard** | ₹79/week | ₹5,500/week | ₹785/day | Metro cities, mixed disruption risk, evening-shift workers |
|  **Premium** | ₹99/week | ₹7,000/week | ₹1,000/day | High-risk zones, monsoon/heat season, full-day shift workers |

### Premium Calculation (AI Pricing Model)

```
Weekly_Premium = Base_Premium × Zone_Risk × Season_Factor

Where:
  Base_Premium   = ₹49 (Basic tier minimum)
  Zone_Risk      = Pulled from historical disruption frequency per PIN code
                   (0.8 = low-disruption zone, 1.2 = high-disruption zone)
  Season_Factor  = 1.0 (Oct–Feb) to 1.5 (Jun–Sep monsoon)
                   1.3 (Mar–May heat season)
                   1.2 (Nov–Jan pollution season)
```

**Example — Ankit, South Delhi, June (monsoon season):**
```
Zone_Risk (110017, South Delhi)   = 1.2
Season_Factor (June, monsoon)      = 1.5
Base_Premium                       = ₹49

Weekly_Premium = 49 × 1.2 × 1.5 = ₹88.2 ≈ ₹89/week (Standard tier)
```

**Example — Priya, Dwarka, January (pollution season):**
```
Zone_Risk (110075, Dwarka)        = 1.1
Season_Factor (January, AQI)      = 1.2
Base_Premium                       = ₹49

Weekly_Premium = 49 × 1.1 × 1.2 = ₹64.68 ≈ ₹65/week (Standard tier)
```

### Data Sources for Premium Multipliers

| Factor | Source | Phase 1 Approach |
|--------|--------|-----------------|
| **Zone_Risk** | Historical IMD disruption data + CPCB AQI frequency per PIN | Pre-loaded dataset for Delhi-NCR PIN codes |
| **Season_Factor** | IMD seasonal calendar + known disruption months | Static seasonal lookup table for Phase 1 |
| **Phase 2+** | Real-time API feeds, partner claim history, shift pattern analysis | Upgrades to live API integration |

---

## Parametric Triggers (Phase 1 — 4 Triggers)

Each trigger is backed by a **public, tamper-proof data source** and maps directly to income loss.

| # | Trigger | Data Source | Threshold | Payout Logic |
|---|---------|------------|-----------|-------------|
| 1 | **Extreme Heat** | OpenWeatherMap API (real-feel temp) | > 45°C real-feel for 2+ consecutive hours during insured shift | Full shift payout if disruption lasts ≥ 60% of shift; proportional if less |
| 2 | **Severe Air Pollution** | CPCB / AQICN.org (AQI data) | AQI > 400 (Severe) for 3+ hours during shift | Proportional payout based on hours affected |
| 3 | **Heavy Rainfall / Storm** | OpenWeatherMap API (precipitation rate) | Rainfall ≥ 15mm/hour OR IMD Red/Orange alert for partner's district | Full shift payout |
| 4 | **Zone Restriction / Curfew** | News NLP (mocked via curated alert system for Phase 1) | Official movement restriction declared for partner's PIN code | Full-day payout |

### Trigger Decision Matrix

```
For every registered partner, at every shift window:

Is the current time inside an active shift window?
    NO  → No monitoring, no payout eligibility
    YES → Check all 4 trigger APIs for partner's PIN codes
           ANY trigger threshold breached?
               NO  → No payout
               YES → Run fraud validation
                       Pass → Auto-trigger payout
                       Fail → Flag for admin review
```

### Why Phase 1 Stops at 4 Triggers

| Trigger | Frequency in Delhi-NCR | Demo Credibility |
|---------|----------------------|-----------------|
| Extreme Heat | 15-20 days/year (Mar–Jun) | High |
| Severe AQI | 30-40 days/year (Oct–Jan) | High  |
| Heavy Rain | 50-60 days/year (Jul–Sep) |  High  |
| Zone Restriction | 10-15 events/year |  Medium — harder to demo without live news feed |

Adding a 5th trigger (flooding) and advanced news NLP is a Phase 2 move.

---

## 🤖 AI Integration Strategy

### AI Scope — "AI-Informed, Not AI-Heavy"

### AI Component 1: Dynamic Risk Scoring (Pricing Engine)

**Phase 1 approach:** Rule-based scoring function in Node.js using weighted feature inputs.

| Input | Weight | Source |
|-------|--------|--------|
| Zone disruption history | 40% | Pre-loaded IMD/CPCB historical dataset per PIN code |
| Seasonal risk factor | 30% | Static lookup table based on IMD calendar |
| Shift timing risk | 20% | Evening/night shifts have different exposure profiles |
| Partner tenure / claim history | 10% | Simulated for Phase 1 |

**Output:** Risk tier (Basic/Standard/Premium) → Weekly premium.

**Phase 2 upgrade:** Replace with XGBoost model trained on real claim data. SHAP values for explainability.

### AI Component 2: Fraud Detection 

**Phase 1 approach:** Rule-based validation before payout.

| Check | Logic | Action on Failure |
|-------|-------|-------------------|
| **Duplicate trigger check** | Same partner, same trigger, within 24 hours → reject duplicate | Auto-reject + log |
| **Threshold validation** | API data must confirm breach; no payout on borderline values | Auto-reject |
| **Shift window check** | Trigger must occur during partner's registered shift hours | Auto-reject |
| **Location plausibility** | Partner declared PIN must match trigger zone | Flag for review |

**Phase 2 upgrade:** Add GPS cross-check, Isolation Forest anomaly scoring, and behavioral pattern matching.

### AI Component 3: Explainability Layer 

Every premium quote and payout decision includes a plain-language reason shown to the partner:

> **"Your weekly premium is ₹89 because June is monsoon season in South Delhi, and historical weather data shows high disruption risk in your zone."**

> **"Your payout of ₹700 was approved because a rainfall threshold was crossed in your area (PIN 110017) during your 6 PM–9 PM shift on June 15."**


---

## 🛠️ Tech Stack — Phase 1 Focused

### Why This Stack

| Layer | Technology | Phase 1 Choice | Justification |
|-------|-----------|----------------|---------------|
| **Frontend** | React.js + PWA (Workbox) |  Keep | Component-based, PWA-ready. Fastest path to a mobile-first UI that works on Ankit's low-end Android phone. |
| **Backend** | Node.js + Express.js |  Keep | Fast API development. JavaScript end-to-end reduces context switching for a small team. |
| **Database** | SQLite (Phase 1) → PostgreSQL (Phase 2) |  Keep | SQLite needs zero setup — ships with the app. Perfect for a 2-week prototype. No Docker or cloud DB needed to get started. |
| **AI Pricing** | Node.js scoring function (Phase 1) |  Keep | Avoids a separate Python microservice for Phase 1. One AI script in Python can be imported if needed. |
| **Weather API** | OpenWeatherMap (free tier) |  Keep | 1000 calls/day free. Covers Phase 1 demo easily. |
| **AQI API** | AQICN.org / CPCB |  Keep | Real Indian city AQI data. Mocked for Phase 1 demo. |
| **Auth** | Simple OTP via MSG91 or mocked OTP |  Simplify | Firebase adds unnecessary third-party complexity for Phase 1. Mock OTP is fine for demo. |
| **Payments** | Simulated UPI payout display |  Simplify | No real payments in Phase 1. Show the payout flow as a mock transaction. |
| **Hosting** | Vercel (frontend) + Railway (backend) |  Keep | Free tiers. Works for Phase 1. |
| **Cache** | In-memory (Phase 1) → Redis (Phase 2) |  Cut Redis | No real-time caching needed yet. |
| **ML Microservice** | Not yet |  Cut | Phase 1 scoring runs in-process. Separate service adds Docker, networking, and deployment overhead. |
| **CI/CD** | GitHub Actions |  Cut | Not needed for a 2-week prototype. |
| **Monitoring** | Sentry |  Cut | Not needed at this stage. |
| **API Gateway** | Express.js built-in routing |  Keep | No need for a separate gateway in Phase 1. |

### Phase 1 vs Phase 2 Tech Comparison

| Component | Phase 1 | Phase 2 |
|-----------|---------|---------|
| Database | SQLite | PostgreSQL |
| AI Pricing | Rule-based scoring in Node.js | XGBoost model (Python) |
| Fraud Detection | Rule-based validation | Isolation Forest + GPS cross-check |
| Weather API | OpenWeatherMap (mocked for demo) | Live API with webhook |
| AQI API | Mocked for demo | Live CPCB/AQICN feed |
| Payments | Simulated payout flow | Razorpay UPI sandbox |
| Auth | Mock OTP | Real OTP via MSG91/Twilio |
| Monitoring | Console logs | Sentry + structured logging |
| Caching | In-memory | Redis |
| News/Advisory Feed | Curated mock alerts | News NLP (median of 3 sources) |

---

##  System Architecture

```
┌──────────────────────────────────────────────────────────┐
│                    DELIVERY PARTNER                      │
│                   (Mobile PWA — Ankit)                   │
└─────────────────────────┬────────────────────────────────┘
                          │ HTTPS
                          ▼
┌──────────────────────────────────────────────────────────┐
│              API SERVER (Express.js)                     │
│  ┌─────────────┐  ┌──────────────┐  ┌────────────────┐   │
│  │ /register   │  │ /policy      │  │ /claim/trigger │   │
│  │ /auth/otp   │  │ /premium     │  │ /payout        │   │
│  │ /profile    │  │ /dashboard   │  │ /fraud-check   │   │
│  └─────────────┘  └──────────────┘  └────────────────┘   │
│                          │                               │
│         ┌────────────────┼────────────────┐              │
│         ▼                ▼                ▼              │
│  ┌─────────────┐  ┌──────────────┐  ┌────────────────┐   │
│  │ SQLite DB   │  │ AI Scorer    │  │ Trigger Engine │   │
│  │ Policies    │  │ (Risk Pricing│  │ (Weather/AQI   │   │
│  │ Partners    │  │  Scoring Fn) │  │  Monitor)      │   │
│  │ Claims      │  │              │  │                │   │
│  └─────────────┘  └──────────────┘  └────────────────┘   │
│                          │                               │
│                          ▼                               │
│                 ┌─────────────────┐                      │
│                 │ External APIs   │                      │
│                 │ OpenWeatherMap  │                      │
│                 │ AQICN (AQI)     │                      │
│                 │ Advisory Feed   │                      │
│                 └─────────────────┘                      │
└──────────────────────────────────────────────────────────┘
```

### Data Flow During a Trigger Event

```
1. Trigger Engine polls weather/AQI APIs every 15 minutes
         ↓
2. Threshold breached for PIN 110017 at 6:15 PM
         ↓
3. Find all active policies for PIN 110017 with shift window covering 6 PM
         ↓
4. For each matching partner, run fraud validation checks
         ↓
5. Fraud pass → calculate payout → log claim → update dashboard
   Fraud fail → flag for admin review → notify partner of hold
         ↓
6. Send SMS/push notification to partner
         ↓
7. Partner sees payout in dashboard
```

### Database Schema (Phase 1 — SQLite)

```
partners
  - id, phone, name, platform_id, pin_codes[], shift_start, shift_end, risk_tier, created_at

policies
  - id, partner_id, tier, weekly_premium, coverage_cap, status, start_date, end_date

triggers
  - id, type, pin_code, severity, threshold_breached, triggered_at, api_source

claims
  - id, partner_id, trigger_id, payout_amount, status, processed_at, fraud_check_passed

premium_history
  - id, partner_id, week_start, premium_charged, payout_received
```


##  Roadmap

| Phase  | Focus | 
|-------|-------|
| Phase 1  | README, mock prototype, strategy video |
| Phase 2 | Real APIs, trigger engine, auto-payout | 
| Phase 3  | ML models, fraud detection, pitch + demo | 

---

## Phase 1 — Ideation & Foundation

| Week | Tasks |
|------|-------|
| **W1** | Repo setup → DB schema → Express skeleton → React PWA scaffold → AI pricing function → Trigger engine (mock) → End-to-end mock |
| **W2** | README final → Polish UI → Video script → Record + edit → Submit |

**Must ship:** README, mock demo

---

## Phase 2  — Core Product

| Week | Tasks |
|------|-------|
| **W3** | Real OTP → Partner registration → Live OpenWeatherMap + AQI → Trigger engine (live) → Payout calculator → Fraud validation |
| **W4** | Dashboard (live data) → UPI payout display → Admin panel → Deploy → Bug fixes → Demo run-through → Submit |

**Must ship:** Live APIs, 2+ triggers fire in demo, deployed URLs

---

## Phase 3  — Intelligence + Polish

| Week | Tasks |
|------|-------|
| **W5** | XGBoost pricing + SHAP → Isolation Forest fraud → GPS cross-check → Fraud review UI → Prophet risk forecast → Zone heatmap → Analytics charts → B2B2C API → Security audit |
| **W6** | Demo recording × 3 → Pitch deck → Code review → Final polish → Submit |

**Must ship:** ML in production, demo, pitch deck, clean codebase

---

##  Why GigShield ?

| Feature | Traditional Insurance | GigShield |
|---------|----------------------|-----------|
| Claim filing | Paper forms, 15-45 day wait | **Zero-touch, auto-trigger** |
| Payout speed | Weeks | **Same day / within hours** |
| Premium model | Monthly / annual | **Weekly** (matches gig earnings) |
| Risk assessment | Generic demographics | **AI-driven, hyperlocal, PIN-level** |
| Fraud detection | Post-claim manual review | **Real-time rule + ML validation** |
| Onboarding | Branch visit, 20 documents | **2 minutes, phone + OTP** |
| Transparency | Complex policy documents | **Plain-language reasons for every decision** |
| Trigger proof | Worker must prove loss | **Parametric data validates automatically** |

---

##  GitHub Repository

**Repository:** [github.com/your-team/gigshield](https://github.com/N-Jishnu/gigshield)

```
gigshield/
├── README.md                    # Project documentation
├── SPEC.md                      # Product specification
├── frontend/                    # React PWA
│   ├── src/
│   │   ├── components/         # UI components
│   │   ├── pages/              # Onboarding, Dashboard, Profile
│   │   ├── services/          # API calls
│   │   └── App.jsx
│   ├── public/
│   │   └── manifest.json       # PWA manifest
│   └── package.json
├── backend/                    # Express.js API
│   ├── routes/                 # /register, /policy, /trigger, /payout
│   ├── models/                # SQLite schema
│   ├── services/
│   │   ├── scoring.js         # AI pricing function
│   │   ├── trigger.js         # Trigger engine
│   │   └── fraud.js           # Fraud validation
│   ├── data/
│   │   ├── zones.js           # Delhi-NCR PIN risk data
│   │   └── seasons.js         # Seasonal risk lookup
│   └── server.js
├── ml/                         # Python ML scripts (Phase 2+)
│   ├── pricing_model.py       # XGBoost pricing
│   └── fraud_model.py         # Isolation Forest
├── docs/                       # Additional docs
│   ├── architecture.md
│   └── api-spec.md
└── .github/
    └── workflows/             # CI/CD (Phase 2+)
```

