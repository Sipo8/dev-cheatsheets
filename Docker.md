# Docker

## Образы
```bash
docker images                  # список образов
docker pull nginx:alpine       # скачать
docker build -t myapp:1.0 .    # собрать из Dockerfile
```

## Контейнеры
```bash
docker ps                      # запущенные
docker run -d -p 8080:80 nginx # запустить в фоне
docker exec -it <id> bash      # зайти в работающий
docker logs -f <id>            # смотреть логи
```

## Очистка
```bash
docker system prune -a         # удалить всё неиспользуемое
```

## docker-compose
```bash
docker compose up -d           # поднять
docker compose down            # остановить
docker compose logs -f web     # логи сервиса
```
