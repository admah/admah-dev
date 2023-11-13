---
title: 'Creating a Google Chat Bot with Cloudflare Workers'
description: 'Demo of using Workers with Webhooks'
pubDate: 'Jun 16 2022'
heroImage: '/blog-placeholder-2.jpg'
---

I created [this template](https://github.com/admah/worker-gchat-bot) to help notify me of form submissions in Google Chat channels via Webhooks.

Each time a Google form is submitted, a `POST` request is sent to the Worker, which is turn responds with a `POST` request to the webhook URL. 