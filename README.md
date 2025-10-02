<!DOCTYPE html><html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقعي المميز</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Cairo', sans-serif;
      background: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    header {
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://source.unsplash.com/1600x900/?nature,abstract') no-repeat center center/cover;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      animation: fadeInDown 2s ease;
    }
    header p {
      font-size: 1.2rem;
      margin: 20px 0;
      animation: fadeInUp 2s ease;
    }
    .btn {
      background: #ff5722;
      color: white;
      padding: 12px 25px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      font-size: 1rem;
      transition: 0.3s;
    }
    .btn:hover {
      background: #e64a19;
      transform: scale(1.05);
    }
    nav {
      background: #333;
      padding: 10px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: #ff5722;
    }
    section {
      padding: 50px 20px;
      text-align: center;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: 0.3s;
    }
    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    }
    footer {
      background: #222;
      color: #bbb;
      padding: 15px;
      text-align: center;
    }
    @keyframes fadeInDown {
      from {opacity: 0; transform: translateY(-30px);}
      to {opacity: 1; transform: translateY(0);}
    }
    @keyframes fadeInUp {
      from {opacity: 0; transform: translateY(30px);}
      to {opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body>
  <header>
    <h1>👋 أهلاً بك في موقعي المميز</h1>
    <p>موقع حديث بتصميم جميل ورسوم متحركة ✨</p>
    <button class="btn" onclick="scrollToSection('about')">استكشف أكثر</button>
  </header>  <nav>
    <a href="#home">الرئيسية</a>
    <a href="#about">عن الموقع</a>
    <a href="#services">الخدمات</a>
    <a href="#contact">تواصل</a>
  </nav>  <section id="about">
    <h2>ℹ️ عن الموقع</h2>
    <p>هذا الموقع مصمم ليكون تجربة مميزة بتصميم عصري وجذاب. مناسب للعرض على الجوال والكمبيوتر.</p>
  </section>  <section id="services">
    <h2>🚀 خدماتنا</h2>
    <div class="cards">
      <div class="card">
        <h3>🌐 تصميم مواقع</h3>
        <p>إنشاء مواقع احترافية متجاوبة وسريعة.</p>
      </div>
      <div class="card">
        <h3>📱 تطبيقات موبايل</h3>
        <p>تطوير تطبيقات أندرويد و iOS بواجهة سهلة.</p>
      </div>
      <div class="card">
        <h3>🎨 تصميم جرافيك</h3>
        <p>إبداع في تصميم الشعارات والبروشورات.</p>
      </div>
    </div>
  </section>  <section id="contact">
    <h2>📞 تواصل معنا</h2>
    <p>يمكنك إرسال رسالة على البريد: <a href="mailto:example@email.com">example@email.com</a></p>
  </section>  <footer>
    <p>© 2025 - موقعي المميز | جميع الحقوق محفوظة</p>
  </footer>  <script>
    function scrollToSection(id) {
      document.getElementById(id).scrollIntoView({behavior: 'smooth'});
    }
  </script></body>
</html>
