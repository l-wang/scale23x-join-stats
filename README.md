# scale23x-join-stats
SCaLE 23x Talk: Helping the Planner Help You - Extended Statistics in PostgreSQL

#### Hacker's List Discussion & PoC Patch
[Re: Is there value in having optimizer stats for joins/foreignkeys?](https://www.postgresql.org/message-id/CAK98qZ0LwJbUoiZjjFXitojHy4UskkjYDiSd_JZfGE9LbfZm9w%40mail.gmail.com)

#### Join Order Benchmark (JOB) Repo:
[l-wang/join-order-benchmark](https://github.com/l-wang/join-order-benchmark)

#### Relavent Past Talks
[Louise Leinweber, “A Deep Dive into Statistics”, PGConfEU2024](https://www.postgresql.eu/events/pgconfeu2024/sessions/session/5747/slides/559/postgres_statistics_presentation.pdf)

#### Relavent Work
[postgrespro/aqo](https://github.com/postgrespro/aqo)
[pg_plan_advice](https://www.postgresql.org/message-id/flat/CA%2BTgmoZ-Jh1T6QyWoCODMVQdhTUPYkaZjWztzP1En4%3DZHoKPzw%40mail.gmail.com)
[pg_hint_plan](https://github.com/ossc-db/pg_hint_plan/)

#### References
[Leis et al., "How Good Are Query Optimizers, Really?" PVLDB 2015](https://www.vldb.org/pvldb/vol9/p204-leis.pdf)
[Leis et al., "Cardinality Estimation Done Right: Index-Based Join Sampling" (CIDR 2017)](https://www.cidrdb.org/cidr2017/papers/p9-leis-cidr17.pdf)
[Leis et al., "Still Asking: How Good Are Query Optimizers, Really?" PVLDB 2025](https://www.vldb.org/pvldb/vol18/p5531-viktor.pdf)
[Zhang et al., "Simple Adaptive Query Processing vs. Learned Query Optimizers." VLDB Journal 2025](https://link.springer.com/article/10.1007/s00778-025-00936-6)
[Wang et al., "Are We Ready For Learned Cardinality Estimation?" PVLDB 2021](https://www.vldb.org/pvldb/vol14/p1640-wang.pdf)
[LpBound: Pessimistic Cardinality Estimation Using ℓp-Norms of Degree Sequences](https://dl.acm.org/doi/pdf/10.1145/3725321)
[Kipf et al., "Learned Cardinalities: Estimating Correlated Joins with Deep Learning" CIDR 2019](https://arxiv.org/pdf/1809.00677)
[Hilprecht et al., "DeepDB: Learn from Data, not from Queries!" PVLDB 2020](https://arxiv.org/pdf/1909.00607)
[Yang et al., "NeuroCard: One Cardinality Estimator for All Tables" PVLDB 2021](https://arxiv.org/abs/2006.08109)
[Han et al., "ByteCard: Enhancing ByteDance's Data Warehouse with Learned Cardinality Estimation" SIGMOD 2024](https://arxiv.org/pdf/2403.16110)
[Shankhdhar et., "Presto’s History-based Query Optimizer" PVLDB 2024](https://www.vldb.org/pvldb/vol17/p4077-shankhdhar.pdf)
[SQL Server CE Feedback](https://learn.microsoft.com/en-us/sql/relational-databases/performance/intelligent-query-processing-cardinality-estimation-feedback?view=sql-server-ver17)
[Oracle Adaptive Query Optimization](https://oracleapex.com/ords/features/r/dbfeatures/features?feature_id=344)
[Spark Adaptive Query Execution](https://spark.apache.org/docs/latest/sql-performance-tuning.html#adaptive-query-execution)
