<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мұғалімнің Веб-Сайты</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Мұғалімнің Веб-Сайты</h1>
        <nav>
            <ul>
                <li><a href="#news">Жаңалықтар</a></li>
                <li><a href="#materials">Оқу Материалдары</a></li>
                <li><a href="#assignments">Тапсырмалар</a></li>
                <li><a href="#algorithms">Алгоритмдер</a></li> <!-- Алгоритмдер бөлімін қосу -->
                <li><a href="#forum">Форум</a></li>
                <li><a href="#feedback">Кері Байланыс</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="news">
            <h2>Сынып Жаңалықтары</h2>
            <p>Сайтқа қош келдіңіз! Жаңа сабақтар мен тапсырмалар туралы хабарландырулар осында жарияланады.</p>
        </section>

        <section id="materials">
            <h2>Оқу Материалдары</h2>
            <ul>
                <li><a href="#">Презентация: Тақырып 1</a></li>
                <li><a href="#">Бейне сабақ: Тақырып 2</a></li>
                <li><a href="#">Мәтіндік материал: Тақырып 3</a></li>
            </ul>
        </section>

        <section id="assignments">
            <h2>Тапсырмалар</h2>
            <ul>
                <li><a href="#">Тапсырма 1</a></li>
                <li><a href="#">Тапсырма 2</a></li>
            </ul>
        </section>

        <section id="algorithms"> <!-- Алгоритмдер бөлімінің мазмұны -->
            <h2>Алгоритмдер</h2>
            <p>Алгоритмдер дегеніміз – мәселені шешуге немесе тапсырманы орындауға арналған нақты нұсқаулар жиынтығы.</p>
            <h3>Алгоритмнің элементтері</h3>
            <ul>
                <li>Кіріс</li>
                <li>Шығыс</li>
                <li>Нұсқаулар (операциялар)</li>
                <li>Шартты операторлар</li>
            </ul>
            <h3>Тапсырмалар</h3>
            <ol>
                <li>Алгоритмнің мысалын жазыңыз.</li>
                <li>Алгоритмді блок-схема түрінде бейнелеңіз.</li>
                <li>Топтық жұмыс: алгоритмнің бір түрін зерттеңіз.</li>
            </ol>
        </section>

        <section id="forum">
            <h2>Форум</h2>
            <p>Сұрақтарыңыз бен пікірлеріңіз үшін осы жерге жазыңыз.</p>
        </section>

        <section id="feedback">
            <h2>Кері Байланыс</h2>
            <form>
                <label for="name">Атыңыз:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Электрондық пошта:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Хабарлама:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Жіберу</button>
            </form>
        </section>
    </main>

    <footer>
        <p>© 2024 Рахымберді Мейрамбек. Мұғалімнің Веб-Сайты. Барлық құқықтар қорғалған.</p>
        <p>Байланыс: <a href="mailto:example@example.com">example@example.com</a></p> <!-- Мысал электрондық пошта -->
    </footer>
</body>
</html>
