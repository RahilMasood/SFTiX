# Shenanigang-HZ25AMC-W3BC01
----------------------------------
-> PDF: [SFTiX.pdf](https://github.com/user-attachments/files/18956411/SFTix.1.pdf)
-> Deployed: [SFTix](https://shenanigang-hz-25-amc-w3-bc-01.vercel.app/)

## Problem Statement
----------------------------------
- **REGULATING TICKET SALES**
Regulating Ticket sales and insider reselling drives up prices unfairly, lack of a centralized platform leads to unfair confusion
- **MULTIPLE TICKET SCAM**
One ticket is sold to multiple buyers, fake tickets flood the market, causing losses.
- **REFUND MODULATION**
No refunds for black-market buyers when concerts are canceled,organizers and fans suffer financial losses.
---------------------------
## Solution
Our project tackles ticket reselling issues using Web3 and SFTs, ensuring transparency, security, and fair profits.

- SFT Based Tickets - Each ticket is converted into an SFT, preventing duplication and ensuring authenticity.
- Decentralized Resale Market – Users can trade tickets transparently until the highest bid is reached.
- Ownership Verification – Blockchain technology ensures only one person holds a valid ticket at any time.
- Profit Sharing – Event organizers receive a percentage of resale profits, making the system fair and profitable for them.
- Automated Refunds – Smart contracts ensure buyers get refunds if the event is canceled, eliminating black-market risks.
- This system eliminates scams, multiple sales of the same ticket, and refund fraud, creating a trustworthy and efficient ticket resale marketplace.
  
## Demo
----------------------------------
![image](https://github.com/user-attachments/assets/d8d757d5-2c2f-4a02-9323-84e9873f6f8a)

![image](https://github.com/user-attachments/assets/5eac393c-1622-424e-b72a-3f0e3e431443)


## TechStack
-----------------------------------
- Frontend:
1) React.Js
2) Tailwind CSS

- Backend:
1) Solidity (for Smart Contracts)
2) Hard Hat
3) Arbitrum
4) Python (AI chatbot)

Deployment:
1) Frontend: Vercel
2) Backend: Onrender
 
## Project Structure & Setup
```
├── contracts/: Smart contracts (Solidity).
│   ├── Lock.sol: Example/utility contract.
│   └── TicketingSFT.sol: Core Ticketing SFT contract.
├── src/: Frontend application source code (React/TS).
│   ├── components/: Reusable UI components.
│   │   ├── Navbar.tsx: Navigation bar.
│   │   └── ThemeToggle.tsx: Theme toggle component.
│   ├── contracts/: Frontend contract artifacts.
│   │   └── TicketingSFT.json: Contract ABI.
│   ├── hooks/: Custom React Hooks.
│   │   ├── useContract.tsx: Contract interaction hook.
│   │   ├── useEvents.tsx: Blockchain events hook.
│   │   ├── useTheme.tsx: Theme management hook.
│   │   └── useWallet.tsx: Wallet connection hook.
│   ├── pages/: Application pages/views.
│   │   ├── CreateEvent.tsx: Create event page.
│   │   ├── EventDetails.tsx: Event details page.
│   │   ├── Home.tsx: Home/dashboard page.
│   │   ├── Landing.tsx: Initial landing page.
│   │   ├── MyHostedEvents.tsx: Hosted events page.
│   │   └── MyTickets.tsx: My tickets page.
│   ├── services/: Utility/logic services.
│   │   ├── analysis.ts: Data analysis service.
│   │   └── contract.ts: Contract service abstraction.
│   ├── App.tsx: Root React component.
│   ├── index.css: Global CSS styles.
│   ├── main.tsx: React application entry.
│   └── vite-env.d.ts: Vite env declarations.
├── .gitignore: Git ignore file.
├── README.md: Project documentation (this file).
├── eslint.config.js: ESLint configuration.
├── index.html: Main HTML file.
├── package-lock.json: Dependency lock file.
├── package.json: Project metadata/dependencies.
├── postcss.config.js: PostCSS configuration.
├── tailwind.config.js: Tailwind CSS config.
├── tsconfig.app.json: TS app config.
├── tsconfig.json: TS project config.
├── tsconfig.node.json: TS Node.js config.
└── vite.config.ts: Vite configuration.
```
Setup Instructions:

1.  **Install Node.js and npm:** Ensure you have Node.js and npm (Node Package Manager) installed on your system. You can download them from [https://nodejs.org/](https://nodejs.org/).

2.  **Clone the repository:**
    ```bash
    git clone https://github.com/HackZion/Shenanigang-HZ25AMC-W3BC01
    cd Shenanigang-HZ25AMC-W3BC01


3.  **Install Dependencies:**
    ```bash
    npm install
    ```
    
4.  **Start the Development Server:**
    ```bash
    npm run dev
    ```

## Team
------------------------------------
1) Tejasvi: Web3 backend -> Writing smart contracts
2) Rahil: AI analyzer and assistant bot, web3 integration with solidity
3) Rajarshi: Frontend designer and Developer
