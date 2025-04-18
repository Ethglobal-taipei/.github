# 🌐 ADMOJO Protocol (SEEKING GRANTS FOR PHASE1 Development)

**Smarter Ads. Verified Views. Real Engagement.**

ADMOJO Protocol is a decentralized bridge between **Advertising Companies (ACs)** and **Real World Ad Space Owners (ASPs)** — powered by **DePIN**, on-chain incentives, and **cryptographically verified real-time engagement metrics**.

We transform physical ads into secure, verifiable **Real World Assets (RWAs)** — democratizing advertising with transparency, fairness, and trust.

> Say goodbye to opaque ad spend and unverifiable impressions.

---

## 📸 Our Phase-1 progress:

### 💻 The UI
![WhatsApp Image 2025-04-06 at 06 03 24 (1)](https://github.com/user-attachments/assets/a3a2dee2-f39b-4e58-8e0d-de6630502c4e)


### 🔌 The Module
![tapnfc](https://github.com/user-attachments/assets/eaa46a7c-238c-49b8-9807-832e9cd3330e)



### 🧠 Proof of Views Algorithm in Action
https://github.com/user-attachments/assets/3d5c1920-0f42-4b53-b5f1-8830150adf55


---

## 🚀 Modules Breakdown

### 1. 📸 `admojo_web_server` — Proof of Views Engine

> **Goal:** Quantify genuine human engagement with physical ads.

- **ESP32-CAM** streams MJPEG video over Wi-Fi
- Uses **GoCV + OpenCV (SSD + ResNet DNN)** for face detection
- Aggregates viewer counts every 5 minutes
- Sends metrics to an off-chain oracle → on-chain smart contracts

**Highlights**:
- Dynamic IP support for seamless connectivity
- IoU filtering to avoid duplicate detection
- Live bounding-box debug feed

> _Ads aren’t just visible — they’re verifiable._

---

### 2. 📲 `admojo_nfc_module` — Proof of Taps IoT Writer

> **Goal:** Capture active user engagement through NFC taps.

- Powered by **ESP32 WROOM** + **PN532** (SPI)
- Deep sleep enabled for ultra-low power consumption
- Campaign URLs fetched dynamically & securely
- NFC tags written with **NDEF-formatted MiFare Classic**
- PN532 powered down post-write to prevent interference

**Security**:
- Cryptographic write control
- Unique sector keys + tag locking
- ADMOJO-signed firmware

> _Passive views show interest; taps prove intent._

---

### 3. 🌍 `web-app (Campaign Hub)` — Ad Management & Token Staking

> **For Advertisers:**

- Stake **ADC tokens** to launch campaigns
- Browse ASP locations with:
  - Real-time traffic analytics
  - Proof-of-View & Tap ratios
- Schedule ad slots via map interface
- Smart contracts auto-distribute tokens based on verified engagement

**Stack**:
- `Next.js` + `TailwindCSS`
- Map integration
- Metal API for token logic

---

### 4. 🎯 `web-app (User Engagement)` — Rewards & Verification

> **Flow:**

- Users tap NFC-enabled ads → redirected to campaign mini-site
- Engage with rewards, giveaways, tokens
- Sybil-resistance via **World App Mini Apps**
- Verified taps logged securely with **ZK-proofs**

**Why it matters**:
- Filters fraudulent interactions
- Ensures privacy + rewards authentic users

---

## 🔗 On-Chain Logic

- **ADC Token**:
  - Staked by advertisers
  - Distributed based on real-world engagement

- **Smart Contracts**:
  - Handle ADC token staking + campaign execution
  - Automate payouts from verified oracle data

- **ZK-Proofs**:
  - Anonymously verify demographic engagement
  - Preserve privacy without compromising transparency

> _Actions are verifiable, auditable, and privacy-first._

---

## 💡 Why ADMOJO?

✅ **Real-Time Accuracy**  
✅ **DePIN Integration**  
✅ **Transparent Tokenized RWAs**  
✅ **Democratized Access**  
✅ **Performance-Based Payouts**

> Like Airbnb unlocked income for property owners — ADMOJO empowers small ad space owners.

---

## 📅 MVP Milestones

- ✅ **Subtask 1**: ESP32-CAM views + secure oracle integration  
- ✅ **Subtask 2**: Secure NFC tag writing & URL updates  
- ✅ **Subtask 3**: Web dashboard + ADC staking  
- ⏳ **Subtask 4**: ZK-Proof based user verification  
- ✅ **Subtask 5**: Smart contract payout integration

---

## 🛠 Tech Stack

| Layer        | Technologies                                   |
|--------------|------------------------------------------------|
| **Hardware** | ESP32 WROOM / CAM, PN532, Secure Elements      |
| **Software** | Arduino IDE, GoCV, OpenCV                      |
| **Web**      | Next.js, TailwindCSS, TypeScript               |
| **Blockchain** | Solidity, Foundry, ZK-Proofs, Metal API     |
| **User Auth**| World App Mini Apps                            |
| **Data Flow**| Secure Off-Chain Oracles                       |

---

## 👾 Join the Movement

ADMOJO isn’t just ad tech — it’s a movement to **democratize**, **verify**, and **empower** the real-world advertising ecosystem.

Whether you’re a hardware hacker, blockchain dev, or UI/UX designer — **ADMOJO welcomes all builders.**

> **ADMOJO Protocol** — _where ads aren’t just seen, they’re proven and trusted._
