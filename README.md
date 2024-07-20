<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Madam Pak - Temizlik Ürünleri</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            color: #333;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #00a859; /* Temizlik ürünleri için doğal yeşil renk */
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        header p {
            margin: 10px 0 0;
        }
        section {
            padding: 20px;
            margin: 10px auto;
            max-width: 1000px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #007a33; /* Ürünlerin temizliğini temsil eden koyu yeşil */
            border-bottom: 2px solid #00a859;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            margin-bottom: 20px;
        }
        .product img {
            max-width: 100px;
            margin-right: 20px;
        }
        .product-description {
            max-width: 800px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input, .contact-form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .footer {
            background-color: #00a859;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        a {
            color: #00a859;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>Madam Pak</h1>
    <p>Temizlik Ürünleri ve İpuçları</p>
</header>

<section id="home">
    <h2>Ana Sayfa</h2>
    <p>Temizlik ihtiyaçlarınızı karşılamak için buradayız! Kaliteli ve etkili temizlik ürünleri ile evinizi, ofisinizi veya iş yerinizi temiz ve hijyenik tutun.</p>
</section>

<section id="products">
    <h2>Ürünlerimiz</h2>
    <div class="product">
        <img src="temizlik-spreyi.jpg" alt="Temizlik Spreyi">
        <div class="product-description">
            <h3>Temizlik Spreyi</h3>
            <p>Güçlü temizleme formülü ile her yüzeyde etkili temizlik sağlar. Yüzey temizleyici, bakterileri yok eder ve parlatır.</p>
            <p><strong>Fiyat:</strong> 29.99 TL</p>
        </div>
    </div>
    <div class="product">
        <img src="temizlik-bezi.jpg" alt="Temizlik Bezi">
        <div class="product-description">
            <h3>Temizlik Bezi</h3>
            <p>Yüksek emiş gücüne sahip mikrofiber bez, tozları ve kirleri kolayca temizler. Uzun ömürlü ve dayanıklıdır.</p>
            <p><strong>Fiyat:</strong> 14.99 TL</p>
        </div>
    </div>
    <!-- Diğer ürünler burada listelenebilir -->
</section>

<section id="about">
    <h2>Hakkımızda</h2>
    <p>Madam Pak olarak amacımız, sizlere en kaliteli temizlik ürünlerini sunmak ve temizlik alanında en iyi hizmeti vermektir. Temizlik ürünlerimiz, güvenilir ve etkili formüller ile hazırlanmıştır. Sağlıklı bir yaşam için kaliteli temizlik çözümleri sunuyoruz.</p>
</section>

<section id="blog">
    <h2>Blog</h2>
    <p>Temizlik ipuçları, ürün incelemeleri ve daha fazlası için blog yazılarımızı takip edin.</p>
    <ul>
        <li><a href="#">Temizlik Spreylerinin Faydaları</a></li>
        <li><a href="#">Mikrofiber Bezler Nasıl Kullanılır?</a></li>
        <li><a href="#">Evde Temizlik Rutinleri</a></li>
    </ul>
</section>

<section id="contact">
    <h2>İletişim</h2>
    <p>Ürünlerimiz hakkında daha fazla bilgi almak veya sipariş vermek için bizimle iletişime geçebilirsiniz:</p>
    <form class="contact-form" action="#" method="post">
        <input type="text" name="name" placeholder="Adınız" required>
        <input type="email" name="email" placeholder="E-posta Adresiniz" required>
        <textarea name="message" rows="5" placeholder="Mesajınız" required></textarea>
        <input type="submit" value="Gönder">
    </form>
</section>

<section id="social-media">
    <h2>Sosyal Medya</h2>
    <p>Bizi sosyal medyada takip edin:</p>
    <p><a href="#">Twitter</a> | <a href="#">Instagram</a> | <a href="#">Facebook</a> | <a href="#">LinkedIn</a></p>
</section>

<div class="footer">
    <p>&copy; 2024 Madam Pak. Tüm Hakları Saklıdır.</p>
</div>

</body>
</html>
