### Firman Aulia Insani

Backend engineer in Jakarta. I work on government-scale systems: PHP and Go services on MariaDB,
with Kafka, Elasticsearch and Kubernetes around them. Most of my time goes to the unglamorous half
of backend work, which is keeping things up under real load, and making migrations boring enough to
run at 22:00.

```text
$ whoami
backend engineer @ PT Virtue Digital Indonesia, on-site with a public-sector client

$ cat stack
lang   go · php (yii1/yii2) · java · python · sql
data   mariadb · postgres · redis · elasticsearch · clickhouse
bus    kafka
infra  docker · kubernetes · openshift · jenkins · nginx · linux/freebsd

$ tail -n 3 changelog
2026-10  moved a kafka cluster from 1 host to 3: 16 min downtime, 0 of 13 in-flight messages lost
2026-08  cross-agency integration: per-document payments, bulk callback, audit trail, backfill
2025-07  name search moved to elasticsearch before a nationwide launch; outages stopped
```

**Building**

- [logpilot](https://github.com/firmanains/logpilot) — self-hosted log ingestion and alerting. Go ingestor → Kafka → ClickHouse, with a Redis-backed alert evaluator. In development.
- [cinema-ticketing](https://github.com/firmanains/cinema-ticketing) — clean architecture in Go, with the tests actually written.
- [backend-engineering-vault](https://github.com/firmanains/backend-engineering-vault) — notes I re-read: foundations through distributed systems, Go-first.

**Reach me**

[firmanains.github.io](https://firmanains.github.io) · [linkedin](https://www.linkedin.com/in/firmanains) · firmanains@gmail.com
