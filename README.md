<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Музыка в моей жизни | Татьяна Луковникова</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #f9f7fe;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 40px 0;
            background: linear-gradient(120deg, #a8c0ff, #3f2b96);
            color: white;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        section {
            background: white;
            padding: 25px;
            margin-bottom: 25px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        
        h2 {
            color: #3f2b96;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid #f0f0f0;
        }
        
        h3 {
            color: #5e4bbb;
            margin: 20px 0 10px;
        }
        
        p {
            margin-bottom: 15px;
        }
        
        ul {
            margin-left: 20px;
            margin-bottom: 15px;
        }
        
        li {
            margin-bottom: 8px;
        }
        
        .favorite-artists {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 15px;
        }
        
        .artist {
            background: #f0f7ff;
            padding: 15px;
            border-radius: 8px;
            flex: 1 1 200px;
            border-left: 4px solid #a8c0ff;
        }
        
        .artist-name {
            font-weight: bold;
            color: #3f2b96;
            margin-bottom: 5px;
        }
        
        .quote {
            background: #f0f7ff;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
            font-style: italic;
            text-align: center;
            border-left: 4px solid #a8c0ff;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 30px;
            color: #666;
            font-size: 0.9rem;
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 10px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            section {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Татьяна Луковникова</h1>
            <p class="subtitle">Моё музыкальное хобби</p>
        </header>
        
        <main>
            <section id="about">
                <h2>О моём увлечении музыкой</h2>
                <p>Музыка для меня - это способ выразить свои эмоции, отдохнуть после учёбы и просто получить удовольствие. Я не профессиональная певица, но очень люблю петь и слушать хорошую музыку.</p>
                
                <div class="quote">
                    "Музыка зажигает свет в душе, даже когда вокруг темно"
                </div>
                
                <p>С детства я занималась в музыкальной школе по классу фортепиано, и хотя сейчас учусь на другой специальности, музыка остаётся важной частью моей жизни.</p>
            </section>
            
            <section id="favorites">
                <h2>Мои любимые исполнители</h2>
                <p>У меня довольно разнообразный музыкальный вкус. Вот артисты, которых я слушаю чаще всего:</p>
                
                <div class="favorite-artists">
                    <div class="artist">
                        <div class="artist-name">Адель</div>
                        <p>Люблю её за сильный голос и искренние тексты песен. "Hello" - моя любимая композиция.</p>
                    </div>
                    
                    <div class="artist">
                        <div class="artist-name">Coldplay</div>
                        <p>Их музыка вдохновляет и поднимает настроение. "Fix You" - песня, которая всегда меня поддерживает.</p>
                    </div>
                    
                    <div class="artist">
                        <div class="artist-name">Лариса Долина</div>
                        <p>Восхищаюсь её вокальными данными и артистизмом. Мечтаю научиться петь так же powerfully.</p>
                    </div>
                </div>
            </section>
            
            <section id="vocal">
                <h2>Мои вокальные упражнения</h2>
                <p>Чтобы поддерживать голос в форме, я регулярно делаю простые упражнения:</p>
                
                <h3>Дыхательные упражнения</h3>
                <ul>
                    <li>Глубокий вдох и медленный выдох на звуке "с"</li>
                    <li>Дыхание животом - 4 секунды вдох, 4 секунды задержка, 6 секунд выдох</li>
                </ul>
                
                <h3>Распевки</h3>
                <ul>
                    <li>Пение гамм от низких нот к высоким и обратно</li>
                    <li>Упражнения на гласные звуки "а-о-у-и-э"</li>
                    <li>Простые песни для разогрева голоса</li>
                </ul>
                
                <p>Обычно я занимаюсь 15-20 минут в день, этого достаточно чтобы поддерживать голос в хорошей форме.</p>
            </section>
            
            <section id="inspiration">
                <h2>Что меня вдохновляет</h2>
                <p>Музыкальное вдохновение я нахожу в разных местах:</p>
                
                <h3>Фильмы и сериалы</h3>
                <p>Саундтреки к фильмам часто становятся источником новых музыкальных открытий.</p>
                
                <h3>Концерты и выступления</h3>
                <p>Люблю смотреть живые выступления любимых исполнителей на YouTube.</p>
                
                <h3>Прогулки на природе</h3>
                <p>Шум ветра, пение птиц и шелест листьев - это естественная музыка, которая успокаивает и вдохновляет.</p>
            </section>
        </main>
        
        <footer>
            <p>Сайт создан в рамках учебного проекта | 2025</p>
        </footer>
    </div>
</body>
</html>
