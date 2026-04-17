---
layout: post
title: "❓ (AIF) TikTok's Research API: Problems without Explanations"
date: 2025-06-12 10:00:00
description: "TikTok's Research API fails to provide metadata for one in eight videos, undermining independent research"
tags: methodology, analysis, API
categories: research
featured: false
related_posts: true
author: Carlos Entrena-Serrano, Martin Degeling, Salvatore Romano, Raziye Buse Çetin
---

*This report was published by [AI Forensics](https://aiforensics.org/work/tk-api). A summary was published on [TechPolicy.Press](https://www.techpolicy.press/unpacking-tiktoks-data-access-illusion/).*

The Digital Services Act mandates that very large online platforms provide researchers access to data. TikTok's Research API is the primary mechanism for this. Our investigation reveals that the API systematically fails to return metadata for a significant share of videos — including high-profile official content and advertisements — without any explanation.

An interactive dashboard exploring our findings is available at [playground.tiktok-audit.com/api-na/](https://playground.tiktok-audit.com/api-na/).

## Key Findings

**One in eight videos inaccessible.** Testing 260,000 TikTok URLs via data donation methodology over 64 days, we found that approximately 12.5% of videos cannot have their metadata retrieved through the Research API, despite being publicly visible on the platform.

**Official TikTok content excluded.** Videos published by TikTok's own corporate account — including CEO statements with over 30 million views — are not accessible via the API. This makes it impossible for researchers to study official platform communications.

**Major creators missing.** Content from prominent accounts including Taylor Swift, Brook Monk, and major news outlets cannot be retrieved, creating systematic blind spots in research datasets.

**Thousands of ads hidden.** Advertisements that are publicly visible in the ad library are not accessible through the Research API, undermining cross-referencing between commercial content and organic content studies.

**Unexplained account exclusions.** Approximately 1% of creators appear to be randomly excluded from API access, with no explanation provided by TikTok.

## Research Methodology

The investigation used two complementary approaches: (1) systematic testing of 260,000 TikTok URLs from data donations over 64 days, comparing API responses against direct web access; and (2) real-time monitoring of 100 daily videos from German For You Pages, verified against web scraping results.

## Implications for Research

The unreliability of the Research API is not merely a technical inconvenience — it directly compromises research validity. Studies using data donation methodologies rely on complete datasets to draw conclusions about algorithmic behavior. Systematic gaps in API coverage mean that research findings may be skewed by the very content that is most prominent or commercially significant.

Previous work on [TikTok's data access landscape](https://tiktok-audit.com/blog/2023/the-TikTok-research-API-falls-woefully-short/) identified structural issues with the API when it launched. This report documents that those problems persist and have new dimensions. We call on TikTok to provide transparency about the criteria for API exclusions and to remediate the gaps as a matter of DSA compliance.
