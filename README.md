
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>M&G للنقل والتوريدات</title>

  <!-- خط جميل -->
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">

  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    html { scroll-behavior: smooth; }

    body {
      font-family: 'Cairo', sans-serif;
      background: #fff;
      color: #333;
      line-height: 1.6;
    }

    header {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      gap: 30px;
      font-size: 1.4rem;
      padding: 1rem;
      background-color: #f9f9f9;
    }

    header img {
      height: 5rem;
      width: 5rem;
      object-fit: contain;
    }

    header li {
      list-style: none;
    }

    header a {
      text-decoration: none;
      color: black;
      transition: color 0.3s ease;
    }

    header a:hover {
      color: darkgrey;
    }

    hr {
      opacity: 0.3;
      margin: 0;
    }

    .hero {
      background-color: darkslategray;
      color: white;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      padding: 2rem 1rem;
      text-align: right;
    }

    .heroimg {
      width: 90%;
      max-width: 350px;
      height: auto;
      border-radius: 2rem;
      object-fit: cover;
      margin: 1rem;
    }

    .herotext {
      max-width: 600px;
      padding: 1rem;
      font-size: 1.1rem;
    }

    .herotext ul {
      padding-right: 1rem;
      margin-top: 1rem;
    }

    .herotext li {
      margin-bottom: 0.5rem;
    }

    .section-title {
      text-align: center;
      font-size: 2rem;
      margin: 2rem 0 1rem;
      color: #222;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1.5rem;
      padding: 1rem 2rem 3rem;
    }

    .card {
      background-color: #fff;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-8px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card-content {
      padding: 1rem;
    }

    .card-content h3 {
      margin: 0;
      font-size: 1.2rem;
      color: #2e2e2e;
    }

    .card-content p {
      font-size: 1rem;
      margin: 0.5rem 0;
      color: #555;
    }

    .card-content a {
      display: inline-block;
      margin-top: 0.5rem;
      color: darkslategrey;
      font-weight: bold;
      text-decoration: none;
    }

    .card-content a:hover {
      color: #009688;
    }

    #contact {
      padding: 2rem;
      background-color: #f1f1f1;
      text-align: center;
    }

    #contact img {
      width: 50px;
      height: 50px;
      margin-bottom: 1rem;
    }

    #contact a {
      color: #25D366;
      text-decoration: none;
      font-weight: bold;
    }

    /* MEDIA QUERIES */
    @media (max-width: 768px) {
      header {
        flex-direction: column;
        gap: 1rem;
      }

      .herotext {
        font-size: 1rem;
        padding: 0.5rem;
      }

      .heroimg {
        width: 90%;
      }

      .section-title {
        font-size: 1.5rem;
      }

      .card-content h3 {
        font-size: 1.1rem;
      }

      .card-content p {
        font-size: 0.95rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="ChatGPT Image Jun 11, 2025, 03_07_22 PM.png" alt="شعار" />
    <li><a href="#products">منتجاتنا</a></li>
    <li><a href="#contact">اتصل بنا</a></li>
    <li><a href="#about">عن M&G</a></li>
  </header>

  <hr />

  <!-- التعريف -->
  <section class="hero" id="about">
    <img src="ChatGPT Image Jun 11, 2025, 08_48_48 PM.png" alt="منتجات مجمدة" class="heroimg">
    <div class="herotext">
      <p>
        مرحبًا بكم في الصفحة الرسمية لشركة <strong>M&G للنقل والتوريدات</strong>، خبراء التوريد والتوزيع في السوق المصري.
        نقدم لكم أفضل المنتجات المجمدة بجودة عالية ومعايير صحية مضمونة.
      </p>
      <ul>
        <li>🥭 مانجا مجمدة</li>
        <li>🍈 جوافة مجمدة</li>
        <li>🍓 فراولة مجمدة</li>
        <li>🥬 خضروات مجمدة متنوعة</li>
        <li>🍟 بطاطس صوابع مجمدة</li>
        <li>🥩 مجندات استربسات بجودة عالية</li>
      </ul>
      <p>📦 خدماتنا تشمل النقل والتوريد لكافة المحافظات بأعلى كفاءة.</p>
    </div>
  </section>

  <!-- المنتجات -->
  <section class="product-section" id="products">
    <h2 class="section-title">منتجاتنا</h2>
    <div class="product-grid">

      <div class="card">
        <img src="mangoes@550w.ef053743.avif" alt="مانجا">
        <div class="card-content">
          <h3>مانجا مجمدة</h3>
          <p>مذاق رائع وجودة ممتازة للعصائر والحلويات.</p>
          <a href="details.html">تفاصيل</a>
          
        </div>
      </div>

      <div class="card">
        <img src="guava@550w.2cd641d3.avif" alt="جوافة">
        <div class="card-content">
          <h3>جوافة مجمدة</h3>
          <p>طبيعية 100% ومفيدة جداً للصحة.</p>
          <a href="details.html">تفاصيل</a>
        </div>
      </div>

      <div class="card">
        <img src="f.jpg" alt="فراولة">
        <div class="card-content">
          <h3>فراولة مجمدة</h3>
          <p>جاهزة للعصير والتزيين والحلويات.</p>
          <a href="details.html">تفاصيل</a>
        </div>
      </div>

      <div class="card">
        <img src="https://cdn.pixabay.com/photo/2017/05/23/22/36/vegetables-2338824_1280.jpg" alt="خضروات">
        <div class="card-content">
          <h3>خضروات مجمدة</h3>
          <p>تشكيلة متنوعة من الخضروات الطازجة.</p>
          <a href="details.html">تفاصيل</a>
        </div>
      </div>

      <div class="card">
        <img src="b.webp" alt="بطاطس">
        <div class="card-content">
          <h3>بطاطس صوابع</h3>
          <p>بطاطس مجمدة جاهزة للقلي.</p>
          <a href="details.html">تفاصيل</a>
        </div>
      </div>

      <div class="card">
        <img src="s.webp" alt="استربسات">
        <div class="card-content">
          <h3>مجمدات و استربس</h3>
          <p>لحم مجمد عالي الجودة جاهز للطهي.</p>
          <a href="details.html">تفاصيل</a>
        </div>
      </div>

    </div>
  </section>

  <!-- التواصل -->
  <section id="contact">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="واتساب">
    <p>تواصل معنا على <strong style="color:#25D366;">واتساب</strong> مع <strong>الأستاذ إبراهيم محمد</strong></p>
    <p>📞 <a href="https://wa.me/201010872267">+201010872267</a></p>
  </section>

</body>
</html>

