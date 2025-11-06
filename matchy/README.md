# ARG25 Project Submission

Welcome to Invisible Garden- ARG25.

##  Project Title
Matchy

## Team
- Team Name: Matchers
- GitHub Handles: mahdieh-amiri1, hossi1363, 22lolo
- Devfolio Handles: mahdieh, hoka, Smilehi



## Project Description

**Matchy** is a location-based AI networking platform that helps people discover and connect with others nearby who share similar **interests, skills, or goals**.  
It’s designed for **events, co-working spaces, universities, or any social environment** where participants want to find more relevant people to meet — while maintaining strong privacy guarantees.

### How It Works

1. **Login & Verification**  
   Users log in with their wallet. Optionally, they can link an **onchain passport** (e.g., [app.passport.xyz](https://app.passport.xyz)) to verify their humanity score (e.g., >20) and ensure they are real individuals — similar to Gitcoin verification standards.

2. **Profile Enrichment**  
   The app pulls profile data (bio, skills, interests) from connected social accounts such as **X (Twitter), Farcaster, or Lens** to automatically build a lightweight user profile.

3. **Location Proof (Privacy-Preserving)**  
   Users share their location access — but the app never learns their exact coordinates.  
   Instead, we are exploring **Zero-Knowledge Proof (ZKP)**-based mechanisms that allow users to **prove they are in a claimed location** without revealing it directly.  
   (We are currently evaluating suitable tools and frameworks for this.)

4. **AI Matchmaking**  
   A privacy-aware **AI matchmaker** processes interest embeddings and location proofs to find relevant matches **within a 1 km radius**.

5. **Match Feed**  
   Matches are displayed as interactive cards in the app feed.  
   Each card shows basic profile data and shared interests.

6. **Match Pot**  
   Users can **“Add to Match Pot”** (shortlist) or ignore suggestions.  
   When both users shortlist each other, they can open a chat and coordinate a meeting.

---

### Future Roadmap
- Integrate robust **Zero-Knowledge proof tooling** for verifiable location claims.  
- Add **gamified badges** and **onchain proof-of-meet interactions** to encourage participation.  
- Explore optional integrations with **event platforms (e.g., Luma)** or **social graphs (e.g., Farcaster)** for discovery and identity context.  
- Deliver a **fun, secure, and privacy-first networking experience** powered by verifiable AI and decentralized identity.

---

## Objectives

1. Build a functional MVP for location-based AI matchmaking.  
2. Implement wallet connection and optional onchain passport verification.  
3. Integrate AI-based matching suggestions for users within a 1 km proximity.  
4. Experiment with **ZK-based location proof** mechanisms for privacy-preserving geolocation.  
5. Create an interactive “match feed” and “match pot” feature for connection management.  
6. Prepare documentation and a working demo for the final **ARG25 showcase**.


## Weekly Progress

### Week 1 (ends Oct 31)
**Goals:**
- Define the project concept and validate the idea scope.  
- Research similar tools (e.g., Cherry Matchmaker, Luma integrations, and event networking apps).  
- Choose project name, repo structure, and tech stack.  
- Set up development environment for frontend and backend.  
- Design initial user flow (connect wallet → fill interests → get matches).  

**Progress Summary:**  
- Finalized the main idea and simplified scope to make it achievable within hackathon time.  
- Researched comparable products such as Cherry Matchmaker, Brella, and Luma integrations to identify differentiators.  
- Decided on the core direction: **location-based AI matching** for events, with optional wallet connection for identity.  
- Defined future roadmap for privacy-preserving (ZK-based) features but deferred them for MVP.  
- Created initial repo structure and started frontend environment setup with Next.js + Tailwind.  
- Discussed AI matchmaking approach (embedding similarity + local suggestions).  
- Decided to keep architecture modular to allow optional Arbitrum Stylus / ZK integrations later.  


### Week 2 (ends Nov 7)
**Goals:**  
- Build core profile creation and editing flow.
- Implement basic AI matching engine using embeddings or rule-based similarity.  
- Create match proposal and notification system (mock or simple backend).  
- Set up basic UI for matched profiles and accept/reject interactions.  
- Conduct first internal test with mock users.  

**Progress Summary:**  
_(to be updated at the end of Week 2)_  

### Week 3 (ends Nov 14)
**Goals:**  
- Polish UX/UI and deploy public demo.  
- Add chat feature for mutually accepted matches.  
- Prepare optional Arbitrum Stylus proof-of-concept for on-chain badges.  
- Record demo video and finalize documentation.  

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