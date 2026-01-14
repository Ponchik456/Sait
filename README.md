<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Антицеллюлитный массаж | Салон красоты</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Arial, sans-serif;
        }

        body {
            color: #333;
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: #8e44ad;
            color: white;
            text-align: center;
            padding: 30px 0;
            margin-bottom: 30px;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .service-image {
            width: 100%;
            height: 400px;
            background: linear-gradient(135deg, #9b59b6, #8e44ad);
            border-radius: 8px;
            margin-bottom: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2rem;
        }

        .section {
            margin-bottom: 40px;
        }

        .section h2 {
            color: #8e44ad;
            margin-bottom: 20px;
            font-size: 1.8rem;
            border-bottom: 2px solid #8e44ad;
            padding-bottom: 5px;
        }

        .section p {
            margin-bottom: 15px;
            font-size: 1.1rem;
        }

        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .benefit-card {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            border: 1px solid #eee;
        }

        .benefit-card h3 {
            color: #8e44ad;
            margin-bottom: 10px;
        }

        .price-box {
            background: #e8f4e8;
            padding: 25px;
            border-radius: 8px;
            text-align: center;
            border: 2px solid #27ae60;
        }

        .price {
            font-size: 2.2rem;
            font-weight: bold;
            color: #27ae60;
            margin: 15px 0;
        }

        .btn {
            display: inline-block;
            background: #8e44ad;
            color: white;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 15px;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #7a288a;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            .service-image {
                height: 250px;
                font-size: 1.5rem;
            }

            .section h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Антицеллюлитный массаж</h1>
            <p>Эффективное решение для коррекции фигуры и улучшения качества кожи</p>
        </div>
    </header>

    <div class="container">
        <div class="service-image">
            Изображение процедуры массажа
        </div>

        <section class="section">
            <h2>Что это такое?</h2>
            <p>Антицеллюлитный массаж — это специализированная техника воздействия на подкожно-жировую клетчатку, направленная на устранение целлюлита, улучшение микроциркуляции крови и лимфодренажа.</p>
            <p>Процедура способствует выведению токсинов, активизации обменных процессов и повышению упругости кожи.</p>
        </section>

        <section class="section">
            <h2>Преимущества процедуры</h2>
            <div class="benefits">
                <div class="benefit-card">
                    <h3>Устранение целлюлита</h3>
                    <p>Разрушает жировые отложения и выравнивает поверхность кожи.</p>
                </div>
                <div class="benefit-card">
                    <h3>Улучшение кровообращения</h3>
                    <p>Стимулирует кровоток и насыщение тканей кислородом.</p>
                </div>
                <div class="benefit-card">
                    <h3>Лимфодренажный эффект</h3>
                    <p>Устраняет отёчность и выводит лишнюю жидкость.</p>
                </div>
                <div class="benefit-card">
                    <h3>Повышение упругости</h3>
                    <p>Улучшает тонус кожи и делает её более гладкой.</p>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>Как проходит процедура?</h2>
            <p>Сеанс длится 60 минут и включает:</p>
            <ul>
                <li>Подготовительный этап — лёгкое разогревающее воздействие</li>
                <li>Основной этап — интенсивная проработка проблемных зон</li>
                <li>Завершающий этап — успокаивающие приёмы и нанесение уходового средства</li>
            </ul>
            <p>Рекомендуется курс из 8–12 сеансов с периодичностью 2–3 раза в неделю.</p>
        </section>

        <section class="section">
            <h2>Противопоказания</h2>
            <ul>
                <li>Беременность и период лактации</li>
                <li>Варикозное расширение вен</li>
                <li>Кожные заболевания в стадии обострения</li>
                <li>Онкологические заболевания</li>
                <li>Тромбофлебит</li>
                <li>Острые инфекционные заболевания</li>
            </ul>
        </section>

        <section class="section">
            <div class="price-box">
                <h2>Стоимость услуги</h2>
                <div class="price">2 500 ₽</div>
                <p>Длительность: 60 минут</p>
                <a href="#contact" class="btn">Записаться на сеанс</a>
            </div>
        </section>
    </div>

    <footer>
        <div class="container">
            <p>Салон красоты «Элеганс»</p>
            <p>г. Москва, ул. Примерная, д. 123 | Тел.: +7 (495) 123-45-67</p>
        </div>
    </footer>
</body>
</html>
