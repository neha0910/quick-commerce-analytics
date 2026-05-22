# Quick-Commerce Product Analytics Dashboard

A self-initiated product analytics project simulating the data work a Product Analyst does at a quick-commerce company (Zepto / Swiggy Instamart model).

**[→ View Live Dashboard](https://neha0910.github.io/quick-commerce-analytics)**

---

## Why I built this

Quick-commerce product teams live or die by three questions:
- Where are users dropping out of the funnel?
- Which users stick around after day 7 — and why?
- Do our experiments actually move the needle?

This project answers all three using a simulated Pune cluster dataset (April 2024).

---

## Key insights derived

**1. Cart abandonment is a fee-reveal problem**
34% of users who reach the cart don't complete checkout. Delivery fee shown only at the final step causes sticker shock. Recommendation: surface fee earlier, or test a free-delivery threshold nudge at cart stage.

**2. The D7 → D30 retention cliff**
Retention drops from 51% at day 7 to 21% at day 30. Users who place 3+ orders in their first week retain at 2.4× the rate. Recommendation: trigger a targeted incentive at order 2.

**3. ML-timed push beats fixed 6pm send**
A/B test across 22,400 users per arm over 14 days. Dynamic ML-timed push yielded +1.41pp conversion lift (p = 0.023, 82% power) — ~630 incremental orders per day at scale.

---

## Tech stack

- **Analysis:** Python (Pandas, NumPy, SciPy) — funnel aggregation, cohort construction, A/B test sizing
- **Visualisation:** Chart.js, HTML/CSS dashboard
- **Statistical testing:** Two-proportion z-test, power analysis for sample sizing

---

## About me

Data analytics professional targeting product analyst roles, with experience in regression modelling, A/B testing, and marketing mix optimisation at ZS Associates.

**[LinkedIn](https://linkedin.com/in/yourprofile)** · **[Email](mailto:nehatulshyan2@gmail.com)**
