# reddit-crypto-bigdata

Pipeline (planned):
Reddit + CoinGecko → Parquet → Spark Aggregation → Elasticsearch → Kibana
Jupyter notebooks for analysis and documentation.

## Structure

- notebooks/: import + processing notebooks
- data/: local data (ignored by git)
- src/: reusable code (later)
- docker-compose.yml: Elasticsearch + Kibana
