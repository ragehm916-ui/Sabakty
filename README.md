
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>سباكتي | خدمات السباكة والصيانة</title>
  <meta name="description" content="سباكتي لخدمات السباكة والصيانة المنزلية. تواصل معنا عبر واتساب.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    :root {
      --navy: #071d3b;
      --blue: #0878d1;
      --light: #f3f8fc;
      --green: #20c76a;
      --white: #ffffff;
      --text: #24364b;
    }

    body {
      font-family: Tahoma, Arial, sans-serif;
      background: var(--white);
      color: var(--text);
      line-height: 1.8;
    }

    a {
      text-decoration: none;
    }

    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
    }

    header {
      background: var(--navy);
      color: white;
      padding: 16px 0;
    }

    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    .logo {
      font-size: 27px;
      font-weight: bold;
      color: white;
    }

    .logo span {
      color: #32aaff;
    }

    nav {
      display: flex;
      gap: 18px;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      font-size: 14px;
    }

    .hero {
      background: linear-gradient(120deg, #071d3b, #0a5594);
      color: white;
      padding: 75px 0;
      overflow: hidden;
    }

    .hero-content {
      display: grid;
      grid-template-columns: 1.1fr 0.9fr;
      align-items: center;
      gap: 35px;
    }

    .hero h1 {
      font-size: clamp(30px, 5vw, 48px);
      line-height: 1.5;
      margin-bottom: 15px;
    }

    .hero h1 span {
      color: #46c1ff;
    }

    .hero p {
      color: #e2efff;
      margin-bottom: 25px;
      font-size: 17px;
    }

    .hero img {
      width: 100%;
      height: 310px;
      object-fit: cover;
      border-radius: 22px;
      border: 4px solid #ffffff24;
    }

    .btn {
      display: inline-block;
      background: var(--green);
      color: #052d19;
      padding: 12px 22px;
      border-radius: 9px;
      font-weight: bold;
      transition: 0.2s;
    }

    .btn:hover {
      transform: translateY(-2px);
    }

    .section {
      padding: 65px 0;
    }

    .section-title {
      text-align: center;
      color: var(--navy);
      font-size: 30px;
      margin-bottom: 10px;
    }

    .section-desc {
      text-align: center;
      margin-bottom: 35px;
      color: #64748b;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .service {
      padding: 25px 20px;
      background: var(--light);
      border-radius: 15px;
      border: 1px solid #e1ebf5;
      transition: 0.2s;
    }

    .service:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px #071d3b12;
    }

    .service .icon {
      font-size: 38px;
      margin-bottom: 8px;
    }

    .service h3 {
      color: var(--navy);
      margin-bottom: 8px;
    }

    .about {
      background: var(--light);
    }

    .about-content {
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      gap: 35px;
    }

    .about img {
      width: 100%;
      height: 300px;
      object-fit: cover;
      border-radius: 18px;
    }

    .about h2 {
      font-size: 30px;
      color: var(--navy);
      margin-bottom: 15px;
    }

    .about p {
      margin-bottom: 20px;
    }

    .contact {
      text-align: center;
      background: var(--navy);
      color: white;
    }

    .contact h2 {
      font-size: 30px;
      margin-bottom: 12px;
    }

    .contact p {
      margin-bottom: 22px;
      color: #dceaff;
    }

    footer {
      background: #041329;
      color: #d1dbea;
      padding: 20px 0;
      text-align: center;
      font-size: 14px;
    }

    .floating-whatsapp {
      position: fixed;
      bottom: 20px;
      left: 18px;
      background: var(--green);
      color: #06361e;
      padding: 13px 17px;
      border-radius: 50px;
      font-weight: bold;
      box-shadow: 0 5px 18px #0003;
      z-index: 10;
    }

    @media (max-width: 750px) {
      .navbar {
        justify-content: center;
      }

      nav {
        justify-content: center;
      }

      .hero {
        padding: 45px 0;
      }

      .hero-content,
      .about-content {
        grid-template-columns: 1fr;
      }

      .hero img {
        height: 230px;
      }

      .services {
        grid-template-columns: 1fr;
      }

      .section {
        padding: 45px 0;
      }

      .about img {
        height: 230px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="container navbar">
      <a href="#home" class="logo">سباك<span>تي</span></a>

      <nav>
        <a href="#home">الرئيسية</a>
        <a href="#services">خدماتنا</a>
        <a href="#about">من نحن</a>
        <a href="#contact">تواصل معنا</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="container hero-content">
        <div>
          <h1>حلول السباكة<br><span>بكل سهولة واحترافية</span></h1>

          <p>
            سباكتي لخدمات السباكة والصيانة المنزلية.
            تواصل معنا واحكيلنا عن المشكلة اللي عندك.
          </p>

          <a class="btn"
             href="https://wa.me/201144216406"
             target="_blank"
             rel="noopener">
            تواصل معنا عبر واتساب
          </a>
        </div>

        <img
          src="https://images.unsplash.com/photo-1607472586893-edb57bdc0e39?auto=format&fit=crop&w=900&q=85"
          alt="أدوات ومستلزمات السباكة">
      </div>
    </section>

    <section class="section" id="services">
      <div class="container">
        <h2 class="section-title">خدماتنا</h2>
        <p class="section-desc">
          بنساعدك في أعمال السباكة والصيانة المنزلية
        </p>

        <div class="services">
          <article class="service">
            <div class="icon">🔧</div>
            <h3>إصلاح التسريبات</h3>
            <p>المساعدة في اكتشاف تسريبات المياه وإصلاح الأعطال.</p>
          </article>

          <article class="service">
            <div class="icon">🚿</div>
            <h3>تركيب الأدوات الصحية</h3>
            <p>تركيب وصيانة الخلاطات والأحواض والدش.</p>
          </article>

          <article class="service">
            <div class="icon">🛠️</div>
            <h3>صيانة السباكة</h3>
            <p>صيانة الأعطال المنزلية ومشكلات المواسير والصرف.</p>
          </article>

          <article class="service">
            <div class="icon">🚰</div>
            <h3>تركيب الحنفيات</h3>
            <p>تركيب الحنفيات وتغيير القطع التالفة عند الحاجة.</p>
          </article>

          <article class="service">
            <div class="icon">🏠</div>
            <h3>صيانة منزلية</h3>
            <p>حلول لأعمال السباكة المختلفة داخل المنزل.</p>
          </article>

          <article class="service">
            <div class="icon">💬</div>
            <h3>طلب الخدمة</h3>
            <p>ابعتلنا على واتساب واشرح المشكلة لبدء التواصل.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section about" id="about">
      <div class="container about-content">
        <div>
          <h2>ليه تختار سباكتي؟</h2>
          <p>
            هدفنا نسهّل عليك الوصول لخدمات السباكة والصيانة.
            تقدر تتواصل معانا مباشرة وتوضح نوع الخدمة المطلوبة.
          </p>
          <a class="btn"
             href="https://wa.me/201144216406"
             target="_blank"
             rel="noopener">
            اطلب خدمتك دلوقتي
          </a>
        </div>

        <img
          src="https://images.unsplash.com/photo-1621905251189-08b45d6a269e?auto=format&fit=crop&w=900&q=85"
          alt="أعمال صيانة منزلية">
      </div>
    </section>

    <section class="section contact" id="contact">
      <div class="container">
        <h2>محتاج سباك؟</h2>
        <p>تواصل مع سباكتي على واتساب للاستفسار عن الخدمة.</p>

        <a class="btn"
           href="https://wa.me/201144216406"
           target="_blank"
           rel="noopener">
          كلمنا على واتساب
        </a>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <p>© 2026  محمد راجح سباكتي محمد راجح — جميع الحقوق محفوظة<p>
    </div>
  </footer>

  <a class="floating-whatsapp"
     href="https://wa.me/201144216406"
     target="_blank"
     rel="noopener"
     aria-label="تواصل معنا على واتساب">
     واتساب
  </a>

</body>
</html>



