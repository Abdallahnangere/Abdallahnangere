# Hi, I'm Abdullahi Adam Usman (`Abdallahnangere`)

Full-stack mobile & backend engineer (and 300-Level International Studies student at Ahmadu Bello University, Zaria) building production fintech, e-commerce, and civic software—**leveraging agentic development and AI capabilities to deliver efficient, high-craft results**.

> *Most of my commercial products live in private repositories—this page showcases the live apps, verified engineering benchmarks, and open-source data/mobile projects you can inspect and run today.*

[![Website](https://img.shields.io/badge/Website-saukimart.com-2563EB?style=flat-square&logo=googlechrome&logoColor=white)](https://saukimart.com/)
[![Email](https://img.shields.io/badge/Email-abdallah%40saukimart.com-0D9488?style=flat-square&logo=gmail&logoColor=white)](mailto:abdallah@saukimart.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B2348164135836-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/2348164135836)
[![Call](https://img.shields.io/badge/Tel-%2B2348164135836-111827?style=flat-square&logo=phonepe&logoColor=white)](tel:+2348164135836)

> **Open for Collaborations, Contract Works & Hiring:** Available for Flutter mobile engineering, Next.js/FastAPI backend systems, and AI-assisted product delivery. Reach out via [Email](mailto:abdallah@saukimart.com), [WhatsApp (`+2348164135836`)](https://wa.me/2348164135836), or call `+2348164135836`.

---

## Tech Stack & Capabilities

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(Neon)-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite_FTS5-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Cloud_Tasks-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Codemagic](https://img.shields.io/badge/Codemagic-F45E3F?style=for-the-badge&logo=codemagic&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic_AI_Workflows-111827?style=for-the-badge&logo=openai&logoColor=white)

---

## Featured Shipped Products & Open-Source Work

### 1. Sauki Go — Smart Wallet, Bills & AI Express VTU *(Live on Stores · Private Repo)*

[![Google Play](https://img.shields.io/badge/Google_Play-Live-34A853?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.saukimart.go)
[![Apple App Store](https://img.shields.io/badge/App_Store-Live-0D96F6?logo=apple&logoColor=white)](https://apps.apple.com/us/app/sauki-go-data-and-commission/id6815456102)
[![Web](https://img.shields.io/badge/Web-saukimart.com-1D4ED8)](https://saukimart.com/)

A native Flutter financial & VTU app (`88` Dart files, `142` commits) powered by the `APP-Final` Next.js 14 / Neon PostgreSQL / Firebase / Flutterwave backend (`716` commits).

**Key Engineering Feats:**
- **Cold-Boot & Caching Optimization (`dafd632` → `cce002f`):** Unblocked Firebase pre-`runApp()` gating (`0 ms` launch block), reduced splash wait by **68.2%** (`1,100 ms → 350 ms`), built an L1 RAM + L2 `SharedPreferences` cache (**52.95×** faster transaction cache reads in VM microbenchmarks: `1.67 µs` vs `88.42 µs`), and parallelized 4-endpoint home refreshes (**3.06×** faster simulated critical path: `553 ms → 181 ms`).
- **Low-RAM Android OTP Draft Recovery:** Engineered a 20-minute dual-tier encrypted draft engine (`SharedPreferences` + hardware KeyStore via `FlutterSecureStorage` + Android `alwaysRetainTaskState="true"`) paired with idempotent backend responses so switching to SMS apps never wipes onboarding state.
- **"Send When Online" Telco Resilience:** Built an HMAC-signed `retryToken` flow backed by self-chaining Google Cloud Tasks (3-minute retries, atomic lease for zero idle cost, and automatic 24-hour refund safety) for transient carrier outages.
- **Sauki AI & Checkout Safety:** Pre-Gemini local express-buy intent parser for instant airtime/data orders, UUIDv4 idempotency keys + purchase mutexes, 4-digit PIN + biometric lock, and `39` automated Flutter tests.
- **Web Performance (`saukimart.com` — Yellow Lab Tools `A · 94/100`):** `1.12 MB` total page weight, `38` requests, `576` DOM elements, `237 ms` total JS execution time, `0` JS errors, `0` 404s, `0` oversized images, and `0` HTTP/TLS issues.

<p align="center">
  <img src="./assets/sauki_mart_web.jpg" alt="SaukiMart & Sauki Go Web Platform" width="90%" />
</p>

| Smart Wallet Home | Sauki AI Express Buy | Zero-Fee Transfer | Verified Receipt |
| :---: | :---: | :---: | :---: |
| <img src="./assets/sauki_go_wallet.png" width="190" alt="Smart Wallet Home" /> | <img src="./assets/sauki_go_ai.png" width="190" alt="Sauki AI Express Buy" /> | <img src="./assets/sauki_go_transfer.png" width="190" alt="Zero-Fee Transfer" /> | <img src="./assets/sauki_go_receipt.png" width="190" alt="Verified Receipt" /> |

---

### 2. My NELFund — Bilingual Student Loan Guide *(Open Source · Live on Stores)*

[![Repo](https://img.shields.io/badge/GitHub-mynelfund--app-181717?logo=github)](https://github.com/Abdallahnangere/mynelfund-app)
[![Google Play](https://img.shields.io/badge/Google_Play-Live-34A853?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.mynelfund.app)
[![Apple App Store](https://img.shields.io/badge/App_Store-Live-0D96F6?logo=apple&logoColor=white)](https://apps.apple.com/ng/app/my-nelfund/id6809634284)

An independent, bilingual (**English & Hausa**) Cupertino Flutter utility helping Nigerian tertiary students navigate the **Students Loans (Access to Higher Education) Act, 2024**.

**Verified Production Adoption (Firebase Analytics, Aug 20 – Nov 16, 2026):**
- **5,636** total installs (`first_open`) across **41** countries (`5,420` active users in Nigeria)
- **3,402** peak 30-day active users (MAU) · **1,191** peak 7-day active users (WAU)
- **10,492** loan repayment calculations · **5,643** eligibility audits completed
- **100%** crash-free users on both iOS (`2.2.7`) and Android (`2.2.6`), backed by `15` automated test suites (`68` passing tests)

| Home & Overview | Eligibility Checker | Repayment Calculator | Bilingual & About |
| :---: | :---: | :---: | :---: |
| <img src="./assets/nelfund_home.jpg" width="190" alt="My NELFund Home" /> | <img src="./assets/nelfund_eligibility.jpg" width="190" alt="Eligibility Checker" /> | <img src="./assets/nelfund_calculator.jpg" width="190" alt="Repayment Calculator" /> | <img src="./assets/nelfund_about.jpg" width="190" alt="About & Bilingual Toggle" /> |

---

### 3. Sauki Mart 2.0 — Multi-Vendor Commerce App *(Launching Soon · Private Repo)*

[![Web](https://img.shields.io/badge/Platform-saukimart.com-2563EB)](https://saukimart.com/)

Native Flutter multi-vendor marketplace (`79` Dart files, `57` commits) sharing the `APP-Final` commerce & wallet backend:
- Unauthenticated public discovery with staggered masonry product feeds, flash deals, and interactive variant selectors.
- Multi-store grouped cart, Nigerian 36-state + FCT address manager, Flutterwave dynamic virtual account / OPay / Sauki Wallet PIN checkout, and PDF/PNG receipts.

---

### 4. Anjal Islamic Library — Structured Datasets & Headless JSON API *(Open Source)*

[![Repo](https://img.shields.io/badge/GitHub-Anjal--Islamic--Library-181717?logo=github)](https://github.com/Abdallahnangere/Anjal-Islamic-Library)
[![Live API](https://img.shields.io/badge/API-islamiclibrary.anjalventures.com-009688)](https://islamiclibrary.anjalventures.com/docs)

A headless, schema-validated dataset pipeline and FastAPI JSON data service (`Python`, `SQLite FTS5`, `JSON Schema Draft 2020-12`, `Vercel`):
- **Datasets:** `6,236` Quran ayahs (`114` surahs), `36,512` Hadith entries (`10` collections), `55,991` Umm al-Qura Hijri date mappings (`1343–1500 AH`), and `836` prayer time entries across all Nigerian cities/LGAs & global hubs.
- **Pipeline:** UTF-8/NFC normalization (`scripts/build_db.py`), automated mojibake scanning (`verify_text_encoding.py`), SHA-256 `manifest.json` verification & JSON/JSONL exporter (`scripts/export_json.py`), OpenAPI `/docs` + `/redoc`, and automated `unittest`/CI verification.

---

## Let's Work Together

Open to **technical collaborations, freelance/contract builds, and engineering roles** (Flutter, Next.js/TypeScript, FastAPI/Python, and AI-accelerated product delivery):

- **Email:** [abdallah@saukimart.com](mailto:abdallah@saukimart.com)
- **WhatsApp:** [+234 816 413 5836](https://wa.me/2348164135836)
- **Phone / Call:** [+234 816 413 5836](tel:+2348164135836)

