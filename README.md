# Project Showcase
<hr>

Welcome to my project showcase! In this repository, you will find a collection of my projects, showcasing my skills and expertise in the field of business intelligence, data engineering, data science, full-stack development, and other domains. Below is a list that highlights some of the projects I have worked on, along with the stacks I have used. The **Featured Projects** are deeper builds I have chosen to show my different capabilities; while the **Learning Journey** collects my earlier case studies and exercises.

## Featured Projects

### Production & full-stack systems

| No. | Project | Domain/Capability | Stack | Description |
|---|---------|-------------------|-------|-------------|
| 1 | 🛡️ [Graph-Based AML Case Triage & Risk Scoring](https://github.com/namanh-ph/graph-aml-case-triage) | Production data engineering, graph analytics, AML | Python, Polars, DuckDB, NetworkX, Neo4j, scikit-learn, MLflow, Pandera, Streamlit, DVC, Docker, PostgreSQL | End-to-end financial-crime analytics on a banking network. Bronze/Silver/Gold pipeline with DVC lineage, AML rule engine + Isolation Forest + composite risk scoring, case generation with deterministic evidence packs, analyst lifecycle workflows, drift validation, and a Streamlit dashboard for alerts, cases, and audit. |
| 2 | 🌧️ [Rainfall Risk & Parametric Insurance Simulator](https://github.com/namanh-ph/rainfall-risk-and-parametric-insurance-simulator) | Full-stack, geospatial, insurance modelling | Python, FastAPI, SQLAlchemy, PostgreSQL/PostGIS, GeoPandas, LightGBM, MLflow, React, TypeScript, Vite, Tailwind, Leaflet | Full-stack simulator for rainfall exposure and parametric payouts across an SME/property portfolio in Victoria, Australia. PostGIS spatial joins, multi-window rainfall features, risk scoring, payout sensitivity analysis, LightGBM ranking model, FastAPI backend, and a React + Leaflet dashboard with maps, KPIs, and rankings. |

### Modelling & specialised tech

| No. | Project | Domain/Capability | Stack | Description |
|---|---------|-------------------|-------|-------------|
| 3 | ⛓️ [Commitment On Chain - Ethereum dApp](https://github.com/namanh-ph/blockchain-app-etherium-solidity) | Web3, smart contracts, Solidity | Solidity, Ethereum, Truffle, Ganache, Web3.js, MetaMask, Mocha, Chai | Decentralised accountability dApp where users stake ETH against personal goals; on-time completion refunds the stake, missing the deadline routes it to a pre-chosen backup wallet. Contract in Solidity with a Truffle/Ganache dev loop, Mocha + Chai contract tests, and a vanilla JS + Web3.js frontend integrated with MetaMask. |
| 4 | 💹 [ARIMA-GARCH Stock Price Volatility Prediction](https://github.com/namanh-ph/arima-garch-stock-price-volatility-prediction) | Quantitative, time-series modelling | Python | Combines ARIMA and GJR-GARCH to forecast monthly price changes and percentage returns of a Vietnamese equity, capturing both the conditional mean and the asymmetric volatility component that a pure ARIMA misses. |
| 5 | 💳 [Predictive Churn Analysis in Credit Card Banking](https://github.com/namanh-ph/predictive-churn-analysis-banking) | End-to-end stats → ML, banking analytics | Python, SQL, Excel, Power BI, PyCaret, scikit-learn, XGBoost | Investigates churn drivers for a credit-card portfolio. SQL data prep, IV and z-tests for variable selection, Power BI segmentation views (customer, card, credit usage, transactions), then Logistic Regression / SVM / XGBoost compared via PyCaret. |
| 6 | 📉 [Market Tail Risk Modelling with GARCH-EVT](https://github.com/namanh-ph/garch-evt-tail-risk) | Quantitative risk, extreme value theory | R, Quarto, rugarch, evir | Compares standard VaR approaches against a GARCH-EVT model for extreme downside risk on Australian equities. Estimates VaR and ES Historical, Normal, GARCH(1,1)-std, and GARCH-EVT (GPD on standardised residuals); Kupiec and Christoffersen backtests. |

### BI & business consulting

| No. | Project | Domain/Capability | Stack | Description |
|---|---------|-------------------|-------|-------------|
| 7 | 🚗 [Business Case: EON Motor Corporation](https://github.com/namanh-ph/business-case-eon-motor-corporation) | BI, scenario modelling, executive reporting | Tableau, Tableau Prep | Financial-performance and cost analysis for an electric-vehicle manufacturer with profitability trends, cost-structure decomposition, what-if scenarios, and forecasts to support executive decisions. Tableau Prep for raw-data wrangling and Tableau for modelling and visualisation. |

## Learning Journey

| No. | Project | Domain/Capability | Stack | Description |
| --- |---------|-------------------|-------|-------------|
| 8 | 👥 [E-Commerce Online Retail Analysis](https://github.com/namanh-ph/ecommerce-retail-analysis) | Customer analytics, clustering | Python | EDA and RFM analysis on a UK online retailer's transactions . K-Means and Hierarchical clustering split customers into lifecycle groups to inform targeted retention strategies. |
| 9 | 📚 [8-week SQL Challenge](https://github.com/namanh-ph/8-week-sql-challenge) | SQL practice, case studies | SQL | The 8-week SQL challenge is a series of case studies that can be solved using SQL. It consists of projects that participants can undertake to practise and apply their SQL knowledge. The challenges are designed to simulate common data analysis tasks that one might encounter in a professional setting. |
| 10 | 💵 [Company Valuation - DCF Analysis](https://github.com/namanh-ph/company-valuation-dcf-analysis) | Finance, valuation modelling | Excel, Python, yfinance | Two complementary DCF approaches: a deep-dive Excel valuation of REA Group (financial-statement forecasting, DuPont decomposition, bottom-up beta, CAPM-based WACC, sensitivity analysis) and a Python pipeline that pulls financials via to run normalised DCF and cross-sectional comparison across multiple firms. |
| 11 | 🎲 [Portfolio Optimisation with Monte Carlo Simulation](https://github.com/namanh-ph/portfolio-optimisation-with-monte-carlo-simulation) | Quant finance, portfolio optimisation | Excel, Python | Optimises a portfolio of VN30 stocks via Monte Carlo simulation. CAPM and risk-return analysis, correlation/covariance review, then random-weight simulation to identify the Sharpe-optimal allocation on five years of historical data. |
| 12 | 🎯 [Business Case: ChemCorp Incorporated](https://github.com/namanh-ph/business-case-chemcorp-incorporated) | Business strategy, Tableau analytics | Tableau | Strategic case study for a chemicals producer facing market-share decline. Tableau analysis of geographical distribution, industry mix, product profitability, seasonality, and negative-margin lines, leading to customer-strategy, market-opportunity, and product-divestment recommendations. |
| 13 | ⚡ [Business Case: American Energy Market Regulator](https://github.com/namanh-ph/business-case-american-energy-market-regulator) | Energy regulation, outage analytics | SQL, Tableau | Study of US power-network outages across 2 years. Frequency, duration, and energy-loss analysis with a focus on Forced outages, and reliability scoring to flag worst-performing energy providers. |
| 14 | 🎒 [Business Case: Hotel Bookings](https://github.com/namanh-ph/business-case-hotel-bookings) | Hospitality, customer & cancellation analytics | SQL, Power BI | SQL data cleaning and Power BI analysis of a Lisbon hotel group's overseas-visitor market. Segmentation by country, seasonality, channel mix, and cancellation-driver analysis. |
| 15 | 💻 [Stock Price Prediction - LSTM vs Transformer](https://github.com/namanh-ph/stock-price-prediction-lstm-vs-transformer) | Deep learning, sequence models | Python | Compares LSTM and Transformer architectures for stock closing-price forecasting. Simple implementations of each evaluated on the same series. |

## Contact
If you have any questions or would like to collaborate on a project, please feel free to contact me via my [LinkedIn Profile](https://www.linkedin.com/in/namanh-pham).

Feel free to explore each project by clicking on the project link above. Thank you for visiting my project showcase!
