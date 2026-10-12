---
layout: page
title: VIN data pipelines
description: 1,000 VINs an hour for hardware testing
importance: 3
category: work
---

**Problem.** The hardware team needed large numbers of real vehicle VINs to confirm diagnostic code reads vehicle information correctly, and standard scrapers were blocked by bot protection.

**What I built.** Python pipelines for US vehicle marketplaces using rotating proxies, running on a custom Linux server where users choose year, make and model and get the results loaded into a database or emailed as a CSV.

**Result.** About **1,000 VINs an hour** and more than **100,000** collected so far for hardware testing.
