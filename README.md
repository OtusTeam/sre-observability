# otus-observability

# Зависимости
docker pull prom/prometheus:v2.47.2
docker pull grafana/mimir:2.10.3
docker pull grafana/promtail:2.9.2
docker pull grafana/loki:2.9.2
docker pull grafana/tempo:2.3.0
docker pull grafana/grafana:10.2.0
docker pull grafana/agent:v0.37.1
docker pull otel/opentelemetry-collector-contrib:0.88.0
k6s https://k6.io/

# Деплой
Установить app.py из репозитория sre-app
запустить тесты k6
