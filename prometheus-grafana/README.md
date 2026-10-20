# Установка стека Prometheus на VPS Ubuntu через Docker Compose
[Выполнял по шагам по статье](https://cloudzy.com/ru/blog/grafana-prometheus-docker-compose/) 

**P.S.** Для добавления мониторинга за вторым VPS нужно выполнить Шаг 6 из статьи и прописать реальный IP адрес VPS в конфиге prometheus.yml в разделе job_name: 'node' > targets: ['IP:9100']