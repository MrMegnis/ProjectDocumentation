# Стайлгайд технической документации MenshikovAI

Этот каталог содержит руководство по оформлению технической документации Telegram-бота MenshikovAI. Правила подготовлены для лабораторной работы 3 по дисциплине «Проектная деятельность».

## Локальный просмотр

Из корня репозитория выполните:

```bash
cd style-guide-project
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
mkdocs serve
```

Откройте адрес, который выведет MkDocs. Для проверки сборки выполните `mkdocs build --strict`.

## Разделы

Навигация и названия страниц заданы в `mkdocs.yml`. Правила находятся в каталоге `docs/`. Порядок внесения изменений описан в [CONTRIBUTING.md](CONTRIBUTING.md).
