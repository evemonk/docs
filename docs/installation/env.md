# Environment variables reference

| Name | Example | Description |
|------|---------|-------------|
| `SECRET_KEY_BASE` | `3508788ace632c...` | Rails secret key for cookies. etc. |
| `EVEMONK_DATABASE_URL` | `postgres://postgres@postgresql/evemonk_production` | Database for rails app. |
| `EVE_ONLINE_SSO_CLIENT_ID` | `c037a...` | EveOnline Client ID from https://developers.eveonline.com/ |
| `EVE_ONLINE_SSO_SECRET_KEY` | `RIgQfJmpd...` | EveOnline Secret Key from https://developers.eveonline.com/ |
| `REDIS_URL` | `redis://redis:6379/1` | Redis server url |
| `SENTRY_DSN` | `https://...:...@sentry.io/111111` | Sentry url. Skip if you don't have sentry account. |
| `RAILS_SERVE_STATIC_FILES` | `true` | Rails serve static files |
| `RAILS_LOG_TO_STDOUT` | `true` | Rails logs to stdout |
| `ELASTICSEARCH_URL` | `http://elasticsearch:9200` | Elasticsearch server url |
| `RAILS_MAX_THREADS` | `2` | Max threads for ruby server puma |
| `RAILS_MIN_THREADS` | `2` | Min threads for ruby server puma |
