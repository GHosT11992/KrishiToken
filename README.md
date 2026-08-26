## 🌾 KrishiToken (कृषि-टोकन) | Smart Farmer Slot Booking & Real-Time Queue Management System

> **Smart India Hackathon Submission**
> **Problem Statement ID:** ID26032
> **Problem Statement Title:** Farmers often face long waiting times, lack of information regarding procurement schedules, and uncertainty about procurement status.
> **Theme:** Agriculture, Food Technology & Rural Development
> **PS Category:** Software

---

## 👥 Team Details — Team [Devil Genius]
---

## 📌 Executive Summary

Agricultural procurement centers (Mandis / Paddy & Crop Collection Centers) in India face massive traffic congestion during peak harvest seasons. Farmers often travel long distances only to endure prolonged waiting times (often 1 to 3 days), lack visibility into daily procurement capacities, and suffer from uncertainty regarding crop acceptance and payment disbursal.

**KrishiToken** is an end-to-end, multi-channel platform that digitizes procurement schedules, automates token generation, provides live queue tracking, and provides real-time updates via SMS and WhatsApp. Built to bridge the digital divide in rural India, it streamlines Mandi operations, minimizes crop spoilage, and guarantees direct benefit transfer (DBT) payment visibility.

---

## ✨ Core Features & SIH Innovation Highlights

### 🧑‍🌾 1. Smart Registration & Capacity-Aware Slot Booking

* **Aadhaar & Farmer ID Integration:** Verifies landholdings and eligibility through seamless integration with PM-KISAN / State Land Record databases.
* **Dynamic Capacity-Based Scheduling:** Algorithmically calculates daily intake limits per Mandi (based on weighbridge capacity and labor strength) to prevent overbooking.
* **Omnichannel Access for Rural Adoption:**
* **Smartphones:** Web & App interface (React / React Native).
* **Feature Phones / Offline:** Interactive SMS, USSD codes, and IVR toll-free booking.



### ⏳ 2. Real-Time Queue & Mandi Management

* **Digital Token & QR Verification:** Generates a unique QR-coded digital pass upon slot confirmation.
* **Live Counter Status:** Displays active token calls on physical Mandi digital boards and within the app.
* **Adaptive Delay Adjustments:** Auto-adjusts downstream slots in real-time during weather delays or operational lags, sending instant alerts to incoming farmers.

### 📲 3. Multilingual SMS & Voice Alerts

* **Turn Alerts:** Automated localized SMS alerts sent when a farmer's turn is within 5–10 tokens.
* **Vernacular Support:** Local language support (Hindi, Tamil, Telugu, Punjabi, Bengali, Marathi, etc.) for both voice IVR and text messages.

### 💳 4. Procurement & Payment Status Tracking

* **IoT Weighbridge Sync:** Direct weight input integration to eliminate manual tally sheet manipulation.
* **Transparent Lifecycle Tracker:**

$$\text{Slot Booked} \longrightarrow \text{Mandi Entry} \longrightarrow \text{Quality Check} \longrightarrow \text{Weighment} \longrightarrow \text{Invoice Generated} \longrightarrow \text{DBT Disbursed}$$


* **Payment Grievance Redressal:** Built-in ticketing module for tracking delayed Direct Benefit Transfers (DBT) to bank accounts.

---

## 🛠 Tech Stack

* **Frontend:** React.js, Tailwind CSS (Admin / Web Portal) & React Native / Flutter (Farmer App)
* **Backend:** Node.js (Express) / Python (FastAPI)
* **Database & Caching:** PostgreSQL (Relational Data), Redis (Real-Time Token Processing)
* **Communication Gateways:** Twilio / Gupshup / Exotel (SMS & IVR Integration), Firebase Cloud Messaging (FCM)
* **Integrations:** Mock APIs for PM-KISAN, PFMS (Public Financial Management System), and Aadhaar e-KYC
* **DevOps & Cloud:** Docker, NGINX, AWS / GCP Cloud Platforms

---

## 📊 SIH Impact Assessment & Expected Outcomes

| Metric | Traditional Mandi Process | KrishiToken Implementation |
| --- | --- | --- |
| **Mandi Waiting Time** | 8 to 36 Hours | **30 to 45 Minutes** |
| **Crowd & Traffic Congestion** | Heavy Bottlenecks & Chaos | **Smooth 15-Minute Staggered Arrivals** |
| **Payment Visibility** | Manual / Opaque (15-45 Days) | **Step-by-Step Live Tracking (1-3 Days DBT)** |
| **Mandi Capacity Utilization** | Unbalanced (Overcrowded / Idle) | **Optimized & Load-Balanced Across District** |
| **Operational Spoilage Loss** | High (Exposure to rain/heat) | **Near Zero** |

---



## 📄 License

Developed for **Smart India Hackathon (SIH)** under the open-source **MIT License**.
