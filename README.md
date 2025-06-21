# Prometheus + Grafana Monitoring

## Проект демонстрирует развёртывание системы мониторинга Linux-сервера с использованием Docker Compose. В состав входят:

- Prometheus — сбор метрик
- Node Exporter — системные метрики
- Grafana — визуализация
- Docker Compose — управление контейнерами

Grafana: http://localhost:3000 (admin / admin)

Prometheus: http://localhost:9090

Node Exporter: http://localhost:9100/metrics

## Примеры работы Grafana и Prometheus доступны в папке screenshots/.

## Запуск

```bash
git clone https://github.com/Kislenky1/Prometheus-Grafana-Monitoring-Stack.git
cd prometheus-grafana
sudo docker compose up -d
