# ARG25 Project Submission

Welcome to Invisible Garden- ARG25.

##  Project Title
Matchy

## Team
- Team Name: Matchers
- GitHub Handles: mahdieh-amiri1, hossi1363, 22lolo, FaezehShakouri
- Devfolio Handles: mahdieh, hoka, Smilehi, thefazi

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
   A privacy-aware **AI matchmaker** processes interest embeddings and location proofs to find relevant matches **within a desired radius**.

5. **Match Feed**  
   Matches are displayed as interactive cards in the app feed.  
   Each card shows basic profile data and shared interests.

6. **Match Pot**  
   Users can **“Add to Match Pot”** (shortlist) or ignore suggestions.  
   When both users shortlist each other, they can open a chat and coordinate a meeting.


## Getting Started

**Option A: To run the project locally:**

```bash
npm install
npm run dev
```
Then open your browser and visit:
[http://localhost:3000](http://localhost:3000)


**Option B: Alternatively, you can try the live demo:**
[https://matchy-two.vercel.app/](https://matchy-two.vercel.app/)


**Option C: For Farcaster preview mode:**

1. Log in to your Farcaster account.
2. Go to **Settings → Advanced Settings → Developer Mode**.
3. Open the **Preview** section and paste the demo URL.




## Tech Stack

- **Next.js 16**
- **TypeScript**
- **Tailwind CSS**
- **Farcaster Mini App SDK**


## Objectives

1. Build a functional MVP for location-based AI matchmaking.  
2. Implement wallet connection and optional onchain passport verification.  
3. Integrate AI-based matching suggestions for users within a desired radius.  
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
- Built the first version of **Matchy as a Farcaster miniapp**, allowing wallet login and profile creation.  
- Integrated **profile fetching** and mock data for interests and skills.  
- Implemented **AI-based rule-matching** prototype with interest overlap logic.  
- Created responsive UI using **Tailwind CSS + React** for the feed and match cards.  
- Designed and tested “Add to Match Pot” interactions and local state management.  
- Began exploring ZK-based approaches for privacy-preserving location proof (reviewing existing toolkits and research).  


### Week 3 (ends Nov 14)
**Goals:**  
- Polish UX/UI and deploy public demo.  
- Add chat feature for mutually accepted matches.  
- Prepare optional Arbitrum Stylus proof-of-concept for on-chain badges.  
- Record demo video and finalize documentation.  

**Progress Summary:**  
- Completed the **final version of the Farcaster miniapp** with stable wallet connection and profile integration.  
- Enhanced **UX/UI** with improved layouts, animations, and match card transitions using Tailwind CSS.  
- Added **chat functionality** for mutually accepted matches, enabling basic text messaging inside the app.  
- Created **on-chain badge system prototype** using Solidity (Arbitrum Stylus optional integration).  
- Conducted user testing within the ARG25 community; improved matching logic based on feedback.  
- Deployed MVP publicly on **Vercel**, linked with mock backend.  
- Recorded and submitted demo video and prepared presentation slides for final submission.  


## Final Wrap-Up
- **Main Repository Link:** [https://github.com/mahdieh-amiri1/arg25-Projects/tree/matchers-matchy/matchy](https://github.com/mahdieh-amiri1/arg25-Projects/tree/matchers-matchy/matchy)  
- **Demo / Deployment Link:** [https://matchy-two.vercel.app/](https://matchy-two.vercel.app/)  
- **Slides / Presentation:** [https://miro.com/app/board/uXjVJuS-0Q0=/?share_link_id=354271186401](https://miro.com/app/board/uXjVJuS-0Q0=/?share_link_id=354271186401)  


## Learnings
During ARG25, our team learned to combine **AI, Web3 identity, and privacy-preserving design** in a real-world use case.  
Key takeaways include:  
- Gained hands-on experience building a **Farcaster miniapp** and integrating decentralized social graph data.  
- Improved our understanding of **wallet-based authentication** and **onchain identity standards** like Gitcoin Passport.  
- Explored **Zero-Knowledge Proof (ZKP)** tools for privacy-focused location verification.  
- Strengthened collaboration and rapid prototyping skills using **Next.js**, **Tailwind**, and **Solidity** under tight deadlines.  
- Understood how to iterate from idea → prototype → demo with clear user journeys.  


### Future Roadmap
- Integrate robust **Zero-Knowledge proof tooling** for verifiable location claims.  
- Add **gamified badges** and **onchain proof-of-meet interactions** to encourage participation.  
- Explore optional integrations with **event platforms (e.g., Luma)** or **social graphs (e.g., Farcaster)** for discovery and identity context.  
- Deliver a **fun, secure, and privacy-first networking experience** powered by verifiable AI and decentralized identity.


## Next Steps
We plan to continue developing **Matchy** beyond ARG25:  
- Enhance the **AI matchmaker** with better context embedding and interest similarity models.  
- Implement full **ZK location proof** integration to make matching both private and verifiable.  
- Add **multi-event support**, enabling organizers to activate Matchy during specific events or venues.  
- Introduce **onchain badges and rewards** for verified in-person meetings.  
- Prepare for a **beta release on Farcaster** and explore integration with **Luma** and **Lens Protocol** for broader reach.  



This project is part of the [ARG25 Projects Repository](https://github.com/invisible-garden/arg25-projects).
