# Тестовое задание

Также существует решение через [Grafana API](https://grafana.com/docs/grafana/latest/developers/http_api/)

## Локальный запуск

1. В файле `.env` задать переменные окружения
2. Запустить сервис с помощью `docker compose`:
 ```bash
 docker compose up -d
 ```
3. Перейти на http://127.0.0.1:3000

## Запуск сервиса через `Ansimble`

1. В файле `hosts.ini` задать хост сервера
2. Запустить playbook:
```bash
ansible-playbook -i hosts.ini initial.yml
```
Для первичной настройки сервера можно использовать playbook'и из папки `setup`
