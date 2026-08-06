# Power Exchange Market Analytics Dashboard (Power BI)
A multi-page Power BI dashboard tracking India's national power demand, generation mix, power exchange trading volumes, and price trends across regions and time.

## Overview
This dashboard consolidates national-level electricity data — generation capacity, peak demand, regional demand patterns, and power exchange (IEX/PXIL/HPX) trading activity — into an interactive, filterable view spanning multiple years (2023–2025) and sources (Thermal, Solar, Hydro, Wind, Gas, Nuclear, and others).

## Dashboard Pages

### 1. Peak Demand & Generation Capacity
- **Generation capacity during peak periods** — capacity share by source (Thermal 62.55%, Solar 16.54%, Hydro 9.52%, Wind 6.13%, Gas 2.49%, Nuclear, Others) during solar vs. non-solar hours
- **Peak demand tracking** — peak demand in solar hrs vs. non-solar hrs with exact date/time of peak
- **Energy Met & Peak Demand (Month) summary** — Month-over-Month and Year-over-Year comparisons
- **Regional maximum demand map** — state-wise demand visualization across India
### 2. Generation Mix Analysis
- Daily generation breakdown by source (Coal, Gas/Naphtha/Diesel, Hydro, Lignite, Solar, Wind)
- Annual and monthly generation trends by resource
- Annual and monthly installed capacity trends, filterable by source
### 3. Power Exchange Market Segments
- Monthly volume by market segment (DAM, GDAM, GTAM, HPDAM, HPTAM, RTM, TAM) across exchanges (IEX, PXIL, HPX)
- Current vs. previous volume comparison, with Month-over-Month and Year-over-Year % change
- Weighted average price in power exchange, by market segment
- Buy/sell volume by top market participants (states and utilities)
### 4. Day-Ahead & Real-Time Market Trends
- Day Ahead Market (IEX) volume — buy/sell bids and Market Clearing Price (MCP) trend over June
- Real Time Market (IEX) volume — buy/sell bids and MCP trend over June
- MCP range (max/avg/min) for both Day Ahead and Real Time markets

## Key Findings
- Thermal remains the dominant generation source at over 62% capacity share during peak periods
- Peak demand in June 2025 reached 2,45,419 MW during solar hours, with a 4.98% Month-over-Month increase
- HPTAM segment saw a sharp swing — down ~90% Month-over-Month but up over 137% Year-over-Year
- Day Ahead and Real Time market clearing prices both show a notable dip mid-June before recovering toward month-end

## Tools Used
Power BI (drill-down slicers, map visuals, area/line/bar combo charts, dynamic date filters)

## Files
- `[dashboard_file].pbix` — Power BI dashboard file


# Traders Analysis Dashboard (Power BI)
An interactive Power BI dashboard analyzing electricity trading activity in the Indian power market — covering trading volumes, pricing trends, trader categorization, and regulatory compliance status.

## Overview
This dashboard analyzes electricity transaction data across traders, tracking short-term vs. long-term trading volumes, monthly price trends, and trader classification by license category. Data spans April 2024 through March 2025.

## Dashboard Pages

### 1. Trading Volume Analysis
- **Short-term vs. long-term transaction comparison** — monthly trend across traders
- **Total electricity transacted by top 5 traders** — donut chart showing market share (PTC leads at 37.40%, followed by SECI, NVVN, AEL, TPTCL)
- **Volume of electricity transacted by traders (Form IV)** — detailed breakdown by trading category (RTC, Peak, Off-Peak, Banking, Cross-Border) across all traders
### 2. Price Analysis
- **Monthly maximum, minimum & weighted average price** — summary bars showing price range (₹3.01 min to ₹9.94 max)
- **Peak, off-peak & RTC value based price comparison** — month-over-month price trend from April 2024 to March 2025, showing a general decline in prices through the year (₹8.20 in April 2024 down to ₹5.76 by March 2025)
### 3. Trader Categorization & Compliance
- **Traders by category wise** — Sankey-style flow chart showing distribution of 55 total traders across 5 license categories
- **Status of traders** — compliance tracking across annual reports, annual return of inter-state transactions, annual license fee, and standards of performance

## Key Findings
- PTC and SECI together account for over half (60%) of total electricity transacted among the top 5 traders
- Electricity prices showed a clear downward trend across the year, dropping from a peak of ₹8.20 in April 2024 to ₹5.76 by March 2025
- Category V has the highest number of licensed traders (22), followed by Category I (13)

## Tools Used
Power BI (interactive slicers, drill-down filters, Sankey diagram, donut and line charts)

## Files
- `[dashboard_file].pbix` — Power BI dashboard file
