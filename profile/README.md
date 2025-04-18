![WhatsApp Image 2025-04-06 at 06 03 24 (1)](https://github.com/user-attachments/assets/20d4e5b8-748a-4765-b301-accabaea63fe)

![WhatsApp Image 2025-04-06 at 05 53 26](https://github.com/user-attachments/assets/1e6948d4-4d05-4bd4-8f4f-57b16ca4387e)

https://github.com/user-attachments/assets/e347fe3f-adbd-4892-976f-4bcf7bedf830


🌐 ADMOJO Protocol
Smarter Ads. Verified Views. Real Engagement.
Welcome to ADMOJO Protocol — a decentralized bridge between Advertising Companies (ACs) and Real World Ad Space Owners (ASPs) powered by Decentralized Physical Infrastructure Networks (DePIN), on-chain incentives, and cryptographically verified real-time engagement metrics.
Transforming physical ads into secure, verifiable Real World Assets (RWAs), ADMOJO Protocol democratizes advertising, ensuring transparency, fairness, and trust for all stakeholders. Say goodbye to opaque ad spend and unverifiable impressions.

🚀 Modules Breakdown
1. 📸 admojo_web_server — Proof of Views Engine
Goal: Quantify genuine human engagement with physical ads.

ESP32-CAM streams MJPEG video feeds over Wi-Fi
GoCV + OpenCV (SSD + ResNet DNN) ensures accurate face detection
Aggregates viewer counts every 5 minutes
Sends cryptographically secure metrics to an off-chain oracle for on-chain integration

Highlights:

Dynamic IP support for seamless connectivity
IoU filtering eliminates double counting
Live bounding-box debug feed for real-time monitoring


🔍 Ads aren’t just visible—they’re verifiable.


2. 📲 admojo_nfc_module — Proof of Taps IoT Writer
Goal: Capture active user engagement through NFC interactions.

Powered by ESP32 WROOM with PN532 NFC module (SPI)
Ultra-low power with deep sleep cycles
Dynamically fetches campaign URLs with cryptographic security
Writes NDEF-formatted MiFare Classic NFC tags
Powers down PN532 to prevent interference

Security First:

Cryptographically enforced write control
Tag locking with unique sector keys
ADMOJO-signed firmware ensures authenticity


✨ Passive views show interest; taps prove intent.


3. 🌍 web-app (Campaign Hub) — Token Staking & Ad Management
Features:

Advertisers stake ADC tokens to launch campaigns
Browse ASP locations with real-time traffic analytics, Proof-of-View metrics, and Tap ratios
Schedule ad slots via an intuitive map interface
Smart contracts auto-distribute tokens based on verified engagement

Web Stack:

Next.js + TailwindCSS for a responsive UI
Map integration for seamless ASP selection
Metal API for efficient token management


4. 🎯 web-app (User Engagement) — Rewards & Verification Portal
Flow:

Users tap NFC-enabled ads, redirecting to a campaign mini-site
Engage with rewards, giveaways, or tokens
Verify interactions using Sybil-resistant mechanisms (e.g., World App Mini Apps)
Log verified taps securely with ZK-proofs for anonymous demographic data

Why it matters:

Eliminates fraudulent interactions
Rewards authentic engagement while preserving user privacy


🔗 On-Chain Logic

ADC Token: Staked by advertisers, distributed based on verified engagement
Smart Contracts:
Manage ADC token staking and campaign execution
Automate token redistribution using verified metrics
Read off-chain oracles for real-time Proof of Views and Taps
Ensure transparent, auditable fund allocation


ZK-Proofs: Enable privacy-preserving verification of viewer demographics


Actions are verifiable, auditable, and privacy-first.


💡 Why ADMOJO?

🧠 Real-Time Accuracy: Cryptographically secure engagement metrics
📡 DePIN Integration: Trusted execution environments via secure elements
🔐 Blockchain Transparency: Tokenized RWAs and transparent payouts
🌐 Democratized Access: Empowering small ad space owners to compete
💸 Performance-Based: Pay only for proven engagement

ADMOJO Protocol fosters fairness in advertising, just as Airbnb empowered small property owners. By tokenizing physical ad spaces and verifying engagement with DePIN, we create a level playing field for all.

📅 MVP Milestones

✅ Subtask 1: ESP32-CAM views & secure oracle integration
✅ Subtask 2: Secure NFC tag writing & dynamic URL updates
✅ Subtask 3: Complete web dashboard & ADC staking
⏳ Subtask 4: User rewards verification with ZK-proofs
✅ Subtask 5: Smart contract integration for seamless payouts


🛠 Tech Stack

Hardware: ESP32 WROOM/CAM, PN532, Secure Elements (SE)
Software: Arduino IDE, GoCV, OpenCV
Web: Next.js, TailwindCSS, TypeScript
Blockchain & Verification: Solidity, Foundry, Metal API, ZK-Proofs, World App
Data Integration: Secure off-chain oracles


👾 Join the ADMOJO Movement
ADMOJO Protocol isn’t just ad tech—it’s a movement to democratize, verify, and empower the advertising ecosystem. Whether you’re building IoT devices, writing smart contracts, or designing user experiences, ADMOJO welcomes all innovators.

ADMOJO Protocol — where ads aren’t just seen, they’re proven and trusted.

