# Правила проекта

## Фавикон

В `<head>` каждого HTML файла сразу после `<meta charset="utf-8">` должны быть эти теги:

```html
<link rel="icon" type="image/x-icon" href="favicon.ico?v=2">
<link rel="icon" type="image/png" sizes="32x32" href="favicon.png?v=2">
<link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png?v=2">
<meta name="theme-color" content="#e68926">
```

При обновлении файлов фавикона — увеличивай версию `?v=N` во всех страницах для сброса кэша браузера.

При добавлении нового HTML файла или изменении фавикона — проверь все страницы.

## Git

После изменений:

```bash
git add .
git commit -m "favicon"
git push
```
