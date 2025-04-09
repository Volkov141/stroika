<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Строительная компания</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Строительная компания "БетонСтрой"</h1>
        <nav>
            <ul>
                <li><a href="#about">О нас</a></li>
                <li><a href="#services">Услуги</a></li>
                <li><a href="#projects">Проекты</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>О нас</h2>
        <p>Наша компания предоставляет полный спектр строительных услуг: от проектирования до сдачи объектов "под ключ".</p>
    </section>

    <section id="services">
        <h2>Наши услуги</h2>
        <ul>
            <li>Строительство жилых домов</li>
            <li>Ремонт и отделка помещений</li>
            <li>Проектирование и архитектура</li>
            <li>Инженерные работы</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Наши проекты</h2>
        <p>Здесь можно разместить галерею выполненных работ.</p>
    </section>

    <section id="contact">
        <h2>Связаться с нами</h2>
        <form>
            <label for="name">Имя:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Сообщение:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Отправить</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Строительная компания "БетонСтрой"</p>
    </footer>
</body>
</html>
