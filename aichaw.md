<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>منتجات عائشة - العناية بالبشرة</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            direction: rtl;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #ff7f50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 1.2em;
        }
        nav a:hover {
            background-color: #ff7f50;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px 0;
        }
        .intro {
            text-align: center;
            margin-bottom: 50px;
        }
        .intro h2 {
            font-size: 2.5em;
            color: #ff7f50;
        }
        .intro p {
            font-size: 1.2em;
            color: #555;
            line-height: 1.6;
        }
        .product-section {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
            margin-top: 30px;
        }
        .product-card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .product-card:hover {
            transform: scale(1.05);
        }
        .product-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }
        .product-card h3 {
            color: #333;
            font-size: 1.5em;
            margin: 15px 0;
        }
        .product-card p {
            color: #777;
            font-size: 1.1em;
            margin-bottom: 20px;
        }
        .product-card .price {
            color: #ff7f50;
            font-size: 1.5em;
            margin-bottom: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 50px;
        }
    </style>
</head>
<body>

<header>
    <h1>منتجات عائشة للعناية بالبشرة</h1>
</header>

<nav>
    <a href="#">الرئيسية</a>
    <a href="#">المنتجات</a>
    <a href="#">عن عائشة</a>
    <a href="#">اتصل بنا</a>
</nav>

<div class="container">
    <section class="intro">
        <h2>اهتم ببشرتك مع منتجات عائشة</h2>
        <p>منتجاتنا مصممة خصيصًا لتلبية احتياجات بشرتك، نقدم لك مجموعة متنوعة من مستحضرات العناية بالبشرة التي تحتوي على مكونات طبيعية وفعالة لتغذية بشرتك وتبقيها ناعمة وصحية.</p>
    </section>

    <section class="product-section">
        <div class="product-card">
            <img src="product1.jpg" alt="منتج 1">
            <h3>كريم الترطيب</h3>
            <p>كريم ترطيب للبشرة الجافة يحتوي على مكونات طبيعية تغذي البشرة بعمق.</p>
            <p class="price">30 ر.س</p>
        </div>

        <div class="product-card">
            <img src="product2.jpg" alt="منتج 2">
            <h3>غسول الوجه</h3>
            <p>غسول مخصص لتنظيف البشرة بعمق وإزالة الشوائب مع الحفاظ على التوازن الطبيعي للبشرة.</p>
            <p class="price">25 ر.س</p>
        </div>

        <div class="product-card">
            <img src="product3.jpg" alt="منتج 3">
            <h3>مصل فيتامين C</h3>
            <p>مصل غني بفيتامين C لتفتيح البشرة وتوحيد لونها.</p>
            <p class="price">50 ر.س</p>
        </div>
    </section>

    <section class="product-section">
        <div class="product-card">
            <img src="product4.jpg" alt="منتج 4">
            <h3>زيت اللوز</h3>
            <p>زيت اللوز الطبيعي لترطيب البشرة وتقليل ظهور الخطوط الدقيقة.</p>
            <p class="price">40 ر.س</p>
        </div>

        <div class="product-card">
            <img src="product5.jpg" alt="منتج 5">
            <h3>قناع الطين الأخضر</h3>
            <p>قناع من الطين الأخضر لتنقية البشرة وامتصاص الزيوت الزائدة.</p>
            <p class="price">35 ر.س</p>
        </div>

        <div class="product-card">
            <img src="product6.jpg" alt="منتج 6">
            <h3>كريم الليل</h3>
            <p>كريم مغذي للبشرة يعمل على إصلاح البشرة أثناء النوم وتجديد خلاياها.</p>
            <p class="price">45 ر.س</p>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 منتجات عائشة. جميع الحقوق محفوظة.</p>
</footer>

</body>
</html>
