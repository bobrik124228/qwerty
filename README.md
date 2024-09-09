<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой сайт с ссылками</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            height: 100vh; /* Высота экрана */
            display: flex;
            flex-direction: column;
            justify-content: flex-start; /* Центрирование содержимого */
            align-items: center;
            padding-top: 50px;
        .content {
            position: relative; /* Позиционирование для текста */
            z-index: 1; /* Текст будет отображаться выше фона */
            text-align: center; /* Центрируем текст по горизонтали */
        }
        h1 {
            margin-bottom: 30px; /* Отодвигаем заголовок выше от списка */
            color: #191970;
        }
        ul {
            list-style-type: none; /* Убираем маркеры списка */
            padding: 0;
        }
        li {
            margin: 100px 0; /* Отступы между элементами списка */
        }
        a {
            text-decoration: none; /* Убираем подчеркивание ссылок */
            color: #F0F8FF; /* Цвет ссылок */
            font-weight: bold;
            font-size: 30px; /* Увеличиваем размер текста */
        }
        .link-telegram:hover {
            color: #0000CD; /* Синий цвет для Telegram */
        }
        .link-youtube:hover {
            color: #8B0000; /* Красный цвет для YouTube */
        }
        .link-twitch:hover {
            color: #4B0082; /* Фиолетовый цвет для Twitch */
        }
    </style>
</head>
<body>

<div class="background"></div>
<div class="content">
    <h1>Ссылочки:</h1>
    <ul>
        <li><a href="https://t.me/ducken52" class="link-telegram" target="_blank">Telegram</a></li>
        <li><a href="https://www.youtube.com/@Ducken52" class="link-youtube" target="_blank">YouTube</a></li>
        <li><a href="https://www.twitch.tv/ducken52" class="link-twitch " target="_blank">Twitch</a></li>
    </ul>
</div>

</body>
</html>
