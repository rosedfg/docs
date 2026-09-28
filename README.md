# Matrix Network Docs

Документация VPN-сервиса Matrix Network на [Mintlify](https://mintlify.com).

## Структура

```
docs.json        настройки сайта и навигация
index.mdx        главная
quickstart.mdx   быстрый старт
connect/         инструкции по платформам
account/         подписка и устройства
troubleshooting.mdx, faq.mdx
logo/, favicon.svg
```

Новая страница = новый `.mdx` файл + строка в `navigation` в `docs.json`.

## Локальный просмотр

```bash
npm i -g mint
mint dev          # http://localhost:3000
mint broken-links # проверка ссылок
```

## Деплой

Сайт хостится на Mintlify: GitHub-приложение Mintlify пересобирает сайт при каждом push в рабочую ветку. Домен и ветка настраиваются в [dashboard.mintlify.com](https://dashboard.mintlify.com).
