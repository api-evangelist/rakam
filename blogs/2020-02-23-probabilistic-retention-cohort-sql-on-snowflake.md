---
title: "Probabilistic Retention Cohort SQL on Snowflake"
url: "https://rakam.io/blog/probabilistic-retention-cohort-sql-on-snowflake/"
date: "2020-02-23"
feed_url: "https://rakam.io/blog/index.xml"
---
TL;DR: Retention cohorts are expensive to generate, especially if you’re working on a database lacking analytic functions. A deterministic approach is; joining ‘first action’ to ‘returning action’ steps and counting the distinct connectors (user or device identifiers). Joining huge amounts of data should be avoided when working on big data.
