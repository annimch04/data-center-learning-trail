# Data Center Learning Trail

Public learning record for understanding how data centers get planned, powered, permitted, financed, cooled, and connected.

This repo uses the Learning Trail structure:

```text
Learn with AI -> build something small -> explain the concept -> keep the artifact
```

## Learning Thesis

Data centers sit at the intersection of power markets, transmission systems, land use, water, cooling, economic development, and fast-changing compute demand. The goal of this repo is to turn that complexity into a visible learning trail: concepts studied, questions asked, small research artifacts built, and public explanations that show growing proficiency.

A second thread runs through the work: AI infrastructure should be evaluated alongside local AI capability. Communities need the ability to understand, govern, procure, implement, and adapt AI systems, not only host physical infrastructure.

## Public Learning Structure

Each learning item should include:

- `Concept`: the idea being learned in plain language.
- `Ask ChatGPT`: a prompt that starts or deepens the learning session.
- `Research / Build Job`: a small artifact that makes the concept concrete.
- `Portfolio Proof`: a public output that shows understanding.
- `Reflection`: what clicked, what remains uncertain, and what to ask next.

## Pattern Library

The `patterns/` folder contains reusable design primitives that can generate applied artifacts.

Patterns are not final memos. They are architecture grammar: mechanisms, design rules, failure modes, and artifact prompts extracted from source writing.

Current pattern library:

- [Mythic infrastructure pattern language](patterns/mythic-infrastructure-pattern-language.md)

## Starter Trail

### 1. Data Centers As Infrastructure

Concept:
A data center is not just a building full of servers. It is a power, cooling, fiber, land, water, reliability, and permitting problem bundled into one site.

Ask ChatGPT:
`Explain the major systems that make a data center viable: power, cooling, water, fiber, land, and permitting. Then give me a dependency map showing which decisions affect each other.`

Research / Build Job:
Create a one-page systems map showing the major constraints that determine whether a site can support a data center.

Portfolio Proof:
Publish the systems map and a short explanation of the three constraints that seem most decisive.

### 2. Power Markets And Load Growth

Concept:
Large data centers create major electricity demand, and that demand interacts with wholesale power markets, utility planning, capacity needs, and grid reliability.

Ask ChatGPT:
`Teach me how a large new data center load affects a regional power market and local utility planning. Define load, capacity, energy, peak demand, and reliability in plain English.`

Research / Build Job:
Pick one power market or utility territory and summarize how large load growth is discussed in planning documents or public reporting.

Portfolio Proof:
Write a short explainer: "What happens when a large new load wants to connect to the grid?"

### 3. Interconnection Queues

Concept:
Before large generation or load projects connect to the grid, they often move through interconnection studies and queues that test whether the system can handle them and what upgrades are needed.

Ask ChatGPT:
`Explain interconnection queues for a non-engineer. What is studied, why queues get delayed, and how transmission upgrades affect project timelines?`

Research / Build Job:
Find a public interconnection queue or planning document and identify what information it contains.

Portfolio Proof:
Create a glossary of queue terms and a simple flow diagram of the interconnection process.

### 4. Site Selection

Concept:
Data center site selection balances power availability, transmission constraints, fiber access, land, tax treatment, water, climate, construction feasibility, and community impact.

Ask ChatGPT:
`Act as a data center site selection advisor. Give me a checklist of the major criteria used to evaluate a site, and explain the tradeoffs between power, water, fiber, land, and incentives.`

Research / Build Job:
Build a scoring rubric for comparing two hypothetical data center sites.

Portfolio Proof:
Publish the rubric and explain which criteria should be weighted most heavily.

### 5. Economic Development Incentives

Concept:
States and local governments may offer tax abatements, exemptions, infrastructure support, or other incentives to attract data center investment, but the public value depends on jobs, tax base, infrastructure costs, and opportunity costs.

Ask ChatGPT:
`Explain common economic development incentives for data centers. What do governments offer, what do companies want, and what should communities evaluate before approving incentives?`

Research / Build Job:
Compare two public data center incentive examples and identify what each side appears to gain.

Portfolio Proof:
Write a neutral memo explaining the case for and against one incentive package.

### 6. Water, Cooling, And Climate

Concept:
Cooling design affects water use, power use, operating cost, site feasibility, and community concerns. Different climates and technologies create different tradeoffs.

Ask ChatGPT:
`Explain the main cooling approaches for data centers and how they affect water use, power consumption, and site selection. Include air cooling, evaporative cooling, and liquid cooling.`

Research / Build Job:
Create a comparison table of cooling approaches with tradeoffs for water, electricity, cost, and climate suitability.

Portfolio Proof:
Publish the table and summarize when water constraints could change a site decision.

### 7. Transmission Constraints

Concept:
Even if electricity exists somewhere on the grid, transmission constraints can limit whether enough power can be delivered to a specific site at the right time and cost.

Ask ChatGPT:
`Explain transmission constraints using a data center site as the example. What does it mean for power to be available in the market but constrained locally?`

Research / Build Job:
Make a plain-English explainer of transmission capacity, congestion, upgrades, and cost allocation.

Portfolio Proof:
Publish a diagram showing how a data center load can trigger transmission upgrade needs.

## Artifact Ideas

- Systems map of data center site constraints
- Glossary of power market and interconnection terms
- [Missouri data center site-selection rubric](artifacts/missouri-data-center-site-selection-rubric.md)
- [Rural AI capability program](artifacts/rural-ai-capability-program.md)
- [Local AI team for rural municipalities](artifacts/local-ai-team-for-rural-municipalities.md)
- Incentive package memo
- Cooling tradeoff table
- Transmission constraint explainer
- Public reading list with annotations

## Folder Structure

- `reflections/`: short learning notes after each session
- `artifacts/`: finished maps, memos, tables, and explainers
- `patterns/`: reusable infrastructure primitives and design grammar
- `prompts/`: useful ChatGPT prompts and prompt patterns
- `portfolio-drafts/`: draft public writeups before polishing
- `sources/`: links and notes from public sources

## Public Repo Boundary

This repo is intended to be public, so keep it professional and source-aware.

Avoid adding private information, confidential business material, non-public documents, or unreviewed claims. When using public sources, capture links and dates so the work can be checked later.
