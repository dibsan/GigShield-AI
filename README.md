# GigShield AI: Parametric Income Protection  
### AI-Powered Insurance for India’s Q-Commerce Partners  


---

##  1. Project Inspiration & Requirement

India’s platform-based delivery economy (Zepto, Blinkit, etc.) runs on gig workers. However, these workers face a major financial risk:

- During extreme weather or social disruptions, **“Dark Stores” shut down**
- This leads to a **20–30% loss in monthly income**
- There is **no protection for lost working hours**

###  Our Solution
**GigShield AI** acts as a **“Digital Umbrella”**   
A parametric insurance system that:

- Detects disruption events automatically  
- Triggers **instant payouts**  
- Protects **income**, not just accidents  

---

##  2. Persona & Workflow

### Persona: Arjun (24, Delivery Partner)

**Scenario:**  
Arjun is working at a Zepto hub in Mumbai. A sudden monsoon cloudburst halts operations, causing him to lose 4 hours of peak earnings.

###  Workflow

1. **Onboarding** → Signs up via web app  
2. **Activation** → Pays weekly premium  
3. **Monitoring** → System tracks weather at hub location  
4. **Trigger** → Rainfall > 15 mm/hr detected  
5. **Payout** → Instant UPI transfer after AI validation  

---

##  3. Weekly Premium & Parametric Model

###  Why a Web Platform?

- No app download (low storage usage)
- Works on budget smartphones
- Single dashboard for users + admins

###  Premium Formula
Premium = (P_risk × E_avg) + δ


Where:
- `P_risk` → Probability of disruption  
- `E_avg` → Average hourly earnings  
- `δ` → Platform/admin fee  

---

###  Parametric Triggers

**Environmental:**
- Rainfall > 15 mm/hr  
- AQI > 400  
- Temperature > 45°C  

**Social:**
- Curfews  
- Section 144 restrictions  

---

##  4. AI/ML Integration

###  Dynamic Risk Assessment
- Uses **Random Forest Regressor**
- Predicts disruption probability per zone
- Adjusts premiums weekly

###  Fraud Detection

-  Location validation using GPS  
-  Detects “ghost workers” using **Isolation Forest**  
- Flags abnormal activity patterns  

---

## 🛠️ 5. Tech Stack

| Layer        | Technology |
|-------------|-----------|
| Frontend    | React.js + Tailwind CSS |
| Backend     | FastAPI (Python) |
| Database    | PostgreSQL + Redis |
| AI/ML       | Scikit-learn, Pandas |
| APIs        | OpenWeatherMap API |
| Payments    | Razorpay Sandbox |

---

##  Key Features

-  Instant payout system  
-  Real-time weather monitoring  
-  AI-powered risk modeling  
-  Fraud detection engine  
-  Mobile-first responsive design  

---

##  Impact

- Protects gig workers’ income stability  
- Builds financial resilience  
- Scales across India’s growing Q-commerce ecosystem  

---

##  Future Scope

- Integration with multiple delivery platforms  
- Personalized insurance plans  
- Expansion to other gig sectors (ride-sharing, logistics)  
- Advanced ML models for hyperlocal prediction  

---

##  Team Vision

To build a **financial safety net for India’s gig economy**, ensuring that no worker loses income due to factors beyond their control.

---
