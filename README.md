# 🐳 Docker Infrastructure Collection

Коллекция Docker Compose конфигураций для self-hosted сервисов, а так же кастомные Dockerfile. Всё настроено для быстрого развертывания популярных инструментов в домашней лаборатории или на небольшом сервере.

## 📋 Содержание

| Сервис | Описание | Порт по умолчанию | Сложность |
|--------|----------|-------------------|-----------|
| **Uptime-Kuma** | Мониторинг uptime с красивым интерфейсом | 3001 | ★☆☆ |
| **NocoDB** | Альтернатива Airtable, таблицы с API | 8080 | ★☆☆ |
| **Apache Guacamole** | Web-шлюз для RDP/SSH/VNC | 8080 | ★★☆ |
| **Harbor** | Корпоративный Docker Registry с аудитом | 80, 443 | ★★★ |
| **Vaultwarden** | Менеджер паролей (совместим с Bitwarden) | 8080 | ★★★ |

## 🚀 Быстрый старт

```bash
# Клонировать репозиторий
git clone https://github.com/S11ker/Docker.git
cd Docker/Docker-compose-files

# Выберите сервис и запустите
cd uptime-kuma
docker compose up -d
