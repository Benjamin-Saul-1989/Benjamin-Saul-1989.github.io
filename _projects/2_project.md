---
layout: page
title: Releases every 10 days, not 30
description: CI/CD and delivery dashboards at Salvo Software
importance: 2
category: work
---

**Problem.** Three development teams in Mexico, the USA and India built code on their own machines, and a new version took about 30 days of development time to reach release.

**What I built.**

- **Azure Pipelines and Azure Repos CI/CD** (plus GitHub Actions) for every team, with a standard branching strategy and release workflow.
- The pipeline that delivers **xmlpids**, the vehicle parameter ID definitions the company's diagnostic hardware uses, to the client.
- A **CVE scanner** that checks every build for known vulnerabilities and notifies the owning dev team automatically.
- **Delivery dashboards** tracking committed code per project, PID accuracy against the legacy version, and user activity.

**Result.** The time between versions fell from **30 days to 10**, three times faster, and local builds ended.
