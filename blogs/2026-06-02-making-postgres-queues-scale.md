---
title: "Making Postgres Queues Scale"
url: "https://www.dbos.dev/blog/making-postgres-queues-scale"
date: "2026-06-02"
author: "Qian Li and Peter Kraft"
feed_url: "https://www.dbos.dev/blog/rss.xml"
---
This technical article explores how to scale Postgres-backed task queues to handle billions of workflows monthly. The authors share three critical optimizations: using FOR UPDATE SKIP LOCKED clauses to eliminate worker contention, adjusting transaction isolation levels based on queue configuration needs, and making indexes more selective through partial indexing strategies. These improvements enabled their system to achieve over 30,000 workflows per second in throughput.
