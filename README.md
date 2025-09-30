# Smart India Hackathon Workshop
# Date:30:09:2025
## Register Number:25013581
## Name:pooja v
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
A Smart Crop Advisory System that provides personalized, timely, and low-cost advisories to small and marginal farmers through:
1. App + SMS + IVR (local language, offline support).
2. Rule-based + AI engine for irrigation, fertilizer, and pest alerts.
3. Weather, soil & satellite data integration for accurate decisions.
4. Market price & government scheme updates for better income opportunities.

## Technical Approach
1. Data Collection
      > Weather APIs, soil/sensor data (optional), satellite imagery, crop history.
2. Advisory Engine
      > Rule-based system → basic agronomy recommendations.
      > AI/ML models → irrigation scheduling, pest/disease detection, yield prediction.
3. Data Processing & Storage.
      > Backend with FastAPI + PostgreSQL/PostGIS.
      > IoT data via MQTT; satellite & weather in centralized DB.
4. User Access
      > Android App (offline support, local language, voice).
      > SMS/IVR for feature phone users.
      > Web Dashboard for agricultural officers.
5. Deployment
      > Cloud hosting with APIs + lightweight offline caching.
      > Scalable microservices for advisories.
      > <img width="524" height="328" alt="SIH" src="https://github.com/user-attachments/assets/76fc6cb2-0281-4cca-8acc-b99f3a327085" />


## Feasibility and Viability
Feasibility
      > Technical: Uses existing weather APIs, open satellite data, and low-cost IoT sensors → easy to implement.
      > Operational: Works on feature phones (SMS/IVR) as well as smartphones → accessible to all farmers.
      > Scalable: Cloud + modular design → can expand from one village to entire states.
      > Affordable: Minimal cost per farmer (shared sensors, free satellite data).
Viability
      > Economic: Reduces crop losses, saves water/fertilizer, improves yield → direct farmer benefit.
      > Social: Local language + voice support → inclusive for low-literacy farmers.
      > Sustainability: Integrates with government schemes and agri-markets for long-term adoption.
      > Impact: Higher income, better decision-making, and improved food security.

## Impact and Benefits
1. Increased Productivity – Farmers get timely advice on irrigation, fertilizer, and pest control → better crop yields.
2. Cost Savings – Optimized use of water, fertilizer, and pesticides reduces expenses.
3. Market Advantage – Real-time mandi prices & scheme updates help farmers earn more.
4. Accessibility – Works via App, SMS, and IVR in local languages → even low-literacy farmers benefit.
5. Sustainability – Encourages efficient resource use, climate-smart farming, and long-term food security.

## Research and References
1. Crop Advisory Systems
      > FAO e-agriculture case studies on digital advisory tools for smallholder farmers.
      > “Digital Green” initiative in India for video-based advisory.
2. Weather & Remote Sensing
      > Indian Meteorological Department (IMD) – Weather APIs & agro-meteorological services.
      > ISRO Bhuvan & Sentinel-2 satellite data for NDVI & crop monitoring.
3. Agriculture & AI
      > ICAR research on crop disease management and decision support systems.
      > Microsoft AI Sowing App (Andhra Pradesh pilot) – 30% yield increase with data-driven advisories.
4. Government Schemes & Market Data
      > eNAM (National Agricultural Market) for mandi prices.
      > PM-Kisan & Kisan Call Centres for farmer outreach.
5. Related Studies
      > Research papers on “AI in Precision Agriculture” (Springer, IEEE Xplore).
      > Case studies of mKrishi (TCS) and Kisan Suvidha app by Govt. of India.
