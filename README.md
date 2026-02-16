# BT-California — Revenue Acceleration & Product Mix Optimization (Case Study)

> This repository demonstrates how SKU velocity modeling and product mix analysis can drive measurable revenue acceleration through data-driven decision-making.  
> Synthetic dataset used for demonstration purposes.

---

## Executive Summary

A review of historical sales performance revealed uneven revenue contribution across SKUs and categories.  
Instead of optimizing “sales per head,” the strategy pivoted to:

- Identify high-velocity SKUs
- Increase exposure and availability of top performers
- Reduce low-performing inventory drag
- Shift revenue mix toward higher-margin categories

The result (from role experience):  
**67% increase in weekly revenue ($30K → $50K) driven by product mix optimization and strategic positioning.**

---

## Business Problem

Revenue growth had plateaued due to:
- Overweight exposure to low-velocity SKUs
- Inventory allocation not aligned with demand
- Incentives not aligned to high-margin products

The key question:

> Which SKUs and categories actually drive growth — and how should we shift mix to accelerate revenue?

---

## Analytical Approach

1. Calculate SKU velocity (units sold per day/week)
2. Rank SKUs by revenue contribution
3. Analyze category-level product mix %
4. Identify margin-weighted opportunity segments
5. Model projected revenue impact of mix shift

See:
- `analysis/sku_velocity_calcs.md`
- `analysis/product_mix_analysis.md`

---

## Core Metrics Modeled

- **SKU Velocity**
- **Revenue Contribution %**
- **Category Mix %**
- **Revenue per SKU**
- **Projected Mix Shift Uplift**

## Revenue Distribution Snapshot

![Revenue by SKU](visuals/revenue-by-sku.png)

Source: Synthetic dataset — data/sales_by_sku_daily.csv

This visualization highlights revenue concentration across categories, reinforcing the importance of margin-weighted product mix optimization.

Champagne represents approximately 44% of total revenue in the sample despite lower unit velocity, highlighting revenue concentration and the leverage potential of high-margin categories.
---

## Decision Framework

Revenue acceleration decisions were based on:

- Promote top 20% revenue-driving SKUs
- Reduce or reposition bottom 20%
- Increase exposure for high-margin categories
- Align staff incentives to high-margin velocity items

See:
- `docs/decision_playbook.md`

---

## Data Structure

Synthetic datasets include:

- `data/sales_by_sku_daily.csv`
- `data/product_catalog.csv`

These support:
- Daily SKU velocity calculations
- Revenue modeling
- Category mix simulations

---

## What This Demonstrates

- Data-driven revenue acceleration strategy
- Practical SKU rationalization methodology
- Executive-ready modeling framework
- Strategic pivot capability grounded in analytics

---

**Author:** Wolfgang Welch  
**Focus:** Revenue Optimization • Strategic Modeling • Operational Analytics
