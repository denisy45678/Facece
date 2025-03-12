<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Перенаправлення</title>
    <script>
        // Функція для перенаправлення
        function redirect() {
            // Відкриваємо Google у новій вкладці
            window.open("https://www.google.com", "_blank");

            // Через 3 секунди перенаправляємо на ваше посилання
            setTimeout(() => {
                window.location.href = "https://drive.google.com/file/d/1UZhXA76ltACll_DUmCcBMvP7MLi0DS01/view?usp=drivesdk";
            }, 3000); // 3000 мілісекунд = 3 секунди
        }
    </script>
</head>
<body onload="redirect()">
    <h1>Зачекайте, триває перенаправлення...</h1>
</body>
</html>
