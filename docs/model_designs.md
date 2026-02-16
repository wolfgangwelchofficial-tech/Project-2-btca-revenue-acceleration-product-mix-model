# Model Design

## Objective

Design a lightweight analytical framework that identifies revenue acceleration opportunities through SKU velocity and margin contribution modeling.

The model must be:

- Interpretable by executives
- Repeatable weekly
- Simple enough to scale across locations
- Grounded in real operating metrics

---

## Data Inputs

Primary dataset:
- `data/sales_by_sku_daily.csv`

Supporting dataset:
- `data/product_catalog.csv`

Core fields used:
- Units sold
- Net revenue
- Unit cost
- Unit price
- Category classification

---

## Core Calculations

### 1. SKU Velocity
Average units sold per day.

### 2. Revenue Contribution
Total revenue per SKU and per category.

### 3. Gross Margin
Unit price minus unit cost.

### 4. Margin-Weighted Velocity
Velocity × Gross Margin

This metric identifies SKUs that combine:

- Strong demand
- High profitability
- Scalable revenue impact

---

## Modeling Framework

1. Rank SKUs by revenue contribution.
2. Rank SKUs by margin-weighted velocity.
3. Identify top 20% contribution drivers.
4. Simulate mix shift scenarios:
   - +10–15% exposure increase
   - Incentive alignment
   - Reduced exposure to low-performing inventory

---

## Design Philosophy

This model avoids over-engineering.

It prioritizes:
- Clarity over complexity
- Decision impact over statistical novelty
- Executive usability over technical abstraction

The goal is operational leverage — not academic optimization.
