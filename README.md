# Cost-Benefit Analysis of New Night Train Service Concepts

**Transportation Economics, Project Report — Technische Universität München**
Group project (4 members) · *My role: cost modeling, indirect benefits, and methodology*

## Overview

Night train services in Europe sit at an odd point: demand is rising as flight-shaming and sustainability pressure grow, but most operators struggle with outdated rolling stock, low occupancy, and high track access charges. This project ran a full Cost-Benefit Analysis (CBA) on three new night train service concepts for an unserved route — Munich–Berlin–Hamburg — to determine which, if any, would be economically viable through 2040.

## Service concepts evaluated

| | Service 1 — Low-cost | Service 2 — High-speed | Service 3 — Day/night hybrid |
|---|---|---|---|
| Travel time | 8h15m | 6h30m | 8h15m (night) |
| Rolling stock | Couchette + seating cars, bring-your-own bedding | New-generation NightJet sleeper sets | Regular rolling stock, also runs daytime InterCity-style service |
| Strategy | Minimize cost | Compete with day high-speed rail | Avoid depot idle time by running by day too |

## What I did

- **Modeled operational costs**: personnel, energy, route access charges, station fees, track access charges, maintenance/inspection/cleaning, and insurance for all three service concepts, based on BVWP 2030 cost methodology and DB Netz AG price catalogs
- **Built the indirect-benefits quantification**: daytime travel-time savings, mode-shift travel-time savings, and comfort benefits (star-rating-based willingness-to-pay model), including literature review behind each assumption
- **Co-developed the core CBA methodology** (Section 3.1): NPV and BCR formulation, discount rate justification, and the sensitivity analysis framework
- **Wrote and structured ~75% of the final report**, including layout and formatting

## Method

Standard CBA framework per the EU Commission's Guide to Cost-Benefit Analysis of Investment Projects: 16-year horizon (to 2040), 3.5% discount rate, NPV and BCR as decision metrics, followed by one-way sensitivity analysis on occupancy rate, ticket price, and direct costs (±20%).

## Results

| | Service 1 (Low-cost) | Service 2 (High-speed) | Service 3 (Hybrid) |
|---|---|---|---|
| NPV (2040, discounted) | **€50.6M** | €29.0M | €−5.9M |
| BCR (2040, discounted) | **1.55** | 1.25 | 0.97 |

Service 1 — the low-cost, no-frills concept — came out as the most economically viable, despite (or rather because of) having the lowest capital and operating costs. Service 3 was the only concept that failed to break even (BCR < 1), largely because running both day and night service roughly doubled its cost base without a proportional benefit increase.

### Sensitivity analysis

[NPV and BCR sensitivity to occupancy rate, ticket price, and direct cost](figures/01_npv_bcr_sensitivity_analysis.png)

Direct costs turned out to be the dominant driver of project viability for all three concepts — more influential than either occupancy rate or ticket price. A 20% swing in direct costs shifted Service 3's NPV by roughly €32M, more than 5x its base-case value, which is why the report flags direct-cost assumptions as the single most important thing to get right in any follow-up study.

## Full report

The complete report including demand estimation methodology, full cost/benefit breakdowns, and appendices with year-by-year discounted cash flow tables is uploaded in this repository.

## Team

Supervised by Prof. Dr. Constantinos Antoniou and M.Sc. Mohamed Abouelela, TUM Chair of Transportation Systems Engineering
