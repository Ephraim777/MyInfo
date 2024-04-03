
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Центрированное изображение</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            flex-direction: column; /* добавим это, чтобы текст был под изображением */
        }
        img {
            max-width: 30%;
            max-height: 100%;
        }
    </style>
</head>
<body>
    <img src="myphoto.JPG" alt="Описание изображения">
    <font color="green">
        <p>ФИО: Ершов Никита Романович</p>
        <p>Возраст: 20 полных лет</p>
        <p>Местоположение: Московская область (г.Красноармейск)</p>
        <p>Рост: 177 см</p>
        <p>Профессия: Начинающий разработчик C++ (QtCreator)</p>
    </font>
</body>
</html>
