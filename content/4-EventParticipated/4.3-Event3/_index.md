---
title: "Event 3"
date: 2026-07-12
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

### [Event 3](4.3-Event3/)
&emsp;**Event Name:** AABW Hackathon Showcase - Top 8 Finals

&emsp;**Date & Time:** 09:00 - 18:00, July 12, 2026

&emsp;**Location:** AWS Vietnam Office, Bitexco Tower, Ho Chi Minh City

&emsp;**Role:** Attendee (Showcase Audience & Peer Reviewer)

### Event Objectives

- Showcase the eight finalist teams of the AABW (Amazon Agentic AI Build Week) Hackathon, presenting their end-to-end agentic-AI products built on AWS Bedrock, AgentCore, and SageMaker[cite: 1, 4].
- Promote cross-pollination of architectural patterns between AI/ML, Computer Vision, Conversational Agents, and Enterprise Search platforms[cite: 2, 3].
- Provide a public-stage platform for the eight teams to validate their MVPs against a panel of AWS Solution Architects, startup founders, and AI mentors[cite: 1, 4].
- Connect the wider First Cloud AI Journey community with the next wave of GenAI builders through live demos, transparent cost discussions, and Q&A sessions[cite: 1, 2, 3, 4].

### Featured Teams & Projects

- **One Team - KFC Bot Agent** - Anh Duy, Tran Dong, Doan Trung, Minh Viet, Anshul Roy. A multi-channel conversational ordering agent that lets KFC Vietnam customers order directly inside Zalo OA, Messenger, and future channels without app switching. Powered by Amazon Bedrock AgentCore with goals, planning, tools and verification layers. Cost: **$0.006 per order / $88 per month total** for 500 orders/day, 3-5s end-to-end latency, **-60% infra code** versus traditional serverless design[cite: 1].
- **Plan V - SA Professional Native App** - Pham Tien Thuan Phat, Huynh Hoang Long, Le Minh Nghia, Tran Dai Vi, Nguyen An. An agentic Solution Architect assistant that ingests natural-language BRD/PRD requirements, drafts hybrid-cloud architecture, generates editable Drawio + AWS Architecture Icons diagrams, and produces directional cost estimates for ap-southeast-1. Replaces the manual first-draft loop with a chat-sidebar grounded in real company standards[cite: 2].
- **Signal Scout** - Le Tan Luc, Do Hoang Hieu, Trieu Quoc Hao, Nguyen Van Duy Khiem, Nguyen Cong Minh, Nguyen Tran Minh Quan. An enterprise intelligence platform that detects corporate strategic changes early by combining scattered signals (LangFuse traces, TinyFish scraping, Apify feeds) into transparent Maintain / Adapt / Accelerate decisions. Built on the Value Creation & Delivery Canvas with self-service dashboard for risk, competitive intelligence, and B2B account teams[cite: 3].
- **Team 3KA - S.H.E.P.H.E.R.D.** - Huynh An Khuong, Nguyen Quoc Huy, Ngo Quang Khoi, Hoang Le Thanh Duc, Dong Nguyen Phuoc Loc, Dong Truong Hung. Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch - a real-time crowd analytics stack using YOLO + ByteTrack on Amazon SageMaker, with a Bedrock AgentCore + Strands Operation Agent that proactively alerts venue operators when congestion exceeds safe thresholds[cite: 4].

### Key Highlights

#### 1. Agentic AI as the Common Architectural Spine
- **Beyond chatbots:** All four finalist teams converged on an Agent loop (Goal → Plan → Tools → Act → Verify) instead of single-prompt LLM calls, treating tools as the source of truth rather than the model's memory[cite: 1, 2].
- **Bedrock AgentCore as the new baseline:** Three of four teams replaced custom Lambda orchestration with AgentCore primitives, cutting infrastructure code by 40-60% and letting teams focus on tools, prompts, and UX[cite: 1, 4].
- **Domain grounding matters:** Every project paired foundation models with trusted business data (KFC menu & promo rules, AWS architecture standards, corporate filings, camera frames) - the model never invents; tools decide what is real[cite: 1, 2, 3, 4].

#### 2. Cost & Latency Transparency on Stage
- **KFC Bot Agent:** $0.006 per order / $88 per month for 500 orders/day - Bedrock accounts for **75% of the bill**, AgentCore absorbs the rest. End-to-end latency 3-5s including LLM planning round-trips[cite: 1].
- **SA Professional Native App:** Removes manual first-draft cost entirely; what used to be a 1-2 day architecture sketching session becomes a 30-minute iterative chat[cite: 2].
- **Signal Scout:** Built two architecture options and openly compared them on stage - the cost-efficient design keeps the same accuracy while halving monthly run-rate, demonstrating mature FinOps instincts[cite: 3].
- **S.H.E.P.H.E.R.D.:** Inference latency on the YOLO+ByteTrack pipeline was the central engineering challenge; teams shared their frame-skipping, batching, and caching strategies publicly[cite: 4].

#### 3. From Hackathon MVP to Real Product
- **Channel-extensible design:** "Design once, deploy everywhere" was the explicit design principle for KFC Bot Agent - adding a new channel is an adapter, not a rewrite[cite: 1].
- **Diagram-as-code:** SA Professional Native App produces editable Drawio diagrams with official AWS Architecture Icons so architects can keep iterating without lock-in[cite: 2].
- **Evidence-backed decisions:** Signal Scout never lets the agent act without showing the source snippet behind each Maintain/Adapt/Accelerate recommendation, building trust for enterprise risk teams[cite: 3].
- **Operations as a first-class citizen:** S.H.E.P.H.E.R.D. treats venue operators as users, not operators of an algorithm - alerts are explainable, actionable, and tied to dispatch workflows[cite: 4].

#### 4. The Hackathon Emotional Arc - A Shared Story
- **Doubt → Flow → Pride:** Every team walked through the same emotional arc - signing up unsure, hitting the wall in the middle hours, then proudly demoing a finished product at the end[cite: 4].
- **The "small, finished work beats big, broken ideas" principle:** Multiple teams explicitly scoped their MVP down to one workflow done well (one Zalo channel, one SOP document, one signal type, one camera angle) and that constraint saved them[cite: 1, 2, 3, 4].
- **The people you meet matter more than the prize:** Teams repeatedly highlighted the mentors, AWS SAs, and other builders as the real return on the weekend - some collaborations have already continued beyond the hackathon[cite: 1, 4].

---

### Key Takeaways

#### Engineering & Architecture Mindset
- **Tool-grounded agents are the new default:** A well-defined tool surface beats clever prompting. Build the tools first, then teach the model how to use them[cite: 1, 2, 4].
- **Make cost a first-class design constraint:** Every team on stage had a unit-economics slide ($/order, $/month, latency budget). That discipline is what separates a hackathon demo from a deployable product[cite: 1, 3].
- **Verification loops prevent silent failures:** Both KFC Bot Agent and S.H.E.P.H.E.R.D. add an explicit "Verify" step that reconciles the agent's plan against the real cart / real frame state before acting[cite: 1, 4].
- **Composable architectures win over monoliths:** Adapter / connector / tool patterns let teams ship a new channel, business, or capability without rebuilding the agent[cite: 1, 2].

#### Product & User Mindset
- **Start from the user's existing surface:** KFC customers are already on Zalo, so the bot lives in Zalo. Don't force them into your app[cite: 1].
- **Explainability is a feature:** Signal Scout's evidence snippets and S.H.E.P.H.E.R.D.'s explainable alerts are what let non-technical users trust the AI[cite: 3, 4].
- **Scope down to one workflow done well:** Every successful team in this showcase cut features aggressively to ship a coherent demo in time[cite: 1, 2, 3, 4].

#### Personal Growth
- **Showing up is already half the battle:** Most first-time hackathon participants in this batch almost dropped out before the build weekend - none of them regret signing up[cite: 4].
- **Hardship is part of the learning:** All four teams openly shared the messy middle of the weekend (debugging at 3AM, sleep deprivation, accidental env-file commits) as the most valuable part of the experience[cite: 4].
- **Define "done" before you start:** Teams that pre-agreed on a one-page scope and a three-minute demo story consistently finished - those that didn't, didn't[cite: 4].

---

### Applying to Work

- **Adopt tool-grounded agent patterns in internal assistants:** Replace free-form prompt chains for SOP lookups, architecture drafts, and order-handling with an explicit Goal→Plan→Tools→Act→Verify loop, mirroring SA Professional Native App's and KFC Bot Agent's design[cite: 1, 2].
- **Add an evidence-and-citation layer to AI recommendations:** Whenever an AI proposes a decision (Maintain/Adapt/Accelerate, dispatch this operator, add this combo), the UI must show the underlying source the model used - inspired by Signal Scout's evidence-backed design[cite: 3].
- **Pair CV pipelines with an agentic operations layer:** Real-time analytics on its own is not enough; the next layer is an agent that recommends and triggers downstream action - the S.H.E.P.H.E.R.D. pattern is directly applicable to security log triage and queue management[cite: 4].
- **Make FinOps a habit, not an afterthought:** Track $ per workflow and per call from day one; the four teams that did this could defend their architecture decisions on stage with numbers, not vibes[cite: 1, 3].
- **Run an internal "mini-hackathon" before the next big project:** The hackathon-style 24-hour scope, defined roles, and demo-first culture forced every team to ship something coherent - the same mechanics can reset a stalled workstream[cite: 4].

---

### Personal Event Experience

Attending the AABW Hackathon Showcase as an audience member was one of the most energising events of the entire internship:

- **Eight MVPs, eight real architectures:** Each finalist presented not just a demo but a complete agent stack - tools, prompts, cost breakdown, and an honest list of what they would build next. The technical depth exceeded many commercial GenAI launches[cite: 1, 2, 3, 4].
- **A clear snapshot of where GenAI is going:** Seeing four different verticals (conversational commerce, architecture copilot, enterprise intel, real-time CV) converge on the same Bedrock AgentCore + tool-grounded patterns was a strong signal that the agentic-AI abstraction is ready for production[cite: 1, 2, 3, 4].
- **A community that ships:** The mentors, AWS SAs, and other participants openly shared pricing tricks, prompt iterations, and infra templates throughout the day - the same "people you meet matter more than the prize" spirit that defined Team 3KA's reflection[cite: 4].
- **An honest look at the messy middle:** Several presenters shared the 3AM debugging sessions, the accidental env-file pushes, and the "we almost quit at hour 12" stories. That vulnerability made the achievements feel earned and the lessons reusable[cite: 4].

#### Event Visuals

*Photos captured during the AABW Hackathon Showcase - the eight finalist teams, the AWS Vietnam venue, and the community moment.*

![Event 3 - Hackathon Showcase opening and venue 1](/AWS-Workshop/images/4-Event/event%203.png)

![Event 3 - Hackathon Showcase teams and demos 2](/AWS-Workshop/images/4-Event/event%203%20(2).png)

![Event 3 - Hackathon Showcase finalists and Q&A 3](/AWS-Workshop/images/4-Event/event%203%20(3).png)

![Event 3 - Confirmation email](/AWS-Workshop/images/4-Event/email%20xac%20nhan.png)

> **Conclusion:** The AABW Hackathon Showcase was a vivid demonstration that agentic AI on AWS has matured beyond prototypes. By combining Bedrock AgentCore, SageMaker, and grounded tool design, all eight finalist teams shipped measurable products with transparent cost, latency, and explainability budgets[cite: 1, 2, 3, 4]. It left the whole community - including me - with a concrete template for the next generation of cloud-native AI applications.