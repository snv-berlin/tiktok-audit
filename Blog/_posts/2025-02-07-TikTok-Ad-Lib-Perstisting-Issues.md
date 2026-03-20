---
layout: post
title: "⛓️‍💥 TikTok's Ad Library: Persistent Issues and New Challenges*"
date: 2025-02-07 10:00:00
description: "The problems I have when trying to do research on the ad library"
tags: ads, problems
categories: ad-library
featured: false
related_posts: true
author: Martin Degeling
---

* Organizational Note: The project at SNV/interface that build the basis of this blog ended in 2024. This blog is now maintained by Martin Degeling and is no longer affiliated with SNV/interface.*

In the course of my work with [https://aiforensics.org/](AI Forensics), I am still analysing advertisements on TikTok, primarily utilizing the ad library mandated by the Digital Services Act (DSA), which TikTok operates at [https://library.tiktok.com/](https://library.tiktok.com/). 

Last year, we had alread outlined several critical points regarding the [https://tiktok-audit.com/blog/category/ad-library/](ad library), which mostly remain unchanged:

* The ad library does not [https://tiktok-audit.com/blog/2024/Tik-Tok-oclock/](provide any contextual information about the content of the advertisements), such as video descriptions, links, or audio transcriptions.
* Additionally, for ads that contain photos instead of videos, not even the photo is displayed.

Not much has changed, since the ad library has not seen any noticeable update since it's launch in summer 2024. But over the last weeeks I have noticed additional problems that hinder the effective use of the ad library for research and analysis purposes:

### Interface Issues

The ad library's interface presents significant challenges for research and investigation. Consider the following scenario: I wanted to determine if any ads related to Alice Weidel had been posted since January 1, 2025, which would violate TikTok's policies.

**Problem 1: Time Selection**

The time selection field is always set to October 2022, requiring 27 clicks to select the January 2025 period.

**Problem 2: Search Modes**

The search function has two modes:

* **Exact Search**: Using the search term "alice weidel" in quotation marks yields 0 results:
https://library.tiktok.com/ads?region=DE&start_time=1735686000000&end_time=1738710000000&adv_name=%22alice%20weidel%22&adv_biz_ids=&query_type=1&sort_type=last_shown_date,desc

* **Inexact Search**: Without quotation marks, the search yields 747 results:
https://library.tiktok.com/ads?region=DE&start_time=1735686000000&end_time=1738710000000&adv_name=alice%20weidel&adv_biz_ids=&query_type=1&sort_type=last_shown_date,desc

This requires extensive patience and scrolling through endless duplicates of videos from Plarium Global LTD to find relevant information. For example, finding an ad from the user "alice_weidel_deutschland" requires considerable effort: [https://library.tiktok.com/ads/detail/?ad_id=1820418463412306](https://library.tiktok.com/ads/detail/?ad_id=1820418463412306).

### Missing Data

Besides the aforementioned issues with missing description data and slideshows, I have observed additional problems:

* Some ads do not have an "Advertiser" listed, making it impossible to view other videos from the same advertiser using the "See all ads" feature (e.g., [https://library.tiktok.com/ads/detail/?ad_id=1822749626174498](https://library.tiktok.com/ads/detail/?ad_id=1822749626174498)).
* Other videos have an "Advertiser" listed, but clicking on "See all ads" still results in an empty list (e.g., [https://library.tiktok.com/ads/detail/?ad_id=1820795546159121](https://library.tiktok.com/ads/detail/?ad_id=1820795546159121)).
* Loading Issues: An ad that displayed a video last week now shows nothing (e.g., [https://library.tiktok.com/ads/detail/?ad_id=1820418463412306](https://library.tiktok.com/ads/detail/?ad_id=1820418463412306)).

These issues highlight the ongoing challenges with TikTok's ad library, which impede effective research and analysis. Addressing these problems is crucial for ensuring transparency and compliance with regulatory requirements.
