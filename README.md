# Leela Prasad Maturu

**Software Engineer · Backend Systems · Occasionally Breaking Things in Production**
IIIT Sri City — B.Tech (CSE) · GPA 9.07 · Graduating May 2026

---

## About

I build backend systems that don't fall over (most of the time). Did 3 production internships: Swiggy (GenAI stuff), Caterpillar (enterprise Java hell), and EasyCapital (fintech backend).

I care about systems that scale, code that doesn't make people cry in production, and understanding how companies actually work beyond the engineering bubble — because good code in a bad business model still fails.

---

## Recent Work

**Swiggy** (Oct 2025 - Present)
Built a GitOps-driven API key management platform (1500+ keys generated, 30+ AI models), designed a distributed RAG pipeline (p99 under 150ms), and optimized build times from 50+ min to 3 min (77% cost savings). Also learned that "production-ready" means different things to different people.

**Caterpillar** (May 2025 - Jul 2025)
Migrated enterprise backend from JDK 11/15 to JDK 21 across 10,000+ files using OpenRewrite. Debugged a production bug affecting file transfers — turned 100% failures into 0% with parallelized multi-threading. Enterprise code is... an experience.

**EasyCapital** (Jul 2024 - Sep 2024)
Optimized fintech backend services handling 10,000+ requests/day, reduced API latency by 45%. Built CI/CD pipelines that actually work. First time dealing with payment systems — learned that "eventually consistent" is not acceptable when money is involved.

---

## Tech Stack

**Languages:** Java, Python, JavaScript, SQL, C
**Backend:** Node.js, Spring Boot, Express, REST APIs
**Databases:** MySQL, MongoDB, Redis, Vector DBs (Qdrant, FAISS)
**Infra:** Docker, Kubernetes, AWS, Linux, CI/CD (GitHub Actions, Maven)
**AI/ML:** LLM APIs, RAG pipelines, Model orchestration, ONNX Runtime

**DSA:** 280+ problems solved (LeetCode/GfG) — enough to pass most OAs, not enough to solve P=NP

---

## Projects I Actually Finished

### TradeWise-AI — LLM Trading Journal
**Stack:** Node.js, Google Gemini, Cohere, FinBERT, Jest
LLM-powered trading assistant with sentiment analysis and post-trade insights. 85+ automated tests (80%+ coverage) because I don't trust LLMs to not hallucinate in production.

### Hotel Booking Platform
**Stack:** Node.js, React, MongoDB, MySQL, Redis, Docker
Led backend for 5-member team. RESTful microservices with DDD, dual database setup (relational + NoSQL), CI/CD automation. Reduced delivery time by 60%+. Learned that "it works on my machine" is not a deployment strategy.

---

## What I Think About Companies & Business

Been part of Entrepreneurial Cell at IIITS (organized 3+ startup events, 100+ participants). Led 2 production-grade campus apps with a 5-member team. Here's what working at different companies taught me:

**Large corporations** (Swiggy, Caterpillar) move slow but have resources. Processes everywhere, decisions take forever, but you learn how systems scale when you have thousands of engineers and millions of users. Politics exist. Documentation is a myth. But they don't die easily — they have cash, users, and brand. That's worth something.

**Startups** (EasyCapital) move fast and break things — sometimes on purpose, sometimes by accident. You wear multiple hats. You ship features before they're "perfect" because perfect is the enemy of shipped. Less bureaucracy, more chaos. But they can pivot, ship fast, and die fast too.

**What actually matters:**
- **Execution > Ideas.** Most companies fail not because their tech is bad, but because they can't sell, can't hire, or run out of money. Engineering is 30% of the problem, the rest is business, sales, and not screwing up operations.
- **Distribution > Product.** The best product doesn't always win. The product with better sales, marketing, and network effects wins. Saw this at Swiggy — good enough tech + great distribution beats perfect tech + no users.
- **Unit economics matter.** Revenue looks nice until you realize CAC > LTV and you're burning money. Fintech taught me that every API call costs money, every user costs money, and "we'll figure out monetization later" is cope.
- **People > Everything.** Companies are just groups of people trying to coordinate. The ones that hire well, retain well, and don't have toxic culture ship faster and die slower. Seen teams with average engineers ship 10x more than teams with "rockstars" who can't work together.

**What I'm curious about:**
- Why do some engineering orgs ship 10x faster than others with the same headcount? Is it process, people, tools, or just less meetings?
- How do you build systems that don't collapse when you 10x overnight? (Engineering side is caching + queues. Business side is hiring, onboarding, support — what breaks first?)
- How do you make a service provide more value so customers actually use it more? Not dark patterns — real value. Smart recommendations? Better UX? Faster responses? What engineering decisions actually move user behavior?
- How fast do AI models learn and forget in production? If you fine-tune on new data, what gets overwritten? How do you scale that without breaking what already works?
- **Sales > Everything.** No company survives without sales. How do top companies actually do it? Cold outreach? Inbound? Relationships? What converts prospects into paying customers?
- Why do companies with worse tech dominate markets? (Enterprise software, I'm looking at you.) Is it distribution, sales, or just being first?

**Lessons from entrepreneurship stuff:**
- Talking to users > Building in a cave. Most people build things no one wants because they never asked.
- Shipping fast > Shipping perfect. You learn more from 10 mediocre launches than 1 perfect launch that takes a year.
- Revenue > Funding. Companies that make money are less likely to die. Obvious but somehow everyone forgets this.
- Bias for action > Analysis paralysis. Some people really like meetings. I learned that perfect is the enemy of shipped.

---

## Side Interests

**Trading:** Curious about markets, risk, and decision-making under uncertainty. Built a trading journal because manually logging trades is painful. Lost money, learned lessons, built software to avoid losing the same way twice.

**System Design:** How do you design a system that doesn't die when traffic spikes 100x? How do you make databases fast without throwing money at bigger servers? How do you debug distributed systems when everything is eventually consistent and nothing makes sense?

**Business/Sales:** Engineering doesn't matter if no one buys your product. How do companies find customers? How do you price SaaS? Why do some products with worse tech win in the market? Still figuring this out.

**Engineering × Business:** Most engineers think in code. Most business people think in revenue. I think the real leverage is in the overlap.

You can build the most elegant, scalable, performant system — but if it doesn't move a metric that matters to the business, you just burned time and money. At Swiggy, I saw teams spend weeks optimizing latency from 50ms to 20ms when the actual bottleneck was user onboarding flow. Engineering problem? Solved. Business problem? Still there.

On the flip side, business wants to "increase engagement by 20%" but has no idea if that's technically feasible, what it costs to build, or if the infrastructure can even handle it. That's where understanding both sides matters.

**Examples:**
- **Engineering POV on business:** "You want real-time analytics? That's 10x the infra cost. Can we batch every 5 minutes and still get the same outcome?" Understanding the business goal helps you build the right thing, not just the requested thing.
- **Business POV on engineering:** "We optimized our backend to handle 100k RPS. Cool. But we only get 1k users/day and our conversion rate is 0.5%. Maybe we should fix the funnel before scaling the servers." Metrics matter. Revenue matters. Usage matters.

I look at engineering decisions and ask: does this move revenue, retention, or reduce churn? I look at business goals and ask: can we automate this, scale this, or build this without blowing up the budget?

Most people pick one side. I think the interesting problems are where both sides collide — where the right engineering decision unlocks business growth, and the right business constraint forces better engineering.

---

## What I'm Looking For

**New grad SDE roles** where I can:
- Build systems that scale (and debug them when they don't)
- Learn from people who've solved harder problems than me
- Ship code that matters to real users
- Understand how the business side works (not just the tech side)
- See how engineering decisions connect to revenue, growth, and actual outcomes

---

## Contact

**Email:** leelaprasad.m22@iiits.in
**LinkedIn:** [linkedin.com/in/leelaprasadm](https://linkedin.com/in/leelaprasadm)
**GitHub:** You're already here

**Response time:** Fast if it's interesting, slow if it's a recruiter cold email asking if I know Java (yes, I do, it's literally on my resume).

---

**Last Updated:** May 2026
