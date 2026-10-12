---
layout: page
title: AI sandbox for 50 developers
description: Secure, logged AI adoption at Salvo Software
importance: 1
category: work
---

**Problem.** Developers wanted AI coding tools, but the repositories hold sensitive client data and the company had no rules for AI use.

**What I built.**

- A development environment on VMware ESXi with a custom Debian build and per-developer sandbox folders isolated with **bubblewrap**, so AI agents cannot read sensitive files or change host permissions.
- Local models running on an **NVIDIA Vera Rubin NVL72** and through Ollama and LM Studio, so sensitive code never leaves company hardware.
- A backend that brokers every request to AI providers, with full logging of who asked what and when.
- The company **AI security framework**: approved tools, data classes, logging and review, enforced by a policy engine.

**Result.** 50 developers use AI daily without exposing sensitive data or the host OS, and every AI interaction is auditable. We are now building our own agent harness.
