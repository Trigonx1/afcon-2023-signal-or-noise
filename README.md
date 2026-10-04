# Signal or Noise? What AFCON 2023 Really Tells Us About Nigeria and Africa's Best Players

> An event-level football analytics project using StatsBomb open data to examine expected goals, finishing, player involvement, and Nigeria's AFCON 2023 tournament run.

---

## Why I Built This

Football results can be misleading.

A team can win without creating the better chances. A striker can score more goals than expected without necessarily being an elite finisher. A strong tournament run can also contain a significant amount of randomness.

So instead of asking only:

> **Who won?**

This project asks:

> **What does the underlying data actually support?**

Using event-level StatsBomb data from AFCON 2023, I built an end-to-end analytical pipeline to examine the difference between observable results and the quality of chances behind those results.

The project combines data engineering, statistical analysis, uncertainty estimation, visualization, and Power BI-ready analytical outputs.

---

## The Five Questions

### 1. Did Nigeria create better chances than Côte d'Ivoire?

The first analysis compares Nigeria and Côte d'Ivoire at the match level using:

- Expected goals (xG)
- Non-penalty expected goals (npxG)
- Shots
- Shot quality
- Match-by-match chance creation

The goal is to separate the final scoreline from the underlying quality of the chances created.

---

### 2. Which AFCON 2023 teams finished above or below expectation?

Team finishing is evaluated using goals against expected goals.

Rather than simply ranking teams by:

```text
Goals - xG