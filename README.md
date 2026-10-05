# my-node-app

Учебный проект с CI на GitHub Actions для Node.js.

## Что делает CI

- Линтинг (ESLint)
- Тесты (Jest) на Node.js 18.x, 20.x, 22.x
- Сборка Docker-образа (без публикации)

## Запуск локально

```bash
npm ci
npm run lint
npm test
```

## Docker

```bash
docker build -t my-node-app:latest .
docker run --rm my-node-app:latest
```