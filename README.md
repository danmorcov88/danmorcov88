### Hey, I'm Dan

I've spent the last six years as a database administrator in Moldova, working across nine different database engines > SQL Server, Postgres, Oracle, Informix, MongoDB, ClickHouse, and a few others. Most of what I know about data came from running these systems in production and fixing them when they broke.

Lately I've been moving toward data engineering, which mostly means building the kind of pipelines and tooling I always wished I had on the job. The repos below are where that happens — a streaming CDC setup, an ELT pipeline, and a couple of small command-line tools for the stuff that used to cost me hours: watching a table change in real time, or figuring out which query is eating the database alive.

I like tools that are small enough that someone actually runs them, and systems you can reason about when something goes wrong at 2 AM.

A few things I've built:

- **[realtime-ecommerce-cdc](https://github.com/danmorcov88/realtime-ecommerce-cdc)** — streaming changes from Postgres through Debezium, Kafka and Flink into ClickHouse
- **[bnm-exchange-rates-elt](https://github.com/danmorcov88/bnm-exchange-rates-elt)** — an ELT pipeline on the National Bank's exchange rates, with dbt, Airflow and CI
- **[tabletail](https://github.com/danmorcov88/tabletail)** — `tail -f` and `git diff`, but for Postgres tables
- **[pgslow](https://github.com/danmorcov88/pgslow)** — a read-only CLI that finds and explains slow Postgres queries

I'm based in Chișinău, open to data engineering roles both here in Moldova and remote. You can reach me at danmorcov88@gmail.com or on [LinkedIn](https://linkedin.com/in/dan-morcov-780064161).
