# Empire.gg
file:///C:/Users/cih69/Desktop/index (1).html#
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EmpireLaw — سيرفر رول بلاي</title>
<link rel="icon" type="image/png" href="https://cdn.discordapp.com/icons/1289181393125113908/36ccb226d7c1a3f083b2abae2e2cee70.png?size=1024">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tabler-icons/2.47.0/tabler-icons.min.css">
<style>
  :root{
    --bg:#0a0e1a; --surface:#0e1424; --surface2:#070a12;
    --blue:#2f7fff; --blue-soft:rgba(47,127,255,0.15); --blue-line:rgba(47,127,255,0.3);
    --text:#e8eaf2; --muted:#94a0b8; --dim:#66708a;
    --line:rgba(255,255,255,0.08); --line2:rgba(255,255,255,0.07);
    --discord:#5865f2; --green:#3ddc84;
  }
  *{margin:0;padding:0;box-sizing:border-box}
  html{scroll-behavior:smooth}
  body{font-family:'Tajawal',sans-serif;background:var(--bg);color:var(--text);line-height:1.7;overflow-x:hidden}
  a{text-decoration:none;color:inherit}
  .wrap{max-width:1100px;margin:0 auto;padding:0 22px}
  .blue{color:var(--blue)}

  /* HEADER */
  header{position:sticky;top:0;z-index:50;background:rgba(14,20,36,0.92);backdrop-filter:blur(10px);border-bottom:0.5px solid var(--line)}
  .nav{max-width:1100px;margin:0 auto;padding:13px 22px;display:flex;align-items:center;justify-content:space-between;gap:10px;flex-wrap:wrap}
  .brand{display:flex;align-items:center;gap:11px}
  .brand img{width:40px;height:40px;border-radius:50%}
  .brand span{font-size:19px;font-weight:700;letter-spacing:.5px}
  .menu{display:flex;align-items:center;gap:18px;font-size:15px;color:#aeb8cc}
  .menu a{cursor:pointer;transition:color .15s}
  .menu a:hover{color:#fff}
  .btn-store{background:var(--blue);color:#fff;padding:9px 20px;border-radius:10px;font-weight:500;display:inline-flex;align-items:center;gap:7px;border:none;cursor:pointer;font-family:inherit;font-size:15px;transition:filter .15s}
  .btn-store:hover{filter:brightness(1.1)}

  /* HERO */
  .hero{text-align:center;padding:72px 22px 56px}
  .hero-logo{width:104px;height:104px;border-radius:50%;margin:0 auto 24px;display:block;box-shadow:0 0 0 2px var(--blue),0 0 36px rgba(47,127,255,.35)}
  .badge{display:inline-flex;align-items:center;gap:7px;background:var(--blue-soft);color:#9cc2ff;font-size:13px;padding:7px 17px;border-radius:20px;margin-bottom:20px}
  .badge i{font-size:9px;color:var(--green)}
  .hero h1{font-size:48px;font-weight:800;line-height:1.15;margin-bottom:16px}
  .hero p{font-size:17px;color:var(--muted);max-width:500px;margin:0 auto 30px}
  .hero-btns{display:flex;gap:12px;justify-content:center;flex-wrap:wrap}
  .btn{padding:13px 28px;border-radius:11px;font-weight:500;font-size:15px;display:inline-flex;align-items:center;gap:8px;cursor:pointer;border:none;font-family:inherit;transition:filter .15s,background .15s}
  .btn-discord{background:var(--discord);color:#fff}
  .btn-discord:hover{filter:brightness(1.1)}
  .btn-ghost{background:rgba(255,255,255,.08);color:#fff;border:0.5px solid rgba(255,255,255,.12)}
  .btn-ghost:hover{background:rgba(255,255,255,.14)}
  .btn-blue{background:var(--blue);color:#fff}
  .btn-blue:hover{filter:brightness(1.1)}

  /* STATS */
  .stats{display:grid;grid-template-columns:repeat(4,1fr);gap:1px;background:rgba(255,255,255,.06);border-radius:14px;overflow:hidden;margin:10px 0}
  .stat{background:var(--surface);padding:24px 10px;text-align:center}
  .stat b{display:block;font-size:28px;font-weight:700;color:var(--blue)}
  .stat span{font-size:13px;color:var(--dim)}

  /* SECTIONS */
  section{padding:56px 0 10px}
  .sec-head{text-align:center;margin-bottom:34px}
  .sec-head h2{font-size:28px;font-weight:700;margin-bottom:6px}
  .sec-head p{font-size:14px;color:var(--dim)}

  .grid{display:grid;gap:15px}
  .g3{grid-template-columns:repeat(3,1fr)}
  .feat{background:var(--surface);border:0.5px solid var(--line2);border-radius:13px;padding:22px;transition:border-color .15s,transform .15s}
  .feat:hover{border-color:var(--blue-line);transform:translateY(-3px)}
  .feat .ico{width:42px;height:42px;border-radius:11px;background:var(--blue-soft);display:flex;align-items:center;justify-content:center;color:var(--blue);font-size:23px;margin-bottom:13px}
  .feat h3{font-size:16px;font-weight:500;margin-bottom:6px}
  .feat p{font-size:13px;color:var(--dim);line-height:1.6}

  /* FOUNDERS */
  .founders{display:grid;grid-template-columns:repeat(4,1fr);gap:15px}
  .fc{background:var(--surface);border:0.5px solid var(--line2);border-radius:13px;padding:22px 14px;text-align:center;transition:border-color .15s,transform .15s}
  .fc:hover{border-color:var(--blue-line);transform:translateY(-3px)}
  .fc .av{width:72px;height:72px;border-radius:50%;background:var(--blue-soft);border:1.5px solid var(--blue);display:flex;align-items:center;justify-content:center;margin:0 auto 12px;font-size:25px;color:#9cc2ff;overflow:hidden}
  .fc .av img{width:100%;height:100%;object-fit:cover;border-radius:50%}
  .fc b{display:block;font-size:15px;font-weight:500}
  .fc span{font-size:12px;color:var(--blue);margin-top:3px;display:block}

  /* CTA */
  .cta{margin:48px 0;background:var(--surface);border:0.5px solid var(--blue-line);border-radius:16px;padding:38px 22px;text-align:center}
  .cta h2{font-size:24px;font-weight:700;margin-bottom:10px}
  .cta p{font-size:14px;color:var(--muted);margin-bottom:22px}

  /* FOOTER */
  footer{background:var(--surface2);border-top:0.5px solid var(--line);padding:28px 22px;text-align:center;margin-top:40px}
  .f-brand{display:flex;align-items:center;justify-content:center;gap:9px;margin-bottom:16px}
  .f-brand img{width:32px;height:32px;border-radius:50%}
  .f-brand span{font-size:16px;font-weight:700}
  .socials{display:flex;justify-content:center;gap:14px;margin-bottom:14px}
  .socials a{width:40px;height:40px;border:0.5px solid rgba(255,255,255,.1);border-radius:11px;display:flex;align-items:center;justify-content:center;color:var(--dim);font-size:21px;transition:color .15s,border-color .15s}
  .socials a:hover{color:#fff;border-color:var(--blue)}
  .copy{font-size:12px;color:#556}

  /* MODAL — STORE */
  .overlay{position:fixed;inset:0;z-index:100;background:rgba(4,7,14,.78);backdrop-filter:blur(6px);display:none;align-items:flex-start;justify-content:center;padding:40px 16px;overflow-y:auto}
  .overlay.open{display:flex}
  .modal{background:var(--bg);border:0.5px solid var(--blue-line);border-radius:18px;max-width:920px;width:100%;margin:auto;animation:pop .22s ease}
  @keyframes pop{from{opacity:0;transform:translateY(18px) scale(.98)}to{opacity:1;transform:none}}
  .modal-head{position:sticky;top:0;background:var(--bg);border-bottom:0.5px solid var(--line);padding:18px 24px;display:flex;align-items:center;justify-content:space-between;border-radius:18px 18px 0 0;z-index:2}
  .modal-head .t{display:flex;align-items:center;gap:11px}
  .modal-head .t i{width:36px;height:36px;border-radius:10px;background:var(--blue);color:#fff;display:flex;align-items:center;justify-content:center;font-size:20px}
  .modal-head h2{font-size:20px;font-weight:700}
  .x{width:38px;height:38px;border-radius:10px;border:0.5px solid var(--line);background:transparent;color:var(--muted);cursor:pointer;font-size:20px;display:flex;align-items:center;justify-content:center;transition:color .15s,border-color .15s}
  .x:hover{color:#fff;border-color:var(--blue)}
  .modal-body{padding:26px 24px 30px}
  .store-h{display:flex;align-items:center;gap:10px;margin:0 0 16px}
  .store-h:not(:first-child){margin-top:34px}
  .store-h .si{width:34px;height:34px;border-radius:9px;background:var(--blue);color:#fff;display:flex;align-items:center;justify-content:center;font-size:19px}
  .store-h h3{font-size:19px;font-weight:700}

  .prod{background:var(--surface);border:0.5px solid var(--line2);border-radius:13px;overflow:hidden;display:flex;flex-direction:column}
  .prod.feat-card{border-color:var(--blue-line)}
  .prod .img{height:122px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:6px}
  .prod .img.blue-bg{background:var(--blue-soft);color:var(--blue);font-size:46px}
  .prod .img.ph{background:rgba(255,255,255,.03);color:#556}
  .prod .img.ph i{font-size:34px}
  .prod .img.ph span{font-size:11px}
  .prod .body{padding:16px;flex:1;display:flex;flex-direction:column}
  .prod .body h4{font-size:16px;font-weight:500}
  .prod .body .desc{font-size:12px;color:var(--dim);margin:4px 0 14px;line-height:1.5;flex:1}
  .prod .row{display:flex;align-items:center;justify-content:space-between;margin-top:auto}
  .price{font-size:21px;font-weight:700;color:var(--blue)}
  .buy{background:var(--blue);color:#fff;font-size:13px;font-weight:500;padding:9px 18px;border-radius:9px;transition:filter .15s}
  .buy:hover{filter:brightness(1.12)}

  .rest{background:var(--surface);border:0.5px solid var(--line2);border-radius:13px;padding:18px;text-align:center;display:flex;flex-direction:column;align-items:center}
  .rest .ri{width:48px;height:48px;border-radius:12px;background:var(--blue-soft);color:var(--blue);display:flex;align-items:center;justify-content:center;font-size:24px;margin-bottom:12px}
  .rest b{font-size:15px;font-weight:500}
  .rest .rp{font-size:21px;font-weight:700;color:var(--blue);margin:8px 0}
  .rest .buy{display:block;width:100%;background:var(--blue-soft);color:#9cc2ff;padding:9px 0;border-radius:9px}
  .rest .buy:hover{background:rgba(47,127,255,.25);filter:none}

  @media(max-width:760px){
    .menu{gap:12px;font-size:14px}
    .menu .hide-sm{display:none}
    .hero h1{font-size:36px}
    .stats{grid-template-columns:repeat(2,1fr)}
    .g3{grid-template-columns:1fr}
    .founders{grid-template-columns:repeat(2,1fr)}
  }
  .sr{position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)}
</style>
</head>
<body>

<header>
  <nav class="nav">
    <div class="brand"><img src="https://cdn.discordapp.com/icons/1289181393125113908/36ccb226d7c1a3f083b2abae2e2cee70.png?size=1024" alt="EmpireLaw logo"><span>Empire<span class="blue">Law</span></span></div>
    <div class="menu">
      <a href="#home" class="hide-sm">الرئيسية</a>
      <a href="#features" class="hide-sm">المميزات</a>
      <a href="#creators" class="hide-sm">صنّاع المحتوى</a>
      <button class="btn-store" onclick="openStore()"><i class="ti ti-shopping-cart"></i> المتجر</button>
    </div>
  </nav>
</header>

<main id="home">
  <section class="hero" style="padding-top:72px">
    <img src="https://cdn.discordapp.com/icons/1289181393125113908/36ccb226d7c1a3f083b2abae2e2cee70.png?size=1024" alt="EmpireLaw" class="hero-logo">
    <div class="badge"><i class="ti ti-circle-filled"></i> السيرفر شغال الآن   </div>
    <h1>Empire<span class="blue">Law</span></h1>
    <p>أقوى تجربة رول بلاي عربية في GTA V — قصص، وظائف، عصابات، ومدينة كاملة تنتظرك</p>
    <div class="hero-btns">
      <a class="btn btn-discord" href="https://discord.gg/E-L" target="_blank"><i class="ti ti-brand-discord"></i> انضم للديسكورد</a>
      <button class="btn btn-ghost" onclick="openStore()"><i class="ti ti-shopping-cart"></i> تصفّح المتجر</button>
    </div>
  </section>

  <div class="wrap">
    <div class="stats">
      <div class="stat"><b>855</b><span>عضو</span></div>
      <div class="stat"><b>2022</b><span>سنة التأسيس</span></div>
      <div class="stat"><b>8</b><span>مؤسسين</span></div>
      <div class="stat"><b>24/7</b><span>دعم فني</span></div>
    </div>
  </div>

  <section id="features">
    <div class="wrap">
      <div class="sec-head"><h2>ليش EmpireLaw؟</h2><p>مميزات تخليك ما تقدر تطلع</p></div>
      <div class="grid g3">
        <div class="feat"><div class="ico"><i class="ti ti-briefcase"></i></div><h3>وظائف واقعية</h3><p>شرطة، إسعاف، ميكانيكي، وأكثر — اختر مسارك في المدينة</p></div>
        <div class="feat"><div class="ico"><i class="ti ti-home"></i></div><h3>بيوت ومحلات</h3><p>اشتري بيتك، افتح مشروعك، وكوّن إمبراطوريتك الخاصة</p></div>
        <div class="feat"><div class="ico"><i class="ti ti-users-group"></i></div><h3>عصابات ومافيا</h3><p>كوّن عصابتك، سيطر على المناطق، وعِش قصص الشوارع</p></div>
        <div class="feat"><div class="ico"><i class="ti ti-car"></i></div><h3>سيارات مخصصة</h3><p>أسطول واسع من السيارات والتعديلات الحصرية</p></div>
        <div class="feat"><div class="ico"><i class="ti ti-shield-check"></i></div><h3>إدارة محترفة</h3><p>طاقم إداري متواجد دايماً لحل المشاكل وضمان العدل</p></div>
        <div class="feat"><div class="ico"><i class="ti ti-bolt"></i></div><h3>أداء سلس</h3><p>سيرفر مستقر بدون لاق، تجربة لعب سلسة طوال الوقت</p></div>
      </div>
    </div>
  </section>

  <section id="founders">
    <div class="wrap">
      <div class="sec-head"><h2>المؤسسين</h2><p>الفريق اللي بنى EmpireLaw — 8 مؤسسين</p></div>
      <div class="founders">
        <!-- ===== كيف تضيف صورة لكل مؤسس =====
             ١. احفظ صورة المؤسس بنفس مجلد index.html (مثال: founder1.png)
             ٢. شيل سطر الأيقونة <i ...></i> اللي داخل <div class="av">
             ٣. حط بدله: <img src="founder1.png" alt="">
             مثال مطبّق على المؤسس ١ تحت (بدّل الرابط باسم صورتك) -->
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/guilds/1289181393125113908/users/330856295345422337/avatars/872b4e1c0b1b433e68532283b6c37d3e.png?size=4096" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-crown\u0022&gt;&lt;/i&gt;'"></div><b>ᴇʟ !  o ↫</b><span>Owner</span></div>
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/guilds/1289181393125113908/users/785087015782973522/avatars/68dd409db03f293b3e9ea0fe9ea4bb20.png?size=4096" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-star\u0022&gt;&lt;/i&gt;'"></div><b>ᴇʟ ! M</b><span> Owner,Founder</span></div>
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/avatars/585477083250032660/3776be067fa50bf4e56d4491a6137062.png?size=1024" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-star\u0022&gt;&lt;/i&gt;'"></div><b>ᴇʟ | HI</b><span>Owner,Founder</span></div>
                <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/avatars/1134225345290174554/90726cb96b0465493796de01f6507a85.png?size=1024" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-star\u0022&gt;&lt;/i&gt;'"></div><b>ᴇʟ ! i6dr</b><span>Founder</span></div>
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/guilds/1289181393125113908/users/1328023143436259418/avatars/5fd68d8a0a2a9cf1eefc398d8ade4567.png?size=4096" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-star\u0022&gt;&lt;/i&gt;'"></div><b></b>ᴇʟ | 3z<span>Founder</span></div>
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/avatars/742901177796001933/dc9efb4ea3b523a4ff64dec2a2c3e8fd.png?size=1024" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-star\u0022&gt;&lt;/i&gt;'"></div><b>ᴇʟ ! N S</b><span>Head Admin</span></div>
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/avatars/1381192127303778415/94933aaffbbbe244c2d761d5f60bd43c.png?size=1024" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-star\u0022&gt;&lt;/i&gt;'"></div><b>ᴇʟ ! iiOp-Faisal</b><span>Head Admin</span></div>
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/avatars/940761483019702372/4f827f11f0f40a60d5145c04a4f84e51.png?size=1024" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-star\u0022&gt;&lt;/i&gt;'"></div><b>ᴇʟ ! # Abu Shammar</b><span>Head Admin</span></div>
      </div>
    </div>
  </section>

  <section id="creators">
    <div class="wrap">
      <div class="sec-head"><h2>صنّاع المحتوى</h2><p>نجوم اللعب اللي يصنعون المحتوى في EmpireLaw</p></div>
      <div class="founders">
        <!-- نفس طريقة المؤسسين: حط صورة باسم creator1.png .. بنفس المجلد -->
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/attachments/1288476325224386722/1519598276326850600/channels4_profile.jpg?ex=6a3e23ad&is=6a3cd22d&hm=df5c2752a4b0b022ff14e8f2739eeb7e43822abb9296c71f1c87f197635ca575&" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-brand-twitch\u0022&gt;&lt;/i&gt;'"></div><b>ابو داحم</b><span>Streamer</span></div>
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/avatars/1139700032782749776/e0d8ffe09d304119ee0a3230356d37eb.png?size=1024" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-brand-youtube\u0022&gt;&lt;/i&gt;'"></div><b>! OS</b><span>Streamer</span></div>
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/attachments/1288476325224386722/1519597876622266409/image.png?ex=6a3e234e&is=6a3cd1ce&hm=cdbf0a0c4c78fe2d6206ea9ba3004a8096a67531d42e78caf0500748c8b9627f&" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-brand-tiktok\u0022&gt;&lt;/i&gt;'"></div><b>صانع محتوى ٣</b><span>Streamer</span></div>
        <div class="fc"><div class="av"><img src="https://cdn.discordapp.com/avatars/1134225345290174554/90726cb96b0465493796de01f6507a85.png?size=1024" alt="" onerror="this.outerHTML='&lt;i class=\u0022ti ti-brand-youtube\u0022&gt;&lt;/i&gt;'"></div><b></b>ᴇʟ ! i6dr<span>Streamer</span></div>
      </div>
    </div>
  </section>

  <div class="wrap">
    <div class="cta">
      <h2>جاهز تبدأ قصتك؟</h2>
      <p>انضم لـ 855 عضو في أقوى مدينة رول بلاي</p>
      <a class="btn btn-blue" href="https://discord.gg/E-L" target="_blank"><i class="ti ti-rocket"></i> ابدأ الآن مجاناً</a>
    </div>
  </div>
</main>

<footer>
  <div class="f-brand"><img src="https://cdn.discordapp.com/icons/1289181393125113908/36ccb226d7c1a3f083b2abae2e2cee70.png?size=1024" alt=""><span>Empire<span class="blue">Law</span></span></div>
  <div class="socials">
    <a href="https://discord.gg/E-L" target="_blank" aria-label="Discord"><i class="ti ti-brand-discord"></i></a>
    <a href="#" aria-label="YouTube"><i class="ti ti-brand-youtube"></i></a>
    <a href="#" aria-label="TikTok"><i class="ti ti-brand-tiktok"></i></a>
  </div>
  <p class="copy">© 2026 EmpireLaw — جميع الحقوق محفوظة</p>
</footer>

<!-- STORE MODAL -->
<div class="overlay" id="storeOverlay" onclick="if(event.target===this)closeStore()">
  <div class="modal" role="dialog" aria-modal="true" aria-label="متجر EmpireLaw">
    <div class="modal-head">
      <div class="t"><i class="ti ti-shopping-cart"></i><h2>متجر EmpireLaw</h2></div>
      <button class="x" onclick="closeStore()" aria-label="إغلاق"><i class="ti ti-x"></i></button>
    </div>
    <div class="modal-body">

      <div class="store-h"><div class="si"><i class="ti ti-crown"></i></div><h3>المزايا والسيارات</h3></div>
      <div class="grid g3">
        <div class="prod feat-card">
          <div class="img blue-bg"><i class="ti ti-star"></i></div>
          <div class="body"><h4>المزايا (VIP)</h4><div class="desc">صلاحيات ومميزات حصرية داخل السيرفر</div>
            <div class="row"><span class="price">$10</span><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div></div>
        </div>
        <div class="prod">
          <div class="img ph"><i class="ti ti-photo"></i><span>مكان صورة السيارة</span></div>
          <div class="body"><h4>سيارة فخمة ١</h4><div class="desc">سيارة خاصة وفخمة حصرية</div>
            <div class="row"><span class="price">$35</span><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div></div>
        </div>
        <div class="prod">
          <div class="img ph"><i class="ti ti-photo"></i><span>مكان صورة السيارة</span></div>
          <div class="body"><h4>سيارة فخمة ٢</h4><div class="desc">سيارة خاصة وفخمة حصرية</div>
            <div class="row"><span class="price">$45</span><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div></div>
        </div>
      </div>

      <div class="store-h"><div class="si"><i class="ti ti-tools-kitchen-2"></i></div><h3>المطاعم</h3></div>
      <div class="grid" style="grid-template-columns:repeat(4,1fr)">
        <div class="rest"><div class="ri"><i class="ti ti-burger"></i></div><b>مطعم ١</b><div class="rp">$20</div><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div>
        <div class="rest"><div class="ri"><i class="ti ti-pizza"></i></div><b>مطعم ٢</b><div class="rp">$40</div><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div>
        <div class="rest"><div class="ri"><i class="ti ti-coffee"></i></div><b>مطعم ٣</b><div class="rp">$15</div><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div>
        <div class="rest"><div class="ri"><i class="ti ti-soup"></i></div><b>مطعم ٤</b><div class="rp">$25</div><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div>
      </div>

      <div class="store-h"><div class="si"><i class="ti ti-building-community"></i></div><h3>العقارات</h3></div>
      <div class="grid g3">
        <div class="prod">
          <div class="img blue-bg"><i class="ti ti-home-2"></i></div>
          <div class="body"><h4>شقة سكنية</h4><div class="desc">سكن خاص داخل المدينة</div>
            <div class="row"><span class="price">$50</span><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div></div>
        </div>
        <div class="prod">
          <div class="img blue-bg"><i class="ti ti-building"></i></div>
          <div class="body"><h4>فيلا فاخرة</h4><div class="desc">منزل كبير بإطلالة مميزة</div>
            <div class="row"><span class="price">$90</span><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div></div>
        </div>
        <div class="prod">
          <div class="img blue-bg"><i class="ti ti-building-store"></i></div>
          <div class="body"><h4>محل تجاري</h4><div class="desc">عقار تجاري لمشروعك الخاص</div>
            <div class="row"><span class="price">$70</span><a class="buy" href="https://discord.gg/E-L" target="_blank">شراء</a></div></div>
        </div>
      </div>

    </div>
  </div>
</div>

<script>
  function openStore(){document.getElementById('storeOverlay').classList.add('open');document.body.style.overflow='hidden';}
  function closeStore(){document.getElementById('storeOverlay').classList.remove('open');document.body.style.overflow='';}
  document.addEventListener('keydown',function(e){if(e.key==='Escape')closeStore();});
</script>
</body>
</html>
