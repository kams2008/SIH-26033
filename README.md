# Smart India Hackathon Workshop
# Date: 24/11/2026
## Reference Number: 26015065
## Name: Kamalikaa C

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Agricultural products in India pass through several intermediaries, including commission agents, wholesalers, distributors and retailers, before reaching consumers. Each stage adds costs, increasing consumer prices while reducing the earnings received by farmers.

Small and marginal farmers often lack direct market access, updated price information and sufficient bargaining power. Individual transportation expenses, inefficient distribution and post-harvest losses further affect their income.

Major challenges:
- Multiple intermediaries increase distribution costs.
- Lack of transparent market-price information.
- Limited access to bulk buyers and retailers.
- High transportation expenses for small farmers.
- Food wastage due to inefficient distribution.
- A significant gap between farmer earnings and consumer prices.

The core problem is the gap between the price received by farmers and the price paid by consumers. An efficient, transparent and technology-driven agricultural supply chain is required to reduce unnecessary costs while ensuring fair opportunities for farmers and affordable prices for consumers.

## Proposed Solution
FarmLink – A Smart Collective Agricultural Marketplace is a digital platform connecting farmers, FPOs, retailers, bulk buyers and consumers through a transparent supply chain.

<img width="1312" height="1199" alt="image" src="https://github.com/user-attachments/assets/d9483229-7833-4cc5-9935-f22a878675a6" />

Its key features include:

1. Smart Collective Basket: Combines produce from nearby small farmers into bulk listings to improve bargaining power and attract larger buyers.

2. PricePulse: Displays available mandi prices, historical trends and buyer offers, helping farmers make informed selling decisions.

3. Direct Deal Connect: Enables farmers to connect directly with consumers, retailers and bulk buyers for transparent transactions.

4. Smart Shared Logistics: Groups nearby delivery requirements and suggests shared transportation to reduce individual logistics expenses.

5. FairShare Meter: Displays the price breakdown across the supply chain, including farmer earnings, transportation, handling and retail costs.

6. Farm-to-Table QR Tracking: Allows consumers to scan a QR code and view the product's origin, farmer details and available transaction information.

7. AI-Based Demand Forecasting: Analyses historical sales and seasonal trends to estimate future demand and help farmers plan production.

Innovation: FarmLink combines collective selling, transparent price distribution and shared logistics into one platform, reducing unnecessary intermediaries while retaining essential supply-chain services.
## Technical Approach
FarmLink will be developed as a responsive web application with separate dashboards for farmers, buyers and administrators.

A. Technologies Used:
Technology	                                Purpose
HTML, CSS,              -         JavaScript	Frontend development
Python, Django	        -            Backend development
SQLite / MySQL	        -          Database management
Python libraries	      -            Price and demand analysis
Maps API / OpenStreetMap	-        Location and route suggestions
QR Code Library	           -            Product traceability

B. Implementation Methodology

1. Registration: Farmers and buyers create accounts and enter their details.
2. Crop Listing: Farmers upload crop names, quantities, quality and expected prices.
3. Produce Aggregation: Nearby farmers' listings are combined into collective baskets.
4. Price Analysis: The system compares market prices and available buyer offers.
5. Buyer Matching: Buyers are matched with farmers based on crop, quantity, location and price.
6. Logistics: Compatible deliveries are grouped and shared transportation is suggested.
7. Tracking: QR codes and transaction records provide product traceability and price transparency.

C. Working Prototype

The initial prototype will include farmer registration, crop listing, collective baskets, price comparison, buyer orders, FairShare Meter and QR code generation. Advanced demand forecasting and route optimization will be introduced in later stages.
## Feasibility and Viability
Technical Feasibility
- Uses affordable and open-source technologies such as Python and Django.
- Can operate on smartphones and computers.
- Supports integration with available agricultural market-price data.
- QR tracking and transaction management require no specialized hardware.
  
Economic Feasibility
- Low development costs due to open-source tools.
- Basic platform access can be offered to farmers at little or no cost.
- Potential revenue through logistics services, institutional partnerships and optional premium features.
  
Operational Feasibility
- Simple interface with regional language support.
- FPOs and cooperatives can assist with farmer registration.
- Can initially be implemented in selected villages or districts.
  
Potential Challenges and Solutions:

Challenge	                                  Solution
Limited digital literacy	 -     Simple interface and regional languages
Inaccurate price data	     -     Verified sources and timestamps
Quality differences	       -   Crop grading and buyer verification
Transport coordination	   -     Local transport partnerships
Low user participation	   -    FPO and cooperative partnerships
Data security	             -   Secure authentication and access control

Scalability: FarmLink can begin with a small pilot involving selected farmers and crops, then expand to additional districts and markets. It will complement existing platforms such as e-NAM through its focus on collective selling, price transparency and shared logistics.

## Impact and Benefits
FarmLink aims to create a fairer and more efficient agricultural supply chain.

Social Benefits
- Empowers small and marginal farmers.
- Improves access to market information.
- Encourages digital literacy in rural communities.
- Builds trust between farmers and consumers.
  
Economic Benefits
- Improves farmers' bargaining power.
- Reduces avoidable transportation expenses.
- Provides easier access to bulk buyers.
- Offers consumers better price visibility and potentially more competitive prices.
  
Environmental Benefits
- Encourages shared transportation.
- Reduces avoidable food wastage.
- Improves distribution efficiency.
- Promotes better utilization of agricultural resources.
  
Performance Evaluation
- Improvement in farmers' average selling prices.
- Reduction in transportation costs.
- Reduction in post-harvest losses.
- Increase in direct farmer-buyer transactions.
- Improvement in order completion time.
## Research and References
The proposed solution is supported by government research and existing agricultural initiatives.
1. RBI – Dynamics of Agriculture Supply Chain (2025):
A February 2025 RBI study found that farmers' share in consumer prices ranged from 40% to 67% across selected crops, highlighting the need for improved price transparency and supply-chain efficiency. 
2. NABCONS – Post-Harvest Loss Study:
A study commissioned by the Ministry of Food Processing Industries estimated vegetable post-harvest losses at 4.87%–11.61%, demonstrating the importance of efficient storage and transportation. 
3. e-NAM – National Agriculture Market:
A Government of India initiative providing an electronic trading platform connecting agricultural markets, farmers and buyers.
4. RBI – Agriculture Supply Chain Study (2024):
Research examining agricultural supply-chain relationships and the importance of better market infrastructure and competition.
