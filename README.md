# Bootstrap 5
Руководство Bootstrap 5

Bootstrap - это CSS-фреймворк, который позволяет быстро верстать адаптивные макеты сайтов.

Сайт: https://getbootstrap.com  
Примеры макетов: https://getbootstrap.com/docs/5.2/examples/  
Примеры сеток: https://getbootstrap.com/docs/5.2/examples/grid/  
Иконки: https://icons.getbootstrap.com/  

## Установка Bootstrap
Качаем файлы: https://getbootstrap.com/docs/5.2/getting-started/introduction/

Вставляем шаблон:

    <!DOCTYPE html>
    <html lang="ru">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Макет для Bootstrap</title>
        <link rel="stylesheet" href="bootstrap/css/bootstrap.css" />
        <link rel="stylesheet" href="style.css" />
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.3/font/bootstrap-icons.css" />
    </head>
    <body>
        
        <script src="bootstrap/js/bootstrap.bundle.js"></script>
        <script src="common.js"></script>
    </body>
    </html>

## Разное
- атрибуты `aria-*` можно не добавлять, они необходимы для удобства чтения с экрана и других вспомогательных вещей.
