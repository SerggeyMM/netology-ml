# 1

Этот репозиторий содержит Dockerfile для создания контейнера:

1. Копирует файл `1.sh` внутрь контейнера.
2. Устанавливает пакеты Python: `mlflow`, `boto3`, `pymysql`.
3. Запускает вывод файла `1.sh`.

## 2

выполните следующую команду в директории с Dockerfile:

```bash
docker build -t netology-ml:netology-ml .
