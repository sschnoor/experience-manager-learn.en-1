---
title: Basic Next.js app
description: A basic Next.js app that displays a list of WKND adventures and their details
version: Cloud Service
mini-toc-levels: 1
feature: Content Fragments, GraphQL API
topic: Headless, Content Management
role: Developer
level: Beginner
kt: 11368
thumbnail: KT-11368.jpg
index: no
hide: yes
hidefromtoc: yes
---

# Basic Next.js app

This [Next.js](https://nextjs.org/) app demonstrates how to query content using AEM's GraphQL APIs using persisted queries. This application renders a filterable of WKND Adventures, and upon selecting an adventure, displays the adventures full details.

This code:

+ Connects to an AEM Publish service, and does not require authentication
+ Uses the WKND's persisted queries: `wknd-shared/adventures-all` and `wknd-shared/adventures-by-slug`

For a more indepth review of how this Next.js app is built, review the [example Next.js app documentation](../example-apps/next-js.md).