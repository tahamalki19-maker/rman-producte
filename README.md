<!doctype html>
<html lang="ar">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>شركة رمان أولاد عبدالله</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Changa:wght@300;400;700&display=swap" rel="stylesheet">
  <style>
    :root{--accent:#b1202b;--muted:#666}
    *{box-sizing:border-box}
    body{font-family:'Changa', sans-serif;margin:0;background:#fff;color:#111;line-height:1.4}
    header{background:linear-gradient(90deg,#fff 0%, #ffecec 100%);border-bottom:4px solid var(--accent)}
    .container{max-width:1100px;margin:0 auto;padding:20px}
    .brand{display:flex;align-items:center;gap:16px}
    .logo{width:72px;height:72px;border-radius:12px;background:var(--accent);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:20px}
    h1{margin:0;font-size:24px}
    p.lead{margin:6px 0 0;color:var(--muted)}

    .products{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:18px;margin-top:22px}
    .card{border:1px solid #eee;border-radius:10px;padding:12px;display:flex;flex-direction:column;background:#fff;box-shadow:0 6px 18px rgba(0,0,0,0.04)}
    .card img{width:100%;height:150px;object-fit:cover;border-radius:8px}
    .card h3{margin:10px 0 6px;font-size:18px}
    .price{color:var(--accent);font-weight:700}
    .desc{flex:1;color:#444;margin:8px 0}
    form{display:flex;flex-direction:column;gap:6px;margin-top:6px}
    input{padding:8px;border-radius:6px;border:1px solid #ccc;font-family:'Changa',sans-serif}
    button{padding:8px;border-radius:8px;border:none;background:var(--accent);color:#fff;font-weight:700;cursor:pointer}

    .row{display:grid;grid-template-columns:1fr 360px;gap:20px;margin-top:28px}
    .instagram{border:1px solid #eee;border-radius:10px;padding:12px}
    .instagram .placeholder{height:300px;display:flex;align-items:center;justify-content:center;background:#fafafa;border-radius:6px;color:#777}

    footer{margin-top:28px;padding:18px 0;border-top:1px solid #f0f0f0;color:var(--muted)}

    @media(max-width:880px){.row{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="brand">
        <div class="logo">رمان</div>
        <div>
          <h1>شركة رمان أولاد عبدالله</h1>
          <p class="lead">منتوجات طبيعية من الرمان — عصائر، مربى، زيت، ومنتوجات تقليدية.</p>
        </div>
      </div>
    </div>
  </header>

  <main class="container">
    <section>
      <h2>منتوجاتنا</h2>
      <p style="color:var(--muted);margin-top:6px">اختار المنتوج وعمّر المعلومات باش تتحول الطلبية مباشرة عبر واتساب.</p>

      <div class="products">

        <!-- بطاقة منتوج مع فورم -->
        <article class="card">
          <img src="https://via.placeholder.com/600x400?text=عصير+الرمان" alt="منتوج 1">
          <h3>عصير الرمان الطبيعي</h3>
          <div class="price">السعر: 25 درهم</div>
          <p class="desc">عصير طبيعي 100% من رمان أولاد عبدالله.</p>
          <form onsubmit="sendToWhatsApp(event)">
            <input type="hidden" name="product" value="عصير الرمان الطبيعي">
            <input type="text" id="name1" placeholder="الاسم الكامل" required>
            <input type="tel" id="phone1" placeholder="رقم الهاتف" required>
            <button type="submit">إرسال الطلب عبر واتساب</button>
          </form>
        </article>

        <article class="card">
          <img src="https://via.placeholder.com/600x400?text=مربى+الرمان" alt="منتوج 2">
          <h3>مربى الرمان</h3>
          <div class="price">السعر: 30 درهم</div>
          <p class="desc">مربى لذيذ مصنوع من أجود ثمار الرمان.</p>
          <form onsubmit="sendToWhatsApp(event)">
            <input type="hidden" name="product" value="مربى الرمان">
            <input type="text" id="name2" placeholder="الاسم الكامل" required>
            <input type="tel" id="phone2" placeholder="رقم الهاتف" required>
            <button type="submit">إرسال الطلب عبر واتساب</button>
          </form>
        </article>
        <article class="card">
          <img src="ber10P2.png" alt="منتوج 2">
          <h3>مربى الرمان</h3>
          <div class="price">السعر: 30 درهم</div>
          <p class="desc">مربى لذيذ مصنوع من أجود ثمار الرمان.</p>
          <form onsubmit="sendToWhatsApp(event)">
            <input type="hidden" name="product" value="مربى الرمان">
            <input type="text" id="name2" placeholder="الاسم الكامل" required>
            <input type="tel" id="phone2" placeholder="رقم الهاتف" required>
            <button type="submit">إرسال الطلب عبر واتساب</button>
          </form>
        </article>

      </div>
    </section>

    <section class="row">
      <div>
        <h2>حول الشركة</h2>
        <p style="color:var(--muted)">شركة عائلية من أولاد عبدالله متخصصة في تحويل منتوجات الرمان بطرق تقليدية وحديثة. نستخدم مكونات محلية ونهتم بالجودة.</p>
        <ul style="color:var(--muted);margin-top:8px">
          <li>المنتجات: عصير رمان، مربى، خل، زيت بذور الرمان</li>
          <li>التوصيل داخل المنطقة: متاح</li>
          <li>اتصل بنا: 0698322419</li>
        </ul>
      </div>

      <aside class="instagram">
        <h3>صفحتنا على إنستغرام</h3>
        <p style="color:var(--muted);margin-top:6px">رابط الصفحة: <code>@rman_ouladabdallah</code></p>
        <div class="placeholder">هنا يظهر إنستغرام (ضع رابط أو كود)</div>
      </aside>
    </section>

    <footer>
      <div class="container">
        <small>© 2025 شركة رمان أولاد عبدالله — كل الحقوق محفوظة</small>
      </div>
    </footer>
  </main>

  <script>
  function sendToWhatsApp(e) {
    e.preventDefault();
    let form = e.target;
    let name = form.querySelector('input[type=text]').value;
    let phone = form.querySelector('input[type=tel]').value;
    let product = form.querySelector('input[name=product]').value;
    let whatsappNumber = '212698322419';

    let message = `طلب جديد:%0A👤 الاسم: ${name}%0A📞 الهاتف: ${phone}%0A🧺 المنتج: ${product}`;
    let url = `https://wa.me/${whatsappNumber}?text=${message}`;

    window.open(url, '_blank');
  }
  </script>
</body>
</html>
