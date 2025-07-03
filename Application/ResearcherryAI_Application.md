# Y Combinator - ResearcherryAI Application

## Founders

### **How long have the founders known one another and how did you meet? Have any of the founders not met in person?**
The founders have known each other for almost one year and have met in person.

### **Who writes code, or does other technical work on your product? Was any of it done by a non-founder? Please explain.**
Kirill developed the core `ProductResearcherAI` agent using the Cursor IDE and advanced prompt engineering. The Cursor IDE with the set of ProductResearcherAI rules is the MVP for the future ResearcherryAI platform. Kirill handles all technical work, including rule creation, integration logic, workflow automation and code writing for it.

### Founder Video
[Video placeholder]

## Company

### **Company name**
Researcherry AI

### **Describe what your company does in 50 characters or less.**
Platform for AI agents for scaling product research

### **Company URL, if any**
(will be provided upon platform launch)

### **Please provide a link to the product, if any.**
Our current MVP is the `ProductResearcherAI` agent operating within Cursor IDE. Pilot customers receive access to the agent's ruleset and documentation. The full ResearcherryAI no-code platform is under development.

### **What is your company going to make? Please describe your product and what it does or will do.**
Researcherry is a no-code platform where product teams and researchers create AI agents to scale customer research. These agents uncover unsatisfied customer patterns across all touchpoints, evaluate the potential revenue impact of addressing them, and provide real-time insights on which user segments and features to prioritize for maximum revenue. The platform enables product managers to handle 9+ research projects simultaneously (vs. 3 manually) and conduct 50+ quality interviews monthly (vs. 30). AI agents operate throughout the customer journey: analyzing communications, scheduling interviews, formulating user insights, and evaluating their impact on key metrics.

### **Where do you live now, and where would the company be based after YC?**
Mar-del-Plata, Argentina/ Los Angeles, the USA.

### **Explain your decision regarding location.**
The ability for personal contacts with YC company founders who create leading products to expand ResearcherryAI in the international market. Los Angeles offers access to a tech ecosystem, a talent pool, and innovative companies. Partnerships with local YC members and opportunities for collaboration with its startups will facilitate growth and expansion.

## Progress

### **How far along are you?**
We started by developing Jneuro - an algorithm that analyzes user interviews and generates structured maps of unmet needs with importance, frequency, consequences, and satisfaction. This technology was tested across 20+ projects in crypto, real estate, and nutrition sectors. 

Building on it, we created the `ProductResearcherAI` agent deployed in Cursor IDE (our current MVP for the ResearcherryAI platform), currently used by 10+ freelancers managing 5+ research contracts for product companies. The agent's effectiveness is proven across $15,100 in research contracts:
- **3 minutes**: analyze interviews, fill guides, formulate and verify customer needs
- **20 minutes**: synthesize user patterns and generate feature hypotheses 
- **1 hour**: process focus group results into comprehensive reports
- **Proven in 7 sectors**: bankruptcy platforms, dental education, fire-safety systems, bike rentals, flower delivery, exam prep, music platforms

However, onboarding researchers to Cursor reveals critical friction: Git complexity, programming knowledge requirements, and lack of messaging platform integrations decrease productivity per researcher. To solve this, we're building ResearcherryAI - a no-code web platform that enables researchers without coding skills to create, customize, and monetize AI agents with built-in verification algorithms, messaging integrations (WhatsApp/Telegram APIs), and website embedding capabilities for real-time user feedback analysis.

### **How long have each of you been working on this? How much of that has been full-time? Please explain.**
Kirill has over 5 years of experience conducting customer surveys to uncover hidden and unmet needs, having completed more than 2,000 interviews across various sectors.

### **What tech stack are you using, or planning to use, to build this product? Include AI models and AI coding tools you use.**
**Current MVP:** The `ProductResearcherAI` agent operates within Cursor IDE, leveraging terminal and file system integration. However, Git complexity and programming requirements create onboarding friction for researchers. 

**Platform We're Building:** ResearcherryAI as a no-code web platform using agent orchestration technologies:
- **Agent Framework**: LangGraph for stateful multi-agent workflows with graph-based execution and memory persistence
- **Multi-Agent Orchestration**: CrewAI for role-based task execution and collaborative agent teams  
- **Frontend**: React/Next.js with visual agent builder using LangGraph's graph interface
- **Backend**: Python/FastAPI with LangChain integration for tool calling and memory management
- **Database**: Vector databases (Pinecone/Chroma) + PostgreSQL for agent rules, conversation history, and user workflows
- **AI Models**: Latest GPT-4o, Claude 3.5 Sonnet, Gemini Pro with function calling and structured outputs
- **Agent Memory**: Long-term memory with retrieval-augmented generation (RAG) for context retention
- **Integrations**: WhatsApp/Telegram APIs, Slack, Discord, web scraping tools, and API connectors
- **Verification**: Multi-agent validation chains with human-in-the-loop checkpoints
- **Monitoring**: LangSmith for agent tracing, performance analytics, and conversation logging
- **Marketplace**: Agent rule templates, workflow sharing, and monetization ecosystem

### **Are people using your product?**
Yes

### **How many active users or customers do you have? How many are paying? Who is paying you the most, and how much do they pay you?**
We have 10+ freelance researchers and 3 companies using our ProductResearcherAI agent within Cursor. All have paid for research services where the agent was used, gaining access to the agent's ruleset in Cursor environment and subsequently will gain access to our future ResearcherryAI platform. We have a proven company onboarding model: clients pay for research services, then receive agent access for internal use. Our total revenue from these pilots is $15,100. Key contracts include:
- **ArbitrA ($5,000):** Benchmarking of a bankruptcy platform.
- **OHI-S USA ($4,200):** Research for a US-based dental education platform.
- **POST ($3,000):** User-flow generation for a fire-safety IT system.
- **BaliBikes ($1,400):** Market entry research for a scooter rental platform.
- **Trava ($1,000):** Customer churn analysis.
- **Vebium-EGE ($1,000):** Research for an exam preparation platform.
- **UltimateGuitar ($500):** Pilot for agent customization and learning Cursor IDE for developing agents for research purposes.

### **Do you have revenue?**
Yes

### **Where does your revenue come from? If your revenue comes from multiple sources (e.g., multiple products, multiple companies or a mix of consulting and this product), please break down how much is coming from each source.**
All current revenue comes from delivering research as a service using our proprietary `ProductResearcherAI` agent. As part of the deliverable for these paid contracts (7 confirmed, totaling over $15,100), clients receive access to the agent's customized ruleset to continue leveraging the technology internally using Cursor IDE. This validates the demand for both the service and the underlying tool.

### **If you are applying with the same idea as a previous batch, did anything change? If you applied with a different idea, why did you pivot and what did you learn from the last idea?**
This is our second application. We pivoted from `Jneuro` after learning a critical lesson about AI limitations.

In `Jneuro`, we created an algorithm that analyzes user dialogues and highlights unmet needs, handling interview processing, guide completion, pattern identification, and synthesis between multiple respondents into unmet job maps for segments. However, we made a crucial mistake: we removed humans from every node of the algorithm's workflow. As data volume increased, output quality decreased because results weren't verified by humans.

We learned that AI cannot replace humans - instead, it should amplify human capabilities for conducting qualitative research at scale. This insight was validated through our pilot with UltimateGuitar, which paid for agent training for their employee to reduce burnout from managing 3+ simultaneous research projects while doubling project capacity per researcher.

Based on this learning, we built `ProductResearcherAI` - a flexible algorithm comprised of rule sets where humans make decisions at every checkpoint. These rules adapt at each research project stage and form the operating guidelines for AI agents helping scale qualitative research. 

While this agent was built in Cursor IDE and secured over $15,000 in research contracts, further expansion requires a full platform for creating product agents accessible to users without programming skills. This led us to `ResearcherryAI` - a no-code environment for creating AI agents that solves Cursor's complexity barriers and integration challenges while ensuring human verification at critical decision points.

### **If you have already participated or committed to participate in an incubator, "accelerator" or "pre-accelerator" program, please tell us about it.**
No

## Idea

### **Why did you pick this idea to work on? Do you have domain expertise in this area? How do you know people need what you're making?**
This idea was born from desperate necessity. As a freelance researcher abroad facing mounting financial pressures (family obligations, debt, newborn son), Kirill couldn't secure traditional employment due to timezone and visa restrictions. Living in hostel in Argentina, he built the `ProductResearcherAI` agent to clone his workflow algorithm to survive financially.

The results were transformative: In just 2 months, Kirill secured 7 research contracts worth $15,100 - enough to restore his family relationships, move out of shared hostel rooms, relocate his family from Argentina to Brazil, and rent a beachfront apartment. His productivity exploded from managing 3-4 projects monthly to 8+ projects, analyzing interviews in 3 minutes vs. 4-5 hours manually, and generating complex user-flows in 20 minutes vs. 5+ hours.

But the bigger validation came from the decentralized impact: 10+ other freelancers now use ProductResearcherAI in Cursor, with companies like UltimateGuitar paying for agent training to prevent employee burnout while doubling project capacity. This proves the market need for AI that amplifies human researchers rather than replacing them. However, Cursor's technical barriers (Git complexity, programming requirements) limit adoption to tech-savvy users. ResearcherryAI will remove these barriers with a no-code platform, enabling any researcher to create and monetize their own specialized AI agents.

### **Who are your competitors? What do you understand about your business that they don't?**
Our main competitor is manual research, which costs companies $50-150/hour per researcher and takes 5+ hours to process a single interview. Generic AI tools (ChatGPT, Claude) often hallucinate findings or produce irrelevant patterns, forcing researchers to double-check everything, sometimes doubling workload.

We solve this with a **verified chain-of-thought rules system** that delivers measurable value:
- **20 minutes** to generate complex user-flows vs. **5+ hours** manually (15x speed increase)
- **3 minutes** to analyze interviews vs. **4-5 hours** manually (80x speed increase)  
- **8+ projects/month** capacity vs. **3-4 projects/month** manually (2x throughput)
- **90 interviews/month** vs. **30 interviews/month** with same quality (3x scale)

Competitors like UserTesting provide analysis-silos; existing AI development tools like Cursor require programming skills and Git knowledge. We uniquely offer a **no-code command center** where researchers build, customize, and monetize their own specialized AI agents without technical barriers. This creates a **network effect**: as more researchers contribute rules to our marketplace, the platform becomes more valuable for everyone.

Our key insight competitors miss: researchers don't want AI to replace them - they want AI that amplifies their expertise while ensuring human verification at every critical decision point. This "human-in-the-loop" approach maintains research quality while achieving unprecedented scale.

### **How do or will you make money? How much could you make?**
We'll use a multi-revenue stream SaaS model proven by our current success:

**Core SaaS Tiers:**
1. **Pro Plan:** $150/month for freelance researchers (saves $2,000+/month in manual time)
2. **Team Plan:** $500/seat/month for companies (ROI: 10x through 2x researcher throughput)
3. **Enterprise:** $2,000+/month for large organizations with custom integrations

**Additional Revenue Streams:**
4. **Marketplace:** 10% commission on agent rules sales (projected $10K+ monthly from power users)
5. **Research Services → SaaS Bridge:** Current $15,100 in proven revenue transitioning clients from service payments to platform subscriptions as they scale usage
6. **Training & Consulting:** Onboarding and customization services ($1,000-5,000 per implementation)

**18-month targets:** 200 freelancers + 20 teams (5 seats avg) + 5 enterprises = $80,000 MRR
- Freelancers: 200 × $150 = $30,000
- Teams: 20 × 5 × $500 = $50,000  
- Enterprise: 5 × $2,000 = $10,000
- Plus marketplace commissions (~$10,000)

**Total projected:** $100,000 MRR = $1.2M ARR by month 18, with 30%+ monthly growth trajectory toward $10M ARR by year 3 as network effects compound through marketplace adoption.

### **How much money do you want to raise?**
We are seeking $750,000 to build a world-class multi-agent platform over 18 months:

**Development Team (65% - $487,500):**
- **2 Senior AI Engineers** ($202,500): LangGraph/CrewAI integration, multi-agent orchestration - $67.5K/year each × 1.5 years
- **2 Full-Stack Engineers** ($180,000): React/Next.js platform with visual agent builder - $60K/year each × 1.5 years  
- **1 DevOps/MLOps Engineer** ($82,500): Infrastructure, agent monitoring (LangSmith) - $55K/year × 1.5 years
- **1 AI Research Engineer** ($22,500): Agent verification algorithms, RAG optimization - $15K/year × 1.5 years (equity-heavy)

**Founders & Go-to-Market (25% - $187,500):**
- **CEO salary** ($93,750): Product strategy, fundraising, enterprise sales - $62.5K/year × 1.5 years
- **CTO salary** ($93,750): Technical leadership, architecture oversight - $62.5K/year × 1.5 years

*All technical salaries are 20-30% below market rate, compensated with substantial equity packages. Founder salaries are 60% below market rate ($180K+ for CEO/CTO in AI startups). Upon closing Series A or reaching $100K MRR milestone, all salaries will normalize to market rates to ensure long-term retention.*

**Infrastructure & Operations (10% - $75,000):**
- **AI model costs** ($36,000): GPT-4o, Claude 3.5, Gemini Pro at production scale
- **Cloud & database costs** ($18,000): AWS/GCP, Pinecone/Chroma hosting, PostgreSQL clusters
- **Enterprise tools** ($12,000): LangSmith monitoring, GitHub Enterprise, security tools
- **Legal & compliance** ($9,000): YC legal, IP protection, enterprise contracts

**Phased hiring approach:** Start with 4 core team members (months 0-6), scale to 7 team members (months 7-18) to optimize cash flow.

**Target:** This runway enables us to reach $100,000 MRR ($1.2M ARR) with 200+ freelancers and 20+ enterprise teams, positioning for Series A at $15M+ valuation.

### **Which category best applies to your company?**
B2B SaaS

### **If you had any other ideas you considered applying with, please list them. One may be something we've been waiting for. Often when we fund people it's to do something they list here and not in the main application.**
This is our primary idea, born from direct experience and market validation.

## Equity

### **Have you formed ANY legal entity yet?**
No

### **If you have not formed the company yet, describe the planned equity ownership breakdown among the founders, employees and any other proposed stockholders. If there are multiple founders, be sure to give the proposed equity ownership of each founder and founder title (e.g. CEO). (This question is as much for you as us.)**
50% CTO
49% CEO
1% first angel investor/IR Director
+4% as a success fee for IR Director from CEO equity

### **Have you taken any investment yet?**
Yes

### **List any investments your company has received. Include the name of the investor, the amount invested, the premoney valuation / valuation cap, the type of security sold (convertible notes, safes or stock), and the investment date.**
Investor: Sergey Logunov
Amount Invested: $500 (1%)
Premoney Valuation: $50,000
Type of Security: Agreement for Future Equity
Investment Date: January 2025

### **How much money have you raised from investors in total in US Dollars?**
500

### **How long is your runway? (e.g. 5 months)**
We are currently generating revenue from pilot projects, which extends our runway. With the current burn rate, we have over 8 months of runway.

### **Are you currently fundraising?**
Yes

### **Please provide any relevant details about your current fundraise.**
We are raising a pre-seed round to build the no-code platform for Researcherry. The funding will be used to hire two engineers to develop the web application, UI/UX, and robust backend needed to move beyond our current Cursor-based MVP. This will solve the onboarding and usability issues we've identified and allow us to scale to the waitlist of researchers who need a non-technical solution.

## Curious

### **What convinced you to apply to Y Combinator? Did someone encourage you to apply? Have you been to any YC events?**
The inspiring founders of YC companies and the collaborative YC atmosphere convinced us to apply

### **How did you hear about Y Combinator?**
YouTube, Interviews with founders and YC partners 