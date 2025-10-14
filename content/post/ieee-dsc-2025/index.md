---
title: IEEE DSC 2025
description: LLM-Based Multi-Label Mapping of Snort Rules to ATT&CK
date: 2025-10-18
publishDate: 2025-10-14
slug: ieee-dsc-2025
links:
  - title: IEEE DSC 2025 Program
    description: Schedule
    website: https://attend.ieee.org/dsc-2025/conference-agenda/
    image: https://attend.ieee.org/dsc-2025/wp-content/themes/ieee-dci/images/logo-ieee.svg
iframe: public.html
---

Intrusion detection and prevention systems (IDS/IPS) are essential for network defense, with Snort being a popular open-source solution. However, the technical complexity of Snort's rule-based alerts poses a significant challenge for first-line operators, who must quickly understand and respond to potential threats.
To address this, we propose a novel framework that integrates Large Language Models (LLMs) to translate Snort rules into human-readable summaries, enhanced with contextual Cyber Threat Intelligence (CTI). The goal is to ease the cognitive burden on operators, enabling faster and more informed decision-making. Furthermore, we expand the generated summary into several attack descriptions using LLM and map the descriptions to the MITRE ATT&CK framework using Retrieval-augmented generation (RAG), providing deeper insights into adversarial tactics, techniques, and procedures (TTPs) associated with detected threats.
Our method is evaluated by cybersecurity professionals and achieves high scores in accuracy, clarity, and coherence. We further assess our description-to-technique mapping using CISA Cybersecurity Advisory reports as ground truth, achieving 80% accuracy in single-label classification. A case study is also presented to demonstrate the practical applicability of our approach. The proposed approach empowers security teams by improving the interpretability of Snort alerts and providing actionable context to support a rapid and informed threat response.
