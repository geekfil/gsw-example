# Пример подключения виджета
1. Папку со скриптами `guide-screen-widget` необходимо скопировать в корень публичной директории сайта.

2. Установить аттрибут на кнопку или ссылку `data-gsw-open`.
Виджет перехватывает событие клика на ссылку и открывается на весь экран.
Аттрубут можно установить на любой html тег.   
`<a href="#" data-gsw-open>Открыть виджет</a>`

3. Подключаем конфигурацию (конфигурация для удобства вынесена в отдельный файл)   
`<script src="/guide-screen-widget/config.js"></script>`

4. После конфигурации подключем скрипт виджета.    
`<script src="/guide-screen-widget/app.js"></script>`

Порядок подключения скриптов важен.   
Скрипты можно установить в `<head>` или `<body>` секцию.

