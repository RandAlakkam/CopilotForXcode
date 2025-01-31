<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بورتفوليو رند</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
</head>
<body>

    <header>
        <h1>بورتفوليو رند</h1>
    </header>

    <nav>
        <button onclick="showSection('portfolio')">📸 البورتفوليو</button>
        <button onclick="showSection('plans')">📐 المخططات</button>
        <button onclick="showSection('reviews')">💬 الآراء</button>
    </nav>

    <section id="portfolio" class="hidden">
        <h2>📸 أعمالي</h2>
        <div class="gallery">
            <img src="project1.jpg" alt="مشروع 1">
            <img src="project2.jpg" alt="مشروع 2">
            <img src="project3.jpg" alt="مشروع 3">
        </div>
    </section>

    <section id="plans" class="hidden">
        <h2>📐 المخططات الهندسية</h2>
        <div class="gallery">
            <img src="plan1.jpg" alt="مخطط 1">
            <img src="plan2.jpg" alt="مخطط 2">
            <img src="plan3.jpg" alt="مخطط 3">
        </div>
    </section>

    <section id="reviews" class="hidden">
        <h2>💬 آراء العملاء</h2>
        <div class="reviews">
            <p>✨ "عمل رائع جدًا، التصميم كان فوق التوقعات!" - سارة</p>
            <p>🌟 "احترافية ودقة في العمل، أنصح بالتعامل معها!" - محمد</p>
            <p>🔥 "إبداع لا يوصف، شكرًا لكِ رند!" - ليلى</p>
        </div>
    </section>

    <footer>
        <p>© 2025 جميع الحقوق محفوظة لرند</p>
    </footer>

</body>
</html>
