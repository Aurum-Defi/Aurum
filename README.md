# 🟡 AURUM
> **Autonomous, Intelligent Yield Allocation** > *Powered by Chainlink (CRE, CCIP, Functions, Automation)*

AURUM is an AI-driven, cross-chain yield allocation protocol. It autonomously optimizes stablecoin yield using Chainlink infrastructure to ensure every capital move is risk-adjusted and trust-minimized.

---

## 🛠 Tech Stack
- **Smart Contracts:** Solidity / Cairo (Modular Vaults)
- **Infrastructure:** Chainlink (CRE, CCIP, Functions, Automation, VRF, Data Feeds)
- **AI:** Python (Yield Forecasting & Risk Scoring)
- **Frontend:** React / Next.js

---

## ⚖️ Contribution Rules (Mandatory)
To maintain code integrity during the hackathon, follow these rules strictly:

### 1. The Golden Rule
**NEVER push directly to `main`.** Even if you have access, don't do it. The `main` branch is for stable, demo-ready code only.

### 2. Working in Folders
To prevent merge conflicts, stay within your assigned directory:
* **AI/Data Lead:** Work in `/ai-engine`
* **Smart Contract Lead:** Work in `/contracts`
* **Frontend Lead:** Work in `/frontend`
* **Integrations/Scripts:** Work in `/scripts`

### 3. Git Workflow
1. `git pull origin main` (Start your session with this)
2. `git checkout -b feat/your-feature-name`
3. Work only in your relevant folder.
4. `git add .` -> `git commit -m "feat: description of work"`
5. `git push origin feat/your-feature-name`
6. Open a **Pull Request (PR)** on GitHub.

---

## 📂 Repository Structure
```text
├── ai-engine/      # Python models & Yield prediction scripts
├── contracts/      # Solidity/Cairo smart contracts (Vaults, CRE)
├── frontend/       # Next.js Dashboard & Wallet integration
├── scripts/        # Chainlink Functions & Deployment scripts
└── docs/           # PRD, Architecture diagrams & Design assets
