# Freelance MVP 

A Next.js-based decentralized freelance marketplace where clients and freelancers can post jobs, collaborate, and handle payments securely via blockchain escrow. Built with modern web technologies and AI-powered features.



---

## Features 

- **Job Posting & Bidding**:
  - Clients can post jobs with budgets and descriptions.
  - Freelancers can submit proposals and negotiate terms.

- **Blockchain Escrow**:
  - Secure payments via Ethereum smart contracts.
  - Funds held in escrow until job completion.

- **AI-Powered Matching**:
  - Recommends jobs to freelancers based on skills.
  - Improves proposals using OpenAI's GPT.

- **Decentralized Reputation**:
  - Freelancer ratings stored on-chain.
  - Transparent and tamper-proof reviews.

- **Real-Time Collaboration**:
  - Built-in chat and file sharing.
  - Milestone tracking for projects.

---

## Tech Stack 

| Category       | Technologies                                                                 |
|----------------|-----------------------------------------------------------------------------|
| Frontend       | Next.js, Tailwind CSS, Framer Motion                                        |
| Backend        | Node.js, FastAPI, GraphQL, REST                                            |
| Blockchain     | Ethereum, Solidity, Hardhat, ethers.js                                     |
| AI             | OpenAI API, TensorFlow (for advanced matching)                             |
| Database       | PostgreSQL, Redis (caching)                                                |
| Authentication | NextAuth.js, OAuth 2.0, JWT                                               |
| Deployment     | Vercel, AWS EKS, GitHub Actions (CI/CD)                                   |

---

## Getting Started 

### Prerequisites
- Node.js (v18 or higher)
- npm (v9 or higher)
- MetaMask (for blockchain interactions)
- OpenAI API key (for AI features)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/freelance-mvp.git
   cd freelance-mvp

   npm install

   Set up environment variables:
Create a .env.local file:
DATABASE_URL="postgresql://user:password@localhost:5432/freelance"
OPENAI_API_KEY="your_openai_key"
NEXTAUTH_SECRET="your_secret_key"
NEXTAUTH_URL="http://localhost:3000"

Run the development server:
npm run dev

Open your browser:
http://localhost:3000
