<div align="center">
Show Image

Show Image
 
Show Image
 
Show Image
 
<img src="https://komarev.com/ghpvc/?username=Utsav-Thakur&style=flat-square&color=58a6ff"/>

</div>

Who I am

Data Scientist based in Delhi, India — building end-to-end ML systems, graph intelligence engines, LLM-powered platforms, and recommendation systems that solve real business problems across Financial Services, Logistics, Retail, and Entertainment.

MSc Operational Research · University of Delhi · 2025–2027


🏆 Top 25% @ IIT Guwahati Winter Consulting 2025
☁️ Oracle Cloud Infrastructure AI Foundations Certified
🌐 Japanese Language Certification — St. Stephen's College, University of Delhi
📍 Delhi, India  |  🟢 Open to DS / Data & AI Internships 2026



What I've Built


0.941 ROC-AUC · ₹63.8Cr revenue impact · 61,000 titles · 144,867 trips analyzed
I don't just study ML — I ship it.




🏦 AlphaForge — Financial Intelligence Platform

XGBoost · SHAP · PyTorch Transformer · Markowitz · RAG · FAISS · React

5-module financial intelligence system built for JPMorgan/Goldman Sachs-standard analytics.


Credit Risk: XGBoost scorecard on 200K LendingClub loans · ROC-AUC 0.812 · KS Stat 0.47 · SHAP waterfall explaining every prediction to regulators
Price Forecaster: Transformer (PyTorch) on Yahoo Finance data — AAPL, NVDA, RELIANCE.NS, S&P500, NIFTY50 · outperforms LSTM/ARIMA on MAPE
Portfolio Lab: Markowitz + Monte Carlo (5,000 simulations) · efficient frontier · Sharpe maximization on S&P500 + NIFTY50 portfolios
Live Markets: Real-time market feed with VIX overlay, FRED macro indicators, live ticker strip
Forge AI: Zero-API RAG assistant on SEC EDGAR 10-K/10-Q filings (Apple, Microsoft, NVIDIA, JPMorgan, Goldman Sachs) — FAISS + sentence-transformers, no OpenAI key needed


XGBoost SHAP PyTorch FAISS sentence-transformers yfinance FRED SEC EDGAR React FastAPI


👑 BrandIQ — D2C Customer Intelligence Platform

Python · SQL · React · JARVIS AI · Live Data Entry

SQL-driven customer intelligence system for a D2C fashion brand — 3,900 customers, 50 US states.


Engineered 12 features from scratch including 2 competing loyalty definitions — tested both, argued for winner on statistical correlation
SQL segmentation: 8 business queries answering loyalty vs promo-dependency, geographic opportunity, category journey, retention restructuring
JARVIS chatbot (zero API) — answers 15 question categories about customer data using pure JavaScript analytics on live DataContext
Live data entry: CSV upload + manual form entry → all charts re-compute instantly in React Context
Result: identified 1,677 promo-trap customers (43% of base) at margin risk, produced 3-phase promotional sunset plan


Python Pandas SQL SQLite React Recharts Tailwind Zero-API AI


✈️ LoyaltyIQ — Airline Loyalty Analytics System

XGBoost · KMeans · React · Claude AI (SSE Streaming)

End-to-end loyalty analytics on 16,737 real Canadian airline members (2012–2018).


Churn prediction: ROC-AUC 0.941 · F1 0.799 · Precision 0.982 — XGBoost with 16 engineered features, no data leakage (June 2018 cutoff)
CLV interrogation: proved CLV misleads for 50.7% of members (4,228 overestimated + 4,147 underestimated) using forward-scoring composite
KMeans segmentation (k=3): High-Value Loyalists (4.2% churn) · Dormant Members (100% churn · $8,611 avg CLV) · At-Risk Regulars (30.5%)
AI email writer: Claude API streaming via FastAPI SSE → personalised retention emails per member
Dashboard: 10 pages, non-technical marketing manager can identify who needs attention in 4 clicks without reading a manual


XGBoost KMeans Claude API FastAPI React Recharts Tailwind Python SQL


🚚 DeliveryIQ — Graph-Based Logistics Network Intelligence

NetworkX · XGBoost · Folium · React · Zero-API AI

Graph intelligence system for 144,867 Delhivery trip segments across 1,508 facilities.


Built directed weighted graph: 1,508 nodes · 2,847 edges · edge weights = median delay ratio per corridor × route type × time of day
Graph features account for 71.5% of XGBoost model importance — validating the graph-first hypothesis
Betweenness centrality × SLA breach composite → ranked top 5 bottleneck hubs responsible for 41% of all network delays
Quantified ₹63.8Cr annual revenue impact in a 6-page consulting strategy memo to Head of Network Operations
Interactive Leaflet maps: N=10 critical hubs map + N=1,508 full network map + delay heatmap (Folium)
Zero-API AI: 5 pre-computed JSON files (rule-based + ML) replace all API calls at runtime


NetworkX XGBoost Folium React Recharts FastAPI Python Graph ML


🎬 Lumiora — Worldwide Hybrid Recommendation System

Content-Based · SVD · NeuMF (PyTorch) · TMDb · MyAnimeList · MovieLens

Netflix-style hybrid recommendation system covering 61,000 titles across 80+ countries.


6 content types: Movies · TV Series · Anime (Shounen/Shoujo/Seinen/Josei) · K-Drama · Documentaries · Stand-up Comedy
3 recommendation models benchmarked independently then hybridized:

Content-Based (cosine similarity on 150-feature matrix): Precision@10 = 0.31, Coverage = 0.68
SVD Collaborative Filtering (Surprise, 4.8M ratings): RMSE = 1.12, Precision@10 = 0.38
NeuMF Neural CF (PyTorch, GMF + MLP): RMSE = 1.08, Precision@10 = 0.41
Hybrid: Precision@10 = 0.47, NDCG@10 = 0.44 (best across all metrics)



Real datasets: TMDb 45K (real poster URLs via CDN) · MyAnimeList 2023 · MovieLens 25M · Netflix Shows · Korean Drama · Indian Movies IMDb
Cold-start handling: content-based weight = 0.80 for <5 ratings → relevant Day-1 recommendations
Countries: USA · Japan · South Korea · China · India · Russia · France + 73 more


PyTorch scikit-learn Surprise FAISS React Recharts Python Hybrid Recommender


🛒 LoyaltyIQ Airline + LendIQ Digital Lending

XGBoost · Synthetic Data · Credit Policy · CRO Report


LendIQ: Generated 5,000-row synthetic digital lending dataset (correlated defaults, channels, behavioral signals) · XGBoost credit scorecard · Early Warning System (Green/Amber/Red) · 6-page Credit Policy Report addressed to fictional CRO · Streamlit dashboard
TSP/QIGWO Optimizer: Quantum-Inspired Grey Wolf Optimizer in Python · 10-city route optimization · 20% cost reduction vs random baseline · Interactive Leaflet map + HTML dashboard



What I'm building now

pythoncurrent = {
    "AlphaForge"   : "Forge AI zero-API RAG on SEC EDGAR → deploying to GitHub Pages",
    "LoyaltyIQ"    : "Claude AI streaming emails → production FastAPI deployment",
    "DeliveryIQ"   : "Graph bottleneck dashboard → Vercel live demo",
    "Lumiora"      : "TMDb poster integration → worldwide content explorer",
    "Learning"     : "Japanese · Cloud Deployment · Advanced LLMs · Graph Neural Networks"
}


Tools I use

<div align="center">
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image

</div>

GitHub Stats

<div align="center">
<img height="160" src="https://github-readme-stats.vercel.app/api?username=Utsav-Thakur&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Utsav-Thakur&layout=compact&theme=tokyonight&hide_border=true"/>
</div>
<div align="center">
Show Image

</div>

Certifications & Achievements

AchievementOrganisationYear🏆 Top 25% — Winter Consulting (Business Strategy & Analytics)IIT Guwahati2025☁️ Oracle Cloud Infrastructure AI FoundationsOracle2025🌐 Japanese Language Certification (in progress)St. Stephen's College, University of Delhi2025–2026


<div align="center">
0.941 ROC-AUC · ₹63.8Cr revenue impact quantified · 61,000 titles recommended · 144,867 trips analyzed

I have receipts. 🇮🇳

Show Image
 
Show Image
 
Show Image

Open to Data Science & Data/AI Consultant internships 2026

</div>
