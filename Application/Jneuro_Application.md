# Y Combinator - Company Application

## Founders

### **How long have the founders known one another and how did you meet? Have any of the founders not met in person?**
**Jneuro:**
The founders have known each other for almost one year and have met in person.
**ResearcherryAI:**
The founders have known each other for almost one year and have met in person.

### **Who writes code, or does other technical work on your product? Was any of it done by a non-founder? Please explain.**
**Jneuro:**
Kirill created the core module that analyzes and formulates unresolved customer needs using prompt engineering, LLM, and DIFI workflows. This module enables AI assistants to be trained to conduct deep, empathetic user interviews. Konstantin built the front-end and developed the module for autonomous, scalable customer interviews by creating and managing empathetic AI agents. Both founders actively write code independently while complementing each other's work.
**ResearcherryAI:**
Kirill developed the core `ProductResearcherAI` agent using the Cursor IDE and advanced prompt engineering. The cursor with the set of ProsuctResearcherI rulles is an the MVP for the future Researcherry platform. Kirill handles all technical work, including rule creation, integration logic, workflow automation and code wrriting for it.

### Founder Video
[Video placeholder]

## Company

### **Company name**
**Jneuro:**
Jneuro
**ResearcherryAI:**
Researcherry AI

### **Describe what your company does in 50 characters or less.**
**Jneuro:**
App trains AI-agnts to find hidden customers needs
**ResearcherryAI:**
Creating product research AI agents for scale customer surveys.

### **Company URL, if any**
**Jneuro:**
https://jneuro-analyze.vercel.app/
**ResearcherryAI:**
(will be provided upon platform launch)

### **Please provide a link to the product, if any.**
**Jneuro:**
https://jneuro-analyze.vercel.app/
**ResearcherryAI:**
Our MVP, the `ProductResearcherAI` agent, operates within the Cursor IDE. We provide access to its repository and rules for pilot customers. The platform is currently under development.

### **What is your company going to make? Please describe your product and what it does or will do.**
**Jneuro:**
Jneuro helps product teams conduct AI-powered customer interviews at scale to uncover hidden custormers needs. Our proprietary technology enables anyone to create and train empathetic AI assistants that can run over 100 simultaneous interviews while maintaining quality and personnal communication. Through extensive research, we've developed a unique algorithm that generates unmatched customer insights.
**ResearcherryAI:**
Researcherry is a no-code platform where product teams and researchers create AI agents to scale customer research. These agents uncover unsatisfied customer patterns across all touchpoints, evaluate the potential revenue impact of addressing them, and provide real-time insights on which user segments and features to prioritize for maximum revenue. The platform enables product managers to handle 9+ research projects simultaneously (vs. 3 manually) and conduct 50+ quality interviews monthly (vs. 30). AI agents operate throughout the customer journey: analyzing communications, scheduling interviews, formulating user insights, and evaluating their impact on key metrics.


### **Where do you live now, and where would the company be based after YC?**
**Jneuro:**
Mar-del-Plata, Argentina/ Los Angeles, the USA.
**ResearcherryAI:**
Mar-del-Plata, Argentina/ Los Angeles, the USA.

### **Explain your decision regarding location.**
**Jneuro:**
Maximum coverage and the ability for personal contacts with YC company founders who create leading products to expand Jneuro in the international market. Los Angeles offers access to a vibrant tech ecosystem, a diverse talent pool, and key industry players. Partnerships with local tech hubs and opportunities for collaboration with innovative startups in the area can facilitates growth and expansion.
**ResearcherryAI:**
The ability for personal contacts with YC company founders who create leading products to expand Researсрerry in the international market. Los Angeles offers access to a tech ecosystem, a talent pool, and innovative companies. Partnerships with local YC members and opportunities for collaboration with it's startups will facilitate growth and expansion.

## Progress

### **How far along are you?**
**Jneuro:**
We have developed a module that analyzes user interviews and quickly generates a structured map of unmet needs, including their importance, frequency, consequences, current solutions, and satisfaction levels—all supported by relevant quotes. This solution reduces interview analysis time by over 5 hours per interview. The underlying interview analysis technology has been tested across more than 20 projects in various sectors, including crypto, real estate, and healthy nutrition. We have secured our first paying client, and since January 20th, the initial version has been undergoing testing with over 15 users across both B2C and B2B segments. The first private release of the interview analysis module launched on February 10th.

**ResearcherryAI:**
We started by developing a Jneurpo - Alghorhytm that analyzes user interviews and generates structured maps of unmet needs with importance, frequency, consequences, and satisfaction. This technology was tested across 20+ projects in crypto, real estate, and nutrition sectors. 

Building on it, we created the `ProductResearcherAI` agent deployed in Cursor IDE (our current MVP for Researcherry platform), currently used by 10+ freelancers managing 5+ research contracts for product companies. The agent's effectiveness is proven across $15,100 in research contracts:
- **3 minutes**: analyze interviews, fill guides, formulate and verify customer needs
- **20 minutes**: synthesize user patterns and generate feature hypotheses 
- **1 hour**: process focus group results into comprehensive reports
- **Proven in 7 sectors**: bankruptcy platforms, dental education, fire-safety systems, bike rentals, flower delivery, exam prep, music platforms

However, onboarding researchers to Cursor reveals critical friction: Git complexity, programming knowledge requirements, and lack of messaging platform integrations decrease productivity per researcher. To solve this, we're building Researcherry - a no-code web platform that enables researchers without coding skills to create, customize, and monetize AI agents with built-in verification algorithms, messaging integrations (WhatsApp/Telegram APIs), and website embedding capabilities for real-time user feedback analysis.

### **How long have each of you been working on this? How much of that has been full-time? Please explain.**
**Jneuro:**
Kirill has over 5 years of experience conducting customer surveys to uncover hidden and unmet needs, having completed more than 2,000 interviews across various sectors. 
**ResearcherryAI:**
Kirill has over 5 years of experience conducting customer surveys to uncover hidden and unmet needs, having completed more than 2,000 interviews across various sectors. 

### **What tech stack are you using, or planning to use, to build this product? Include AI models and AI coding tools you use.**
**Jneuro:**
The current analysis module is built using the DIFY environment and Python. The platform is developed with React 18, TypeScript, Tailwind CSS, Framer Motion, React Router v7, Zustand, TanStack Query, Feature-Sliced Design, React Hook Form + Zod, Claude AI, and Supabase.
**ResearcherryAI:**
Our current MVP is the Cursor IDE where the `ProductResearcherAI` agent operates, leveraging terminal and file system integration. However, Git complexity and programming requirements create onboarding friction for researchers. 

We're building Researcherry as a no-code web platform using cutting-edge agent orchestration technologies:
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
**Jneuro:**
Yes
**ResearcherryAI:**
Yes

### **How many active users or customers do you have? How many are paying? Who is paying you the most, and how much do they pay you?**
**Jneuro:**
1. Product-research company from CIS have started implementation of our solution in february
2. First user—a B2B company that has paid for the product.
3. Several b2c customers
The first Jneuro' customer recommended letter:
https://drive.google.com/file/d/1NiDko-SGqFUDYy23h17xJC3gZR_qn-lQ/view?usp=sharing
**ResearcherryAI:**
We have 10+ freelance researchers and 3 companies using our agent within Cursor. All have paid for research services where the agent was used, gaining access to the agent's ruleset in Cursor environment and subsequently will gain access to our future Researcherry platform. We have a proven company onboarding model: clients pay for research services, then receive agent access for internal use. Our total revenue from these pilots is $15,100. Key contracts include:
- **ArbitrA ($5,000):** Benchmarking of a bankruptcy platform.
- **OHI-S USA ($4,200):** Research for a US-based dental education platform.
- **POST ($3,000):** User-flow generation for a fire-safety IT system.
- **BaliBikes ($1,400):** Market entry research for a scooter rental platform.
- **Trava ($1,000):** Customer churn analysis.
- **Vebium-EGE ($1,000):** Research for an exam preparation platform.
- **UltimateGuitar ($500):** Pilot for agent customization  and learning Cursor IDE for developing agents for reserach purpouses.

### **Do you have revenue?**
**Jneuro:**
yes
**ResearcherryAI:**
yes

### **Where does your revenue come from? If your revenue comes from multiple sources (e.g., multiple products, multiple companies or a mix of consulting and this product), please break down how much is coming from each source.**
**Jneuro:**
The first user—a B2B company rivo.xyz—has paid for using Jneuro technology during its stealth mode development
The second B2B CIS research company have payed for pilot
Several B2C customers
**ResearcherryAI:**
All current revenue comes from delivering research as a service using our proprietary `ProductResearcherAI` agent. As part of the deliverable for these paid contracts (7 confirmed, totaling over $15,100), clients receive access to the agent's customized ruleset to continue leveraging the technology internally using Cursor IDE. This validates the demand for both the service and the underlying tool.

### **If you are applying with the same idea as a previous batch, did anything change? If you applied with a different idea, why did you pivot and what did you learn from the last idea?**
**Jneuro:**
It is our first batch
**ResearcherryAI:**
This is our second application. We pivoted from `Jneuro` after learning a critical lesson about AI limitations.

In `Jneuro`, we created an algorithm that analyzes user dialogues and highlights unmet needs, handling interview processing, guide completion, pattern identification, and synthesis between multiple respondents into unmet job maps for segments. However, we made a crucial mistake: we removed humans from every node of the algorithm's workflow. As data volume increased, output quality decreased because results weren't verified by humans.

We learned that AI cannot replace humans - instead, it should amplify human capabilities for conducting qualitative research at scale. This insight was validated through our pilot with UltimateGuitar, which paid for agent training for their employee to reduce burnout from managing 3+ simultaneous research projects while doubling project capacity per researcher.

Based on this learning, we built `ProductResearcherAI` - a flexible algorithm comprised of rule sets where humans make decisions at every checkpoint. These rules adapt at each research project stage and form the operating guidelines for AI agents helping scale qualitative research. 

While this agent was built in Cursor IDE and secured over $15,000 in research contracts, further expansion requires a full platform for creating product agents accessible to users without programming skills. This led us to `ResearcherryAI` - a no-code environment for creating AI agents that solves Cursor's complexity barriers and integration challenges while ensuring human verification at critical decision points.

### **If you have already participated or committed to participate in an incubator, "accelerator" or "pre-accelerator" program, please tell us about it.**
**Jneuro:**
It is our first batch
**ResearcherryAI:**
No

## Idea

### **Why did you pick this idea to work on? Do you have domain expertise in this area? How do you know people need what you're making?**
**Jneuro:**
Jneuro emerged naturally from the founders' deep domain expertise. Kirill has spent over 5 years conducting customer surveys to uncover hidden and unmet needs, completing more than 2,000 interviews across various sectors. Konstantin brings 3 years of experience developing and moderating AI assistants for major CIS companies, with his systems facilitating over 1 million client dialogues.
**ResearcherryAI:**
This idea was born from desperate necessity. As a freelance researcher abroad facing mounting financial pressures (family obligations, debt, newborn son), Kirill couldn't secure traditional employment due to timezone and visa restrictions. Living in hostel in Argentina, he built the `ProductResearcherAI` agent to clone his workflow alghorhytm to survive financially.

The results were transformative: In just 2 months, Kirill secured 7 research contracts worth $15,100 - enough to restore his family relationships, move out of shared hostel rooms, relocate his family from Argentina to Brazil, and rent a beachfront apartment. His productivity exploded from managing 3-4 projects monthly to 8+ projects, analyzing interviews in 3 minutes vs. 4-5 hours manually, and generating complex user-flows in 20 minutes vs. 5+ hours.

But the bigger validation came from the decentralized impact: 10+ other freelancers now use ProductResearcherAI in Cursor, with companies like UltimateGuitar paying for agent training to prevent employee burnout while doubling project capacity. This proves the market need for AI that amplifies human researchers rather than replacing them. However, Cursor's technical barriers (Git complexity, programming requirements) limit adoption to tech-savvy users. ResearcherryAI will remove these barriers with a no-code platform, enabling any researcher to create and monetize their own specialized AI agents.

### **Who are your competitors? What do you understand about your business that they don't?**
**Jneuro:**
Our competitors include platforms that create AI agents for interview analysis. However, we operate at a deeper level by training neural networks to create these AI assistants, rather than competing directly with AI assistant platforms. We would only face direct competition from companies like OpenAI, Anthropic, if they developed algorithms for continuous analysis of live user dialogues and needs formulation based on ongoing human feedback. Our product specifically focuses on creating the most empathetic product neural networks that continuously learn from newly discovered interpretations of unsatisfied users needs.

**ResearcherryAI:**
Our main competitor is manual research, which costs companies $50-150/hour per researcher and takes 5+ hours to process a single interview. Generic AI tools (ChatGPT, Claude) often hallucinate findings or produce irrelevant patterns, forcing researchers to double-check everything, sometimes doubling workload.

We solve this with a **verified chain-of-thought rules system** that delivers measurable value:
- **20 minutes** to generate complex user-flows vs. **5+ hours** manually (15x speed increase)
- **3 minutes** to analyze interviews vs. **4-5 hours** manually (80x speed increase)  
- **8+ projects/month** capacity vs. **3-4 projects/month** manually (2x throughput)
- **90 interviews/month** vs. **30 interviews/month** with same quality (3x scale)

Competitors like UserTesting provide analysis-silos; Cursor requires programming skills. We uniquely offer a **no-code command center** where researchers build, customize, and monetize their own specialized AI agents without technical barriers. This creates a **network effect**: as more researchers contribute rules to our marketplace, the platform becomes more valuable for everyone.

Our key insight competitors miss: researchers don't want AI to replace them - they want AI that amplifies their expertise while ensuring human verification at every critical decision point. This "human-in-the-loop" approach maintains research quality while achieving unprecedented scale.

### **How do or will you make money? How much could you make?**
**Jneuro:**
Our revenue model includes implementing and customizing the JNEURO solution for 500 companies, plus ongoing subscriptions for employees using our AI assistant training environment. Revenue streams will come from both implementation fees and monthly subscriptions, with a target of reaching $100 million in monthly recurring revenue in 2025.
**ResearcherryAI:**
We'll use a multi-revenue stream SaaS model proven by our current success:

**Core SaaS Tiers:**
1. **Pro Plan:** $150/month for freelance researchers (saves $2,000+/month in manual time)
2. **Team Plan:** $500/seat/month for companies (ROI: 10x through 2x researcher throughput)
3. **Enterprise:** $2,000+/month for large organizations with custom integrations

**Additional Revenue Streams:**
4. **Marketplace:** 10% commission on agent rules sales (projected $10K+ monthly from power users)
5. **Research Services:** Proven $15,100 in 2 months - transitioning clients to platform subscriptions
6. **Training & Consulting:** Onboarding and customization services ($1,000-5,000 per implementation)

**18-month targets:** 200 freelancers + 20 teams (5 seats avg) + 5 enterprises = $80,000 MRR
- Freelancers: 200 × $150 = $30,000
- Teams: 20 × 5 × $500 = $50,000  
- Enterprise: 5 × $2,000 = $10,000
- Plus marketplace commissions (~$10,000)

**Total projected:** $100,000 MRR = $1.2M ARR by month 18, with 30%+ monthly growth trajectory toward $10M ARR by year 3 as network effects compound through marketplace adoption.

### **How much money do you want to raise?**
**Jneuro:**
$300,000 for team expansion, product development, and initial marketing efforts.
**ResearcherryAI:**
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
**Jneuro:**
B2B SaaS
**ResearcherryAI:**
B2B SaaS

### **If you had any other ideas you considered applying with, please list them. One may be something we've been waiting for. Often when we fund people it's to do something they list here and not in the main application.**
**Jneuro:**
A platform where every sales manager, researcher, and entrepreneur can create their own AI agent, which, like a clone, sees and interprets the world through the framework of its creator. It is capable of negotiating, exploring customer pain points, and making sales in the absence of its creator, thereby scaling their activities and learning based on the analysis of the creator's communications and feedback.
**ResearcherryAI:**
This is our primary idea, born from direct experience and market validation.

## Equity

### **Have you formed ANY legal entity yet?**
**Jneuro:**
no
**ResearcherryAI:**
no

### **If you have not formed the company yet, describe the planned equity ownership breakdown among the founders, employees and any other proposed stockholders. If there are multiple founders, be sure to give the proposed equity ownership of each founder and founder title (e.g. CEO). (This question is as much for you as us.)**
**Jneuro:**
50% CTO
49% CEO
1% first angel investor/IR Director
+4% as a sucess fee for IR Director from CEO equity
**ResearcherryAI:**
50% CTO
49% CEO
1% first angel investor/IR Director
+4% as a sucess fee for IR Director from CEO equity

### **Have you taken any investment yet?**
**Jneuro:**
yes
**ResearcherryAI:**
yes

### **List any investments your company has received. Include the name of the investor, the amount invested, the premoney valuation / valuation cap, the type of security sold (convertible notes, safes or stock), and the investment date.**
**Jneuro:**
Investor: Sergey Logunov
Amount Invested: $500 (1%)
Premoney Valuation: $50,000
Type of Security: Agreement for Future Equity
Investment Date: January 2025
**ResearcherryAI:**
Investor: Sergey Logunov
Amount Invested: $500 (1%)
Premoney Valuation: $50,000
Type of Security: Agreement for Future Equity
Investment Date: January 2025

### **How much money have you raised from investors in total in US Dollars?**
**Jneuro:**
500
**ResearcherryAI:**
500

### **How long is your runway? (e.g. 5 months)**
**Jneuro:**
5 months
**ResearcherryAI:**
We are currently generating revenue from pilot projects, which extends our runway. With the current burn rate, we have over 8 months of runway.

### **Are you currently fundraising?**
**Jneuro:**
yes
**ResearcherryAI:**
yes

### **Please provide any relevant details about your current fundraise.**
**Jneuro:**
Yes, we are fundraising to enhance our synthesis module, which processes multiple interviews simultaneously to identify unresolved customer pain points and recurring patterns. We also plan to improve our AI agent training module that combines interview analysis with human feedback to conduct personalized conversations with users and uncover their deeper needs. The exact size of the fundraising round has not yet been determined, as we are currently assessing our financial needs.
**ResearcherryAI:**
We are raising a pre-seed round to build the no-code platform for Researcherry. The funding will be used to hire two engineers to develop the web application, UI/UX, and robust backend needed to move beyond our current Cursor-based MVP. This will solve the onboarding and usability issues we've identified and allow us to scale to the waitlist of researchers who need a non-technical solution.

## Curious

### **What convinced you to apply to Y Combinator? Did someone encourage you to apply? Have you been to any YC events?**
**Jneuro:**
The inspiring founders of YC companies and the collaborative YC atmosphere convinced us to apply
**ResearcherryAI:**
The inspiring founders of YC companies and the collaborative YC atmosphere convinced us to apply

### **How did you hear about Y Combinator?**
**Jneuro:**
YouTube, Interviews with founders and YC partners
**ResearcherryAI:**
YouTube, Interviews with founders and YC partners 