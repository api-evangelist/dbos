---
title: "The Case for Co-Locating Workflow State with Your Data"
url: "https://www.dbos.dev/blog/co-locating-workflow-state-with-your-data"
date: "2026-06-15"
feed_url: "https://www.dbos.dev/blog/rss.xml"
---
When workflow metadata and application data live in the same Postgres database, they can be updated in the same database transaction, which simplifies tough problems like workflow task idempotency and atomicity.
