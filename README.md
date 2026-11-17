# Smart India Hackathon Workshop
# Date:17/11/2026
## Reference Number:26001904
## Name:Priyadharshini S

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution

1. Detailed Explanation of the Proposed Solution

KrishiSetu is a direct-to-buyer agricultural commerce and logistics platform that links Farmer Producer Organizations (FPOs) and individual farmers directly with bulk buyers (retail chains, hotels, hostels, food processors) and hyperlocal consumer groups.
• Unified Digital Storefront. Farmers and FPOs list harvests using simple voice-assisted inputs in regional languages, complete with crop grade, harvest date, and available quantity.
• Smart Order Aggregation. The platform pools small-lot produce from neighboring farms at the FPO level so smallholders can fulfill large institutional orders.
• Integrated Shared Logistics. An on-demand fleet matching module connects aggregated farm gates with mini-trucks and cold-chain carriers using backhaul (return-trip) capacity to slash transport costs.
• AI Demand and Route Engine. Predictive models forecast regional crop demand and dynamically optimize multi-stop pickup and delivery routes.

2. How It Addresses the Problem

• Eliminates Multi-Tier Middlemen. Direct digital discovery and escrow-backed checkout remove 3 to 5 layers of commission agents, village aggregators, and wholesale brokers.
• Solves Fragmentation via FPO Pooling. Small farmers cannot individually supply bulk buyers, so micro-aggregation at the FPO center creates market-ready volumes without middlemen.
• Reduces Logistics Waste. Route optimization and shared transport prevent half-empty truck runs and cut post-harvest transit delays.

3. Innovation and Uniqueness of the Solution

Unlike standard e-commerce clones or existing platforms like eNAM that primarily serve mandi-to-mandi trade, our solution focuses on farm-gate-to-buyer execution:
• Live Mandi Benchmark Pricing. Integrates public Agmarknet daily price feeds to auto-suggest fair floor prices, ensuring farmers earn above local mandi rates while buyers pay below retail.
• Offline-First & Voice-Driven UX. Supports SMS/IVR order alerts and offline listing sync for low-connectivity rural zones.
• Micro-Escrow & Quality Verification. Buyers lock funds in digital escrow upon order placement, and payment releases instantly upon FPO-level digital quality grading and QR-code dispatch scan.


## Technical Approach
<img width="1408" height="768" alt="image_15d138db (1)" src="https://github.com/user-attachments/assets/00f19d07-12da-4375-8619-9e35c353f042" />


## Feasibility and Viability

1. Analysis of Feasibility

• Technical Feasibility. All required components—open geospatial routing (OR-Tools), public price APIs (Agmarknet), and UPI split-payment gateways—are mature, well-documented, and production-ready.
• Operational Feasibility. Partnering with existing FPOs provides immediate access to thousands of farmers, physical collection centers, and basic weighing/grading infrastructure without building warehouses from scratch.
• Financial Viability. A lightweight 2%–3% platform and logistics facilitation fee paid by bulk buyers keeps the platform completely free for farmers while generating sustainable revenue.

2. Potential Challenges and Risks

• Low Digital Literacy & Rural Connectivity. Many smallholder farmers struggle with complex apps or unstable mobile internet.
• Trust Deficit in Quality & Payment. Buyers fear receiving substandard produce, while farmers fear delayed payments.
• Cold-Start Demand Forecasting. Lack of historical platform transaction data during initial rollout can reduce AI forecast accuracy.

3. Strategies for Overcoming Challenges

• FPO Champion Model & Offline Sync. Equip local FPO coordinators with assisted-mode tablets and provide IVR/SMS voice alerts in local languages for farmers without smartphones.
• Standardized Grading Checklists & Escrow. Enforce photo/weight verification at the FPO collection point backed by automated escrow release upon delivery.
• Transfer Learning on Public Datasets. Bootstrap initial demand and price models using historical Agmarknet mandi arrivals, seasonal weather data, and regional consumption benchmarks before platform data matures.


## Impact and Benefits

1. Potential Impact on the Target Audience

• Farmers & FPOs. Direct market access increases net farmer realization by 15% to 25% by capturing margins previously lost to intermediaries.
• Bulk Buyers & Consumers. Institutional buyers and housing societies procure fresher produce at 10% to 18% lower costs with reliable, predictable delivery schedules.

2. Broader Benefits

• Economic. Strengthens rural incomes, reduces price volatility, and creates local gig opportunities for rural mini-truck drivers and FPO quality graders.
• Social. Empowers smallholder farmers with transparent price visibility and formal digital transaction histories, improving their eligibility for institutional credit.
• Environmental. Optimized routing reduces deadhead (empty) truck kilometers and fuel emissions, while faster farm-to-fork transit cuts perishable food spoilage by up to 20%.


## Research and References
• National Agriculture Market (eNAM Portal). Government of India electronic trading portal integrating APMC mandis across states.
• Agricultural Marketing Information Network (Agmarknet). Ministry of Agriculture & Farmers Welfare database for daily commodity arrivals and wholesale prices.
• Small Farmers' Agribusiness Consortium (SFAC FPO Directory). National framework and guidelines for Farmer Producer Organization aggregation and market linkage.
• Google OR-Tools (Vehicle Routing Documentation). Open-source combinatorial optimization suite for Capacitated Vehicle Routing Problems (CVRP) with time windows.
• DALBERG & NITI Aayog Reports on Agricultural Supply Chains. Studies on post-harvest losses in Indian horticulture and the impact of FPO-led direct market linkages.
If you'd like to refine this further for your presentation deck, let me know:
• Whether you need a Mermaid/text system architecture diagram you can convert into an image for your slides
• Your target crop category or region (e.g., perishables like tomatoes/onions vs. grains) to tailor the AI forecasting and cold-chain metrics
• Whether you want a working prototype script (such as a Python route-optimization or price-prediction demo)
I can generate those directly for your pitch.
AI can make mistakes, so double-check responses 
• 
www.sihbuddy.in
SIH26033 — Multiple intermediaries reduce farmers earnings and increase consumer prices. | SIH Buddy
Problem: Multiple intermediaries reduce farmer earnings and consumer prices. Ask: Direct-sale marketplace for farmers/FPOs to sell...
• 
zaidsayyed.in
SIH26033 — Multiple intermediaries reduce farmers earnings and increase consumer prices. | Zaid Sayyed
October 7, 2026 — Problem: Multiple intermediaries reduce farmer earnings and increase consumer prices (SIH26033, Ministry of Consumer Affairs, Food...

