---
title: "How to Parallel Index Scan in YSQL For Temporal Joins"
url: "https://www.yugabyte.com/blog/parallel-index-scan-in-ysql/"
date: "Mon, 13 Apr 2026 10:15:58 +0000"
author: "Mark Peacock"
feed_url: "https://www.yugabyte.com/blog/feed/"
---
<p>A common temporal join pattern in analytics used to require extra tweaks in distributed Postgres-compatible systems, but is no longer required due to full support for native PostgreSQL Parallel Query (PQ). Achieve latency gains that scale better by keeping your original schema and query and allowing YSQL to execute a Parallel Index Scan directly.</p>
<p>The post <a href="https://www.yugabyte.com/blog/parallel-index-scan-in-ysql/">How to Parallel Index Scan in YSQL For Temporal Joins</a> appeared first on <a href="https://www.yugabyte.com">Yugabyte</a>.</p>
