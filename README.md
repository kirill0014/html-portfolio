# html-portfolio
﻿<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ваше ім'я - Портфоліо</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        header, section, footer {
            margin-bottom: 20px;
        }

        header {
            text-align: center;
        }

        section {
            max-width: 800px;
            margin: 0 auto;
        }

        h1, h2, p {
            text-align: center;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        .project {
            margin-bottom: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Ваше Ім'я</h1>
        <p>Шахов Кирило</p>
    </header>

    <section>
        <h2>Про мене</h2>
        <p>Вчусь у группі ПЗ-21.</p>
    </section>

    <section>
        <h2>Мої проекти</h2>

        <div class="project">
            <h3>Лабораторна 1</h3>            
            <img src="LB1.jpg" alt="Проект 1">
        </div>

        <div class="project">
            <h3>Лабораторна 2</h3>            
            <img src="LB2.jpg" alt="Проект 2">
        </div>

        <!-- Додайте інші проекти за аналогією -->

    </section>
   

</body>
</html>
