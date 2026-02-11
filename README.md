# AURUM
> **Autonomous, Intelligent Yield Allocation**
> *Powered by Chainlink (CRE, CCIP, Functions, Automation)*

AURUM is an AI-driven, cross-chain yield allocation protocol. It autonomously optimizes stablecoin yield using Chainlink infrastructure to ensure every capital move is risk-adjusted and trust-minimized.

---

## 🛠 Tech Stack
- **Smart Contracts:** Solidity / Cairo (Modular Vaults)
- **Infrastructure:** Chainlink (CRE, CCIP, Functions, Automation, VRF, Data Feeds)
- **AI:** Python (Yield Forecasting & Risk Scoring)
- **Frontend:** React / Next.js

---

## Contribution Rules & Workflow
To maintain code integrity and avoid breaking the protocol, all contributors **must** follow this workflow:

### 1. The Golden Rule
**Never push directly to `main`.** The `main` branch is protected. All changes must arrive via a **Pull Request (PR)**.

### 2. Branching Strategy
Create a feature branch for every task.
* **Naming convention:** `feat/feature-name`, `fix/bug-name`, or `docs/update-name`.
* **Example:** `git checkout -b feat/cre-logic`

### 3. Submission Process
1. **Push your branch:** `git push origin feat/your-feature`
2. **Open a PR:** Go to GitHub and click "New Pull Request".
3. **Review:** Tag at least one teammate to review.
4. **Merge:** Once approved and tests pass, merge into `main`.

---

## Repository Structure
```text
├── ai-engine/      # Python models & Yield prediction scripts
├── contracts/      # Solidity/Cairo smart contracts (Vaults, CRE)
├── frontend/       # Next.js Dashboard & Wallet integration
├── scripts/        # Chainlink Functions & Deployment scripts
└── docs/           # PRD, Architecture diagrams & Design assets
