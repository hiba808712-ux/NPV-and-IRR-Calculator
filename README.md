A Python-based financial modelling project designed to evaluate investment feasibility using Net Present Value (NPV) and Internal Rate of Return (IRR) techniques under multiple economic scenarios.

The model performs dynamic cash flow analysis, scenario testing, and risk assessment to support smarter capital budgeting and investment decision-making.

Overview

This project simulates real-world investment analysis by allowing users to input:

Initial investment
Required rate of return
Project duration
Annual cash flows

The system then evaluates project viability across:

Base Case
Best Case (Bull Market)
Worst Case (Bear Market)

using automated NPV and IRR calculations.

Key Features
Dynamic Financial Modelling
User-defined cash flow inputs
Adjustable discount/required return rates
Flexible investment horizons
Scenario-Based Analysis

Automatically generates:

Base Case projections
Bullish market scenarios
Bearish market scenarios

to assess investment resilience under changing economic conditions.

NPV & IRR Evaluation

The system calculates:

Net Present Value (NPV)
Internal Rate of Return (IRR)

to determine project profitability and investment attractiveness.

Decision-Making Logic

Projects are categorized as:

ACCEPT ✅
ACCEPT (Risky) ⚠️
REJECT ❌

based on financial performance and required return thresholds.

Risk Assessment Engine

Performs overall project risk analysis by evaluating scenario outcomes and classifying investments as:

SAFE
MODERATE RISK
HIGH RISK
Tech Stack
Python
Microsoft Excel
Financial Modelling
Capital Budgeting Techniques
Scenario & Sensitivity Analysis
Core Concepts Used
Discounted Cash Flow (DCF)
Net Present Value (NPV)
Internal Rate of Return (IRR)
Risk Analysis
Scenario Forecasting
Investment Decision Modelling
Workflow
User inputs project assumptions
Python validates financial inputs
Scenario cash flows are generated
NPV and IRR calculations are performed
Investment decisions and risk summaries are displayed
Example Output
--- Base Case ---
NPV: 12500
IRR: 18.4%
Decision: ACCEPT ✅

--- Worst Case ---
NPV: -3200
IRR: 8.1%
Decision: REJECT ❌
