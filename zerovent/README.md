# ARG25 Project Submission Template

Welcome to Invisible Garden- ARG25.

Each participant or team will maintain this README throughout the program.  
You’ll update your progress weekly **in the same PR**, so mentors and reviewers can track your journey end-to-end.


##  Project Title
Zerovent

## Team
- Team Name: HereZero
- GitHub Handles: mahdieh-amiri1, hossi1363, 22lolo
- Devfolio Handles: mahdieh, hoka, Smilehi

## Project Description
**Zerovent** is a privacy-preserving event and networking platform built for hackathons and conferences.  
It enables participants to register, check in, and connect with others **without exposing personal data**, using **Zero-Knowledge (ZK) proofs** to verify credentials and actions.  
An **AI matchmaker** suggests relevant people to meet based on shared interests or skills, while maintaining user privacy through local or encrypted data processing.  
We’re also integrating **decentralized notifications** and **gamified badges/POAPs** to reward engagement — creating a fun, secure, and privacy-first experience for event attendees.  

Zerovent aligns with Invisible Garden’s focus on **ZK, AI, and Web3 UX**, showing how decentralized identity and verifiable computation can power real-world social interactions.  


## Tech Stack
- **Frontend:** React, Next.js, TailwindCSS  
- **Smart Contracts:** Solidity + Hardhat (Event Registry, Verifier, POAPs)  
- **Zero-Knowledge Tools:** Semaphore (membership proofs), circom (optional circuits), zkPass / zkEmail (concept references)  
- **Notifications & Messaging:** Push Protocol SDK  
- **Blockchain Infrastructure:** AltLayer Rollup / testnet for deployment  
- **AI Matchmaking:** Python microservice or in-browser embeddings (TF.js / ONNX)  
- **Verifiable Compute (optional):** Brevis or ZKM for future AI proof-of-correctness  
- **Wallet Integration:** wagmi + ethers.js + MetaMask / WalletConnect  


## Objectives
By the end of ARG25, we aim to:  
1. Deliver a **functional MVP** that demonstrates event registration, ZK-based check-in, and AI-powered matchmaking.  
2. Showcase integration with at least one **Invisible Garden sponsor**.  
3. Build a privacy-centric UX that lowers the barrier to using ZK tools in real social scenarios.  
4. Deploy smart contracts on a **scalable testnet (AltLayer)** and enable on-chain POAP issuance.  
5. Prepare a public demo and presentation showing how Zerovent can redefine networking in Web3 events.  


## Weekly Progress

### Week 1 (ends Oct 31)
**Goals:**
- Finalize project scope and technical architecture (ZK flow + AI components).  
- Set up repo structure (frontend / backend / contracts / zk circuits).  
- Implement basic wallet connection and profile creation UI.  
- Begin integration with Push Protocol SDK for notifications.  
- Define ZK proof approach (Semaphore-based membership proof) and deploy test verifier contract.  
- Research sponsors and confirm tech we’ll leverage (AltLayer, Brevis, Push).  

**Progress Summary:**  
- Defined and validated core concept: privacy-first event app using ZK + AI.  
- Created full architecture diagram and sprint plan for two-week build.  
- Bootstrapped Next.js + Tailwind frontend and initialized Hardhat environment.  
- Integrated wallet login (wagmi + MetaMask).  
- Tested Push Protocol notifications on test wallet.  
- Completed first version of event creation and profile components.  
- Began experimenting with Semaphore circuits for private check-in proofs.  


### Week 2 (ends Nov 7)
**Goals:**  
- Implement ZK check-in flow (proof generation and verification).  
- Add event dashboard and attendee management.  
- Build AI matchmaker prototype and connect to mock data.  
- Integrate Push notifications for match invitations and check-in confirmation.  
- Deploy first version of contracts on AltLayer testnet.  

**Progress Summary:**  
_(to be updated at the end of Week 2)_  


### 🗓️ Week 3 (ends Nov 14)
**Goals:**  
- Finalize UI/UX polish and gamified badges (POAPs).  
- Record demo video and prepare final pitch slides.  
- Conduct full end-to-end test with ZK check-in + AI matching.  
- Submit final project to ARG25.  

**Progress Summary:**  
_(to be updated at the end of Week 3)_  


## Final Wrap-Up
_After Week 3, summarize your final state: deliverables, repo links, and outcomes._

- **Main Repository Link:**  _(to be added)_  
- **Demo / Deployment Link (if any):**  _(to be added)_  
- **Slides / Presentation (if any):**  _(to be added)_  


## 🧾 Learnings
_What did you learn or improve during ARG25?_  
_(to be added after final submission)_  


## Next Steps
_If you plan to continue development beyond ARG25, what’s next?_  
_(to be added after final submission)_  


_This template is part of the [ARG25 Projects Repository](https://github.com/invisible-garden/arg25-projects)._  
_Update this file weekly by committing and pushing to your fork, then raising a PR at the end of each week._