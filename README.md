<!doctype html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>MR. CRESTO — الموقع الرسمي</title>
<meta name="description" content="الهوية الرقمية الرسمية لـ MR. CRESTO: المشاريع والخدمات والأخبار وحسابات التواصل في مكان واحد.">
<meta property="og:title" content="MR. CRESTO">
<meta property="og:description" content="WELCOME TO MY WORLD">
<meta name="theme-color" content="#050505">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;900&family=Playfair+Display:wght@700;900&display=swap" rel="stylesheet">
<style>
:root{--gold:#d4af37;--g1:#f1cc4f;--g2:#8f6c16;--bg:#050505;--card:#111;--line:rgba(212,175,55,.18)}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:#e9e4d4;font-family:Cairo,system-ui,sans-serif;line-height:1.7;overflow-x:hidden}
body:before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(60rem 30rem at 50% -10%,rgba(212,175,55,.18),transparent 60%),radial-gradient(40rem 25rem at 100% 50%,rgba(212,175,55,.07),transparent 60%),radial-gradient(40rem 25rem at 0 90%,rgba(212,175,55,.06),transparent 60%)}
a{color:inherit;text-decoration:none}
.wrap{max-width:1100px;margin:auto;padding:0 18px}
.gold{background:linear-gradient(110deg,#8f6c16,#f1cc4f 25%,#fff3b0 50%,#f1cc4f 75%,#8f6c16);background-size:200% auto;-webkit-background-clip:text;background-clip:text;color:transparent;animation:shine 6s linear infinite}
@keyframes shine{to{background-position:-200% center}}
@keyframes up{from{opacity:0;transform:translateY(18px)}to{opacity:1;transform:none}}
@keyframes glow{50%{opacity:1}0%,100%{opacity:.5}}
.reveal{opacity:0;transform:translateY(18px);transition:.7s}
.reveal.in{opacity:1;transform:none}
/* header */
header{position:sticky;top:0;z-index:50;background:rgba(0,0,0,.75);backdrop-filter:blur(14px);border-bottom:1px solid var(--line)}
.bar{display:flex;align-items:center;justify-content:space-between;height:64px;gap:12px}
.logo{font-family:'Playfair Display',serif;font-weight:900;letter-spacing:.2em;font-size:20px}
nav{display:flex;gap:2px}
nav a{padding:6px 12px;border-radius:99px;font-size:14px;font-weight:600;color:#bbb;transition:.3s}
nav a:hover,nav a.on{color:var(--g1);background:rgba(212,175,55,.12)}
.tools{display:flex;gap:8px;align-items:center}
.pill{border:1px solid rgba(212,175,55,.35);background:none;color:#f8de80;border-radius:99px;padding:6px 14px;font:700 12px Cairo;cursor:pointer;transition:.3s}
.pill:hover{background:rgba(212,175,55,.12)}
#burger{display:none}
@media(max-width:900px){nav{display:none;position:absolute;top:64px;inset-inline:0;background:#000f;flex-wrap:wrap;padding:14px;border-bottom:1px solid var(--line)}nav.open{display:flex}#burger{display:block}}
/* hero */
.hero{text-align:center;padding:70px 0 40px}
.avatar{width:210px;height:210px;border-radius:50%;margin:auto;border:2px solid var(--g1);position:relative;box-shadow:0 0 60px rgba(212,175,55,.4);background:#111 center/cover;display:flex;align-items:center;justify-content:center;font:900 90px 'Playfair Display'}
.avatar:before{content:"";position:absolute;inset:-18px;border-radius:50%;background:rgba(212,175,55,.25);filter:blur(30px);z-index:-1;animation:glow 4s infinite}
.tag{margin-top:30px;letter-spacing:.5em;font-size:13px;font-weight:700;color:var(--g1)}
h1{font:900 clamp(40px,9vw,76px) 'Playfair Display',serif;letter-spacing:.12em;margin-top:8px}
.lead{max-width:640px;margin:18px auto 0;font-size:18px;color:#cfc9b8}
.socials{display:flex;flex-wrap:wrap;gap:12px;justify-content:center;margin-top:26px}
.soc{display:flex;align-items:center;gap:10px;padding:7px 18px 7px 8px;border-radius:99px;border:1px solid var(--line);background:var(--card);transition:.3s;text-align:start}
.soc:hover{transform:translateY(-4px);border-color:rgba(212,175,55,.6);box-shadow:0 0 30px rgba(212,175,55,.25)}
.soc i{width:40px;height:40px;border-radius:50%;display:flex;align-items:center;justify-content:center;color:#fff}
.soc i svg{width:20px;height:20px;fill:currentColor}
.soc b{display:block;font-size:14px;line-height:1.2}.soc small{color:#999;font-size:12px;direction:ltr;display:block}
.btn{display:inline-flex;align-items:center;gap:8px;border-radius:99px;padding:12px 26px;font:800 14px Cairo;cursor:pointer;border:0;transition:.3s}
.btn.g{background:linear-gradient(135deg,#f1cc4f,#d4af37 50%,#8f6c16);color:#000}
.btn.g:hover{box-shadow:0 0 40px rgba(212,175,55,.5);filter:brightness(1.1)}
.btn.o{border:1px solid rgba(212,175,55,.4);background:none;color:#f8de80}
.btn.o:hover{background:rgba(212,175,55,.1)}
.cta{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;margin-top:34px}
/* sections */
section{padding:60px 0}
h2{font:900 clamp(28px,5vw,40px) 'Playfair Display',Cairo,serif;text-align:center}
h2+.ln{width:90px;height:1px;margin:14px auto 34px;background:linear-gradient(90deg,transparent,var(--g1),transparent)}
.grid{display:grid;gap:20px;grid-template-columns:repeat(auto-fill,minmax(280px,1fr))}
.card{background:rgba(17,17,17,.85);border:1px solid var(--line);border-radius:18px;overflow:hidden;transition:.3s}
.card:hover{transform:translateY(-5px);border-color:rgba(212,175,55,.5);box-shadow:0 0 30px rgba(212,175,55,.2)}
.card .pad{padding:22px}
.card img{width:100%;aspect-ratio:16/9;object-fit:cover;display:block;background:#1a1a1a}
.card h3{color:#fff3c4;font-size:19px}.card p{color:#aaa;font-size:14px;margin-top:8px}.card time{font-size:12px;color:var(--g1)}
.ico{height:120px;display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,rgba(143,108,22,.35),transparent);font-size:46px}
.about{max-width:820px;margin:auto;padding:34px;white-space:pre-line;font-size:18px;line-height:2.1}
.empty{grid-column:1/-1;text-align:center;color:#888;padding:34px;border:1px dashed var(--line);border-radius:16px}
.tl{max-width:720px;margin:auto;border-inline-start:1px solid rgba(212,175,55,.3);padding-inline-start:30px;display:grid;gap:22px}
.tl .card{position:relative}.tl .card:before{content:"";position:absolute;inset-inline-start:-39px;top:24px;width:16px;height:16px;border-radius:50%;background:#000;border:2px solid var(--g1)}
.filters{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-bottom:22px}
.chip{background:none;border:1px solid var(--line);color:#aaa;border-radius:99px;padding:5px 16px;font:600 13px Cairo;cursor:pointer}
.chip.on{border-color:var(--g1);color:#f8de80;background:rgba(212,175,55,.12)}
.masonry{columns:3 220px;gap:14px}.masonry img{width:100%;border-radius:14px;margin-bottom:14px;cursor:zoom-in;border:1px solid var(--line);transition:.3s}.masonry img:hover{border-color:var(--g1)}
.lb{position:fixed;inset:0;background:#000f;z-index:200;display:none;align-items:center;justify-content:center;padding:18px}.lb.on{display:flex}.lb img{max-width:100%;max-height:88vh;border-radius:12px}
/* forms */
form{max-width:640px;margin:auto;padding:28px;display:grid;gap:16px}
label{font-size:12px;font-weight:700;color:#f1cc4f;display:block;margin-bottom:5px}
input,select,textarea{width:100%;background:#0a0a0a;border:1px solid rgba(212,175,55,.25);color:#fff7d6;border-radius:12px;padding:12px 14px;font:inherit;outline:0;transition:.3s}
input:focus,select:focus,textarea:focus{border-color:var(--g1);box-shadow:0 0 20px rgba(212,175,55,.25)}
.hint{font-size:12px;color:#888;text-align:center;margin-top:10px}
footer{border-top:1px solid var(--line);margin-top:40px;padding:34px 0;text-align:center;color:#888;font-size:13px}
footer .links{display:flex;gap:18px;justify-content:center;margin:12px 0;flex-wrap:wrap}
footer a:hover{color:var(--g1)}
.modal{position:fixed;inset:0;z-index:300;background:#000d;display:none;align-items:center;justify-content:center;padding:18px}.modal.on{display:flex}
.modal .box{max-width:620px;max-height:85vh;overflow:auto;background:#0c0c0c;border:1px solid var(--line);border-radius:18px;padding:28px}
.modal h3{color:#f1cc4f;margin:14px 0 4px}.modal p{color:#bbb}
#e404{display:none;text-align:center;padding:120px 0}#e404 b{font:900 120px 'Playfair Display'}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>

<header><div class="wrap bar">
  <a href="#home" class="logo gold">MR. CRESTO</a>
  <nav id="nav"></nav>
  <div class="tools">
    <button class="pill" id="lang">EN</button>
    <button class="pill" id="burger" aria-label="menu">☰</button>
  </div>
</div></header>

<main id="page">
<section class="hero" id="home"><div class="wrap">
  <div class="avatar" id="avatar"><span class="gold">C</span></div>
  <div class="tag" data-t="tagline"></div>
  <h1 class="gold">MR. CRESTO</h1>
  <p class="lead" data-t="bio"></p>
  <div class="socials" id="socials"></div>
  <div class="cta">
    <a class="btn g" href="#contact" data-t="contactBtn"></a>
    <a class="btn o" href="#about" data-t="moreBtn"></a>
  </div>
</div></section>

<section id="about"><div class="wrap">
  <h2 class="gold" data-t="about"></h2><div class="ln"></div>
  <div class="card about" id="aboutText"></div>
</div></section>

<section id="projects"><div class="wrap">
  <h2 class="gold" data-t="projects"></h2><div class="ln"></div>
  <div class="grid" id="projectsGrid"></div>
</div></section>

<section id="services"><div class="wrap">
  <h2 class="gold" data-t="services"></h2><div class="ln"></div>
  <div class="grid" id="servicesGrid"></div>
</div></section>

<section id="gallery"><div class="wrap">
  <h2 class="gold" data-t="gallery"></h2><div class="ln"></div>
  <div class="filters" id="galFilters"></div>
  <div class="masonry" id="galGrid"></div>
</div></section>

<section id="videos"><div class="wrap">
  <h2 class="gold" data-t="videos"></h2><div class="ln"></div>
  <div class="grid" id="videosGrid"></div>
</div></section>

<section id="news"><div class="wrap">
  <h2 class="gold" data-t="news"></h2><div class="ln"></div>
  <div class="grid" id="newsGrid"></div>
</div></section>

<section id="achievements"><div class="wrap">
  <h2 class="gold" data-t="achievements"></h2><div class="ln"></div>
  <div class="tl" id="achGrid"></div>
</div></section>

<section id="collaborate"><div class="wrap">
  <h2 class="gold" data-t="collab"></h2><div class="ln"></div>
  <p style="text-align:center;color:#999;margin:-20px auto 26px;max-width:560px" data-t="collabSub"></p>
  <form class="card" id="collabForm">
    <div><label data-t="type"></label><select name="type" id="ctype"></select></div>
    <div><label data-t="name"></label><input name="name" required maxlength="100"></div>
    <div><label data-t="phone"></label><input name="phone" dir="ltr" maxlength="40"></div>
    <div><label data-t="msg"></label><textarea name="msg" rows="4" required maxlength="1500"></textarea></div>
    <button class="btn g" data-t="sendWA"></button>
  </form>
  <p class="hint" data-t="waNote"></p>
</div></section>

<section id="testimonials"><div class="wrap">
  <h2 class="gold" data-t="testi"></h2><div class="ln"></div>
  <div class="grid" id="testiGrid"></div>
  <form class="card" id="testiForm" style="margin-top:26px">
    <div><label data-t="name"></label><input name="name" required maxlength="80"></div>
    <div><label data-t="rating"></label><select name="rate"><option>5</option><option>4</option><option>3</option><option>2</option><option>1</option></select></div>
    <div><label data-t="opinion"></label><textarea name="msg" rows="3" required maxlength="800"></textarea></div>
    <button class="btn g" data-t="sendWA"></button>
  </form>
  <p class="hint" data-t="testiNote"></p>
</div></section>

<section id="contact"><div class="wrap">
  <h2 class="gold" data-t="contact"></h2><div class="ln"></div>
  <div class="socials" id="socials2" style="margin-bottom:30px"></div>
  <form class="card" id="contactForm">
    <div><label data-t="name"></label><input name="name" required maxlength="100"></div>
    <div><label data-t="phone"></label><input name="phone" dir="ltr" maxlength="40"></div>
    <div><label data-t="msg"></label><textarea name="msg" rows="4" required maxlength="1500"></textarea></div>
    <button class="btn g" data-t="sendWA"></button>
  </form>
</div></section>
</main>

<div id="e404" class="wrap"><b class="gold">404</b><p data-t="nf"></p><br><a class="btn g" href="#home" data-t="back"></a></div>

<footer><div class="wrap">
  <div class="logo gold">MR. CRESTO</div>
  <div class="socials" id="socials3" style="margin:16px 0"></div>
  <div style="margin:14px 0"><button class="pill" id="share" data-t="share"></button> <button class="pill" id="copy" data-t="copy"></button></div>
  <div>👁 <b id="visits" style="color:#f1cc4f">0</b> <span data-t="visitsL"></span></div>
  <div class="links"><a href="#" id="pv" data-t="privacy"></a><a href="#" id="tm" data-t="terms"></a></div>
  <div>© <span id="yr"></span> MR. CRESTO</div>
</div></footer>

<div class="lb" id="lb"><img id="lbImg" alt=""></div>
<div class="modal" id="modal"><div class="box" id="modalBox"></div></div>

<script>
/* ============================================================
   ✏️ عدّل بياناتك من هنا فقط — كل محتوى الموقع في هذا الكائن
   ============================================================ */
const SITE = {
  whatsapp: "201110546134",
  avatar: "",            // رابط صورتك الشخصية (مثال: "me.jpg" أو رابط مباشر)
  cover: "",
  socials: [
    {p:"tiktok",    label:"TikTok",    handle:"@mr.crest0",    url:"https://www.tiktok.com/@mr.crest0"},
    {p:"whatsapp",  label:"WhatsApp",  handle:"+201110546134", url:"https://wa.me/201110546134"},
    {p:"facebook",  label:"Facebook",  handle:"",              url:"https://www.facebook.com/share/1E7kn8Mjyu/"},
    {p:"instagram", label:"Instagram", handle:"@crestoelhawy", url:"https://www.instagram.com/crestoelhawy/"},
    {p:"youtube",   label:"YouTube",   handle:"@WaraElHekay",  url:"https://www.youtube.com/@WaraElHekay"}
  ],
  /* أضف عناصرك هنا بنفس الشكل. القوائم الفارغة تظهر "قريباً". */
  projects: [
    // {title:"اسم المشروع", title_en:"Project name", desc:"وصف", desc_en:"Description", image:"https://...", date:"2026-10-01", url:"https://..."}
  ],
  gallery: [
    // {image:"https://...", title:"عنوان", category:"شخصية"}
  ],
  videos: [
    // {title:"عنوان", platform:"youtube", url:"https://www.youtube.com/watch?v=XXXXXXXXXXX", thumb:""}
  ],
  news: [
    // {title:"عنوان الخبر", content:"نص الخبر", image:"", date:"2026-10-31"}
  ],
  achievements: [
    // {title:"إنجاز", desc:"وصف", date:"2026-01-01"}
  ],
  testimonials: [
    // {name:"اسم", rating:5, text:"رأي معتمد"}
  ]
};

const SERVICES = [
  {i:"🌐",ar:"تصميم المواقع الإلكترونية",en:"Website Design",da:"مواقع عصرية بتصميم احترافي يعبّر عن هويتك.",de:"Modern, professional websites that express your identity."},
  {i:"💻",ar:"تطوير المواقع",en:"Web Development",da:"برمجة مواقع سريعة وآمنة وقابلة للتطوير.",de:"Fast, secure and scalable web development."},
  {i:"📱",ar:"تصميم التطبيقات",en:"App Design",da:"واجهات تطبيقات سهلة الاستخدام وجذابة.",de:"Easy-to-use, attractive app interfaces."},
  {i:"🎨",ar:"تصميم الجرافيك",en:"Graphic Design",da:"تصاميم إبداعية لكل احتياجاتك البصرية.",de:"Creative designs for all your visual needs."},
  {i:"✨",ar:"تصميم الشعارات والهويات التجارية",en:"Logo & Branding",da:"شعار وهوية متكاملة لعلامتك التجارية.",de:"A complete logo and identity for your brand."},
  {i:"📈",ar:"التسويق الرقمي",en:"Digital Marketing",da:"حملات تسويق تزيد من وصولك ومبيعاتك.",de:"Marketing campaigns that grow your reach and sales."},
  {i:"🛠️",ar:"الخدمات التقنية",en:"Technical Services",da:"حلول ودعم تقني لمشاريعك.",de:"Technical solutions and support for your projects."}
];

const ABOUT_AR = `أنا كريستو، المعروف باسم MR. CRESTO، شخص عنده شغف كبير بعالم التكنولوجيا والإنترنت، وبحب أتعلم وأكتشف كل يوم حاجة جديدة.

بدأت رحلتي بأفكار وطموحات كبيرة، وقررت إني أحوّل الأفكار دي لواقع ومشاريع حقيقية.

مهتم بتطوير المواقع والتطبيقات والبرمجة والتصميم وصناعة المحتوى والتسويق الرقمي.

عندي شغف بالمشاريع والأفكار الجديدة، وبسعى إني أبني اسم وعلامة تجارية مميزة باسم CRESTO.

طموحي إني أطور من نفسي باستمرار، وأكبر بمشاريعي، وأوصل لأهدافي خطوة بخطوة.

لسه الحكاية في أولها، والقادم أفضل بإذن الله.`;
const ABOUT_EN = `I'm Cresto, known as MR. CRESTO — someone with a big passion for technology and the internet, who loves learning something new every day.

My journey started with big ideas and ambitions, and I decided to turn them into real projects.

I'm interested in web and app development, programming, design, content creation and digital marketing.

I'm passionate about new projects and ideas, and I'm working to build a distinctive name and brand: CRESTO.

My goal is to keep developing myself, grow my projects, and reach my goals step by step.

The story is only just beginning — and the best is yet to come, God willing.`;

/* ============================ الترجمة ============================ */
const T = {
  ar:{tagline:"WELCOME TO MY WORLD",bio:"شغوف بعالم التكنولوجيا والإنترنت، وبحوّل الأفكار لمشاريع حقيقية.",contactBtn:"💬 تواصل معي",moreBtn:"اعرف المزيد عني",
    about:"من أنا",projects:"مشاريعي",services:"خدماتي",gallery:"معرض الصور",videos:"الفيديوهات",news:"آخر الأخبار",achievements:"الإنجازات",collab:"التعاون والإعلانات",
    collabSub:"للشركات والعملاء الراغبين في التعاون أو الإعلان أو تنفيذ مشروع.",testi:"آراء المتابعين",contact:"تواصل معي",
    type:"نوع الطلب",name:"الاسم",phone:"رقم الهاتف (اختياري)",msg:"الرسالة",rating:"التقييم",opinion:"رأيك",sendWA:"إرسال عبر واتساب",
    waNote:"سيفتح واتساب برسالتك جاهزة للإرسال.",testiNote:"تظهر الآراء بعد مراجعتها واعتمادها.",
    empty:"قريباً… سيتم إضافة المحتوى هنا.",view:"مشاهدة المشروع",watch:"مشاهدة الفيديو",req:"اطلب الخدمة",more:"اقرأ المزيد",all:"الكل",
    share:"مشاركة الموقع",copy:"نسخ الرابط",copied:"تم النسخ ✓",visitsL:"زيارة",privacy:"سياسة الخصوصية",terms:"شروط الاستخدام",nf:"الصفحة غير موجودة",back:"العودة للرئيسية",
    nav:{home:"الرئيسية",about:"من أنا",projects:"مشاريعي",services:"خدماتي",gallery:"الصور",videos:"الفيديوهات",news:"الأخبار",achievements:"الإنجازات",collaborate:"التعاون",testimonials:"الآراء",contact:"تواصل"},
    kinds:["طلب تعاون","طلب إعلان","طلب تصميم موقع","طلب تنفيذ مشروع"],
    privacyBody:[["ما الذي نجمعه؟","لا يحفظ هذا الموقع أي بيانات على خوادم. عند الإرسال تُفتح رسالة واتساب جاهزة وأنت من تقرر إرسالها."],["عداد الزيارات","يُحسب العدد داخل متصفحك فقط، دون كوكيز تتبّع."],["الروابط الخارجية","روابط تيك توك وفيسبوك وإنستجرام ويوتيوب تخضع لسياسات خصوصيتها."]],
    termsBody:[["المحتوى","جميع المحتويات ملك MR. CRESTO ولا يجوز نسخها دون إذن."],["الطلبات","إرسال طلب لا يُعد عقداً ملزماً؛ تُحدد التفاصيل والأسعار بالاتفاق المباشر."],["التعديلات","يحق لنا تعديل الشروط في أي وقت."]]},
  en:{tagline:"WELCOME TO MY WORLD",bio:"Passionate about technology and the internet, turning ideas into real projects.",contactBtn:"💬 Contact me",moreBtn:"More about me",
    about:"About Me",projects:"Projects",services:"Services",gallery:"Gallery",videos:"Videos",news:"Latest News",achievements:"Achievements",collab:"Collaboration & Ads",
    collabSub:"For companies and clients who want to collaborate, advertise or build a project.",testi:"Testimonials",contact:"Contact Me",
    type:"Request type",name:"Name",phone:"Phone (optional)",msg:"Message",rating:"Rating",opinion:"Your opinion",sendWA:"Send via WhatsApp",
    waNote:"WhatsApp will open with your message ready to send.",testiNote:"Opinions appear after review and approval.",
    empty:"Coming soon… content will be added here.",view:"View project",watch:"Watch video",req:"Request service",more:"Read more",all:"All",
    share:"Share site",copy:"Copy link",copied:"Copied ✓",visitsL:"visits",privacy:"Privacy Policy",terms:"Terms of Use",nf:"Page not found",back:"Back to home",
    nav:{home:"Home",about:"About",projects:"Projects",services:"Services",gallery:"Gallery",videos:"Videos",news:"News",achievements:"Achievements",collaborate:"Collaborate",testimonials:"Reviews",contact:"Contact"},
    kinds:["Collaboration request","Advertising request","Website design request","Project request"],
    privacyBody:[["What we collect","This site stores no data on servers. On submit, a ready WhatsApp message opens and you decide whether to send it."],["Visit counter","Counted inside your browser only, no tracking cookies."],["External links","TikTok, Facebook, Instagram and YouTube links follow their own privacy policies."]],
    termsBody:[["Content","All content belongs to MR. CRESTO and may not be copied without permission."],["Requests","Sending a request is not a binding contract; details and pricing are agreed directly."],["Changes","We may update these terms at any time."]]}
};

/* ============================ الأيقونات ============================ */
const ICON = {
  tiktok:['linear-gradient(135deg,#25f4ee,#000 45%,#fe2c55)','<path d="M19.6 6.7a4.8 4.8 0 0 1-3.8-4.2V2h-3.4v13.4a2.9 2.9 0 1 1-2-2.8V9.2a6.3 6.3 0 1 0 5.4 6.2V9a8.2 8.2 0 0 0 4.8 1.5V7.1a4.8 4.8 0 0 1-1-.4Z"/>'],
  whatsapp:['linear-gradient(135deg,#25d366,#128c7e)','<path d="M12 2a10 10 0 0 0-8.6 15L2 22l5.1-1.3A10 10 0 1 0 12 2Zm5.8 14.2c-.2.7-1.4 1.3-1.9 1.4-.5.1-1.1.1-1.8-.1a14 14 0 0 1-5.4-3.5c-1.6-1.7-2.4-3.2-2.5-3.9-.1-.7.3-1.4.7-1.8.3-.3.6-.4.8-.4h.6c.2 0 .4 0 .6.5l.8 1.9c.1.2.1.4 0 .6l-.4.6c-.2.2-.3.4-.1.7.4.7 1 1.3 1.6 1.8.7.6 1.4.9 1.7 1 .3.1.5.1.7-.1l.7-.9c.2-.2.4-.3.7-.2l1.9.9c.3.1.5.2.5.4.1.2.1.8-.1 1.4Z"/>'],
  facebook:['linear-gradient(135deg,#1877f2,#0b4fb3)','<path d="M13.5 21v-8h2.7l.4-3.2h-3.1V7.8c0-.9.3-1.5 1.6-1.5h1.7V3.4c-.3 0-1.3-.1-2.4-.1-2.4 0-4 1.5-4 4.1v2.4H7.7V13h2.7v8h3.1Z"/>'],
  instagram:['linear-gradient(135deg,#feda75,#fa7e1e 25%,#d62976 55%,#962fbf 80%,#4f5bd5)','<path d="M7.8 2h8.4A5.8 5.8 0 0 1 22 7.8v8.4a5.8 5.8 0 0 1-5.8 5.8H7.8A5.8 5.8 0 0 1 2 16.2V7.8A5.8 5.8 0 0 1 7.8 2Zm-.2 2A3.6 3.6 0 0 0 4 7.6v8.8A3.6 3.6 0 0 0 7.6 20h8.8a3.6 3.6 0 0 0 3.6-3.6V7.6A3.6 3.6 0 0 0 16.4 4H7.6Zm9.6 1.5a1.3 1.3 0 1 1 0 2.6 1.3 1.3 0 0 1 0-2.6ZM12 7a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 2a3 3 0 1 0 0 6 3 3 0 0 0 0-6Z"/>'],
  youtube:['linear-gradient(135deg,#f00,#b30000)','<path d="M21.6 7.2a2.5 2.5 0 0 0-1.8-1.8C18.2 5 12 5 12 5s-6.2 0-7.8.4A2.5 2.5 0 0 0 2.4 7.2C2 8.8 2 12 2 12s0 3.2.4 4.8a2.5 2.5 0 0 0 1.8 1.8C5.8 19 12 19 12 19s6.2 0 7.8-.4a2.5 2.5 0 0 0 1.8-1.8c.4-1.6.4-4.8.4-4.8s0-3.2-.4-4.8ZM10 15V9l5.2 3L10 15Z"/>']
};

/* ============================ المنطق ============================ */
const $=s=>document.querySelector(s), esc=s=>String(s??"").replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
const safeUrl=u=>/^(https?:\/\/|\.?\/?[\w\-./%]+$)/i.test(u||"")?u:"";
let lang=(()=>{try{return localStorage.getItem("lang")||"ar"}catch(e){return"ar"}})();
let galCat=null;
const fdate=d=>{try{return new Date(d).toLocaleDateString(lang==="ar"?"ar-EG":"en-US",{year:"numeric",month:"long",day:"numeric"})}catch(e){return""}};
const pick=(o,k)=>lang==="en"&&o[k+"_en"]?o[k+"_en"]:o[k]||"";

function socialHTML(){return SITE.socials.map(s=>{const ic=ICON[s.p]||ICON.whatsapp;return `<a class="soc" href="${esc(safeUrl(s.url))}" target="_blank" rel="noopener noreferrer"><i style="background:${ic[0]}"><svg viewBox="0 0 24 24">${ic[1]}</svg></i><span><b>${esc(s.label)}</b>${s.handle?`<small>${esc(s.handle)}</small>`:""}</span></a>`}).join("")}
const empty=t=>`<div class="empty">${t.empty}</div>`;
function ytId(u){const m=(u||"").match(/(?:youtu\.be\/|v=|embed\/|shorts\/)([\w-]{11})/);return m?m[1]:""}

function render(){
  const t=T[lang];
  document.documentElement.lang=lang;document.documentElement.dir=lang==="ar"?"rtl":"ltr";
  $("#lang").textContent=lang==="ar"?"EN":"عربي";
  document.querySelectorAll("[data-t]").forEach(e=>{const v=t[e.dataset.t];if(v!==undefined)e.textContent=v});
  $("#nav").innerHTML=Object.entries(t.nav).map(([k,v])=>`<a href="#${k}">${v}</a>`).join("");
  $("#nav a").classList.add("on");
  $("#aboutText").textContent=lang==="ar"?ABOUT_AR:ABOUT_EN;
  ["socials","socials2","socials3"].forEach(id=>$("#"+id).innerHTML=socialHTML());
  if(SITE.avatar){const a=$("#avatar");a.style.backgroundImage=`url("${safeUrl(SITE.avatar)}")`;a.innerHTML=""}
  if(SITE.cover)$("#home").style.background=`linear-gradient(#050505cc,#050505),url("${safeUrl(SITE.cover)}") center/cover`;

  $("#projectsGrid").innerHTML=SITE.projects.length?SITE.projects.map(p=>`<article class="card">${p.image?`<img loading="lazy" src="${esc(safeUrl(p.image))}" alt="">`:""}<div class="pad"><time>${p.date?fdate(p.date):""}</time><h3>${esc(pick(p,"title"))}</h3><p>${esc(pick(p,"desc"))}</p>${p.url?`<br><a class="btn g" target="_blank" rel="noopener noreferrer" href="${esc(safeUrl(p.url))}">${t.view}</a>`:""}</div></article>`).join(""):empty(t);

  $("#servicesGrid").innerHTML=SERVICES.map((s,i)=>`<article class="card"><div class="ico">${s.i}</div><div class="pad"><h3>${lang==="ar"?s.ar:s.en}</h3><p>${lang==="ar"?s.da:s.de}</p><br><a class="btn g" href="#collaborate" data-svc="${i}">${t.req}</a></div></article>`).join("");

  const cats=[...new Set(SITE.gallery.map(g=>g.category).filter(Boolean))];
  $("#galFilters").innerHTML=cats.length?[null,...cats].map(c=>`<button class="chip ${galCat===c?"on":""}" data-cat="${esc(c??"")}">${esc(c??t.all)}</button>`).join(""):"";
  const gl=SITE.gallery.filter(g=>!galCat||g.category===galCat);
  $("#galGrid").innerHTML=gl.length?gl.map(g=>`<img loading="lazy" src="${esc(safeUrl(g.image))}" alt="${esc(g.title||"")}" data-big="${esc(safeUrl(g.image))}">`).join(""):empty(t);

  $("#videosGrid").innerHTML=SITE.videos.length?SITE.videos.map(v=>{const id=v.platform==="youtube"?ytId(v.url):"";const th=v.thumb||(id?`https://i.ytimg.com/vi/${id}/hqdefault.jpg`:"");return `<article class="card">${th?`<img loading="lazy" src="${esc(safeUrl(th))}" alt="">`:`<div class="ico">▶</div>`}<div class="pad"><h3>${esc(v.title)}</h3><p>${v.platform==="tiktok"?"TikTok":"YouTube"}</p><br><a class="btn g" target="_blank" rel="noopener noreferrer" href="${esc(safeUrl(v.url))}">▶ ${t.watch}</a></div></article>`}).join(""):empty(t);

  $("#newsGrid").innerHTML=SITE.news.length?SITE.news.map((n,i)=>`<article class="card">${n.image?`<img loading="lazy" src="${esc(safeUrl(n.image))}" alt="">`:""}<div class="pad"><time>${fdate(n.date)}</time><h3>${esc(pick(n,"title"))}</h3><p>${esc(pick(n,"content")).slice(0,120)}…</p><br><a class="btn o" href="#" data-news="${i}">${t.more}</a></div></article>`).join(""):empty(t);

  $("#achGrid").innerHTML=SITE.achievements.length?SITE.achievements.map(a=>`<div class="card pad">${a.date?`<time>${fdate(a.date)}</time>`:""}<h3>${esc(pick(a,"title"))}</h3><p>${esc(pick(a,"desc"))}</p></div>`).join(""):empty(t);

  $("#testiGrid").innerHTML=SITE.testimonials.length?SITE.testimonials.map(x=>`<div class="card pad"><div style="color:#f1cc4f">${"★".repeat(x.rating||5)}</div><p style="color:#ddd">${esc(x.text)}</p><time>${esc(x.name)}</time></div>`).join(""):empty(t);

  const ct=$("#ctype");const cur=ct.selectedIndex>0?ct.selectedIndex:0;
  ct.innerHTML=t.kinds.map(k=>`<option>${k}</option>`).join("");ct.selectedIndex=cur;
  observe();
}

function observe(){const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add("in");io.unobserve(e.target)}}),{threshold:.08});
  document.querySelectorAll("section .card,h2,.soc").forEach(e=>{e.classList.add("reveal");io.observe(e)})}

function toWA(text){window.open(`https://wa.me/${SITE.whatsapp}?text=${encodeURIComponent(text)}`,"_blank","noopener")}
function modal(html){$("#modalBox").innerHTML=html+`<br><button class="btn g" onclick="document.getElementById('modal').classList.remove('on')">${lang==="ar"?"إغلاق":"Close"}</button>`;$("#modal").classList.add("on")}

/* أحداث */
$("#lang").onclick=()=>{lang=lang==="ar"?"en":"ar";try{localStorage.setItem("lang",lang)}catch(e){}render()};
$("#burger").onclick=()=>$("#nav").classList.toggle("open");
$("#nav").onclick=e=>{if(e.target.tagName==="A")$("#nav").classList.remove("open")};
document.addEventListener("click",e=>{
  const c=e.target.closest("[data-cat]");if(c){galCat=c.dataset.cat||null;render()}
  const b=e.target.closest("[data-big]");if(b){$("#lbImg").src=b.dataset.big;$("#lb").classList.add("on")}
  const s=e.target.closest("[data-svc]");if(s){const sv=SERVICES[s.dataset.svc];$("#collabForm [name=msg]").value=(lang==="ar"?"أرغب في طلب خدمة: ":"I'd like to request the service: ")+(lang==="ar"?sv.ar:sv.en)+"\n";$("#ctype").selectedIndex=3}
  const n=e.target.closest("[data-news]");if(n){e.preventDefault();const x=SITE.news[n.dataset.news];modal(`<h3>${esc(pick(x,"title"))}</h3><time style="color:#f1cc4f">${fdate(x.date)}</time><p style="white-space:pre-line;margin-top:10px">${esc(pick(x,"content"))}</p>`)}
});
$("#lb").onclick=()=>$("#lb").classList.remove("on");
$("#modal").onclick=e=>{if(e.target.id==="modal")$("#modal").classList.remove("on")};
document.addEventListener("keydown",e=>{if(e.key==="Escape"){$("#lb").classList.remove("on");$("#modal").classList.remove("on")}});
$("#pv").onclick=e=>{e.preventDefault();modal("<h2 class='gold' style='font-size:24px'>"+T[lang].privacy+"</h2>"+T[lang].privacyBody.map(([h,p])=>`<h3>${h}</h3><p>${p}</p>`).join(""))};
$("#tm").onclick=e=>{e.preventDefault();modal("<h2 class='gold' style='font-size:24px'>"+T[lang].terms+"</h2>"+T[lang].termsBody.map(([h,p])=>`<h3>${h}</h3><p>${p}</p>`).join(""))};

$("#collabForm").onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);toWA(`*${f.get("type")}*\n${T[lang].name}: ${f.get("name")}\n${f.get("phone")?T[lang].phone.replace(/ \(.*\)/,"")+": "+f.get("phone")+"\n":""}\n${f.get("msg")}`)};
$("#contactForm").onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);toWA(`${T[lang].name}: ${f.get("name")}\n${f.get("phone")?f.get("phone")+"\n":""}\n${f.get("msg")}`)};
$("#testiForm").onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);toWA(`⭐ ${f.get("rate")}/5\n${T[lang].name}: ${f.get("name")}\n\n${f.get("msg")}`)};

$("#share").onclick=async()=>{const u=location.href.split("#")[0];if(navigator.share){try{await navigator.share({title:"MR. CRESTO",url:u});return}catch(e){}}$("#copy").click()};
$("#copy").onclick=async()=>{const u=location.href.split("#")[0];try{await navigator.clipboard.writeText(u)}catch(e){const t=document.createElement("textarea");t.value=u;document.body.appendChild(t);t.select();document.execCommand("copy");t.remove()}const b=$("#copy"),o=b.textContent;b.textContent=T[lang].copied;setTimeout(()=>b.textContent=T[lang].copy,1800)};

/* عداد الزيارات (محلي داخل المتصفح) */
(function(){let n=0;try{n=+localStorage.getItem("visits")||0;if(!sessionStorage.getItem("seen")){n++;localStorage.setItem("visits",n);sessionStorage.setItem("seen","1")}}catch(e){}$("#visits").textContent=n.toLocaleString("en-US")})();
$("#yr").textContent=new Date().getFullYear();

/* صفحة 404 لأي رابط # غير معروف + تمييز القسم النشط */
const valid=["","home","about","projects","services","gallery","videos","news","achievements","collaborate","testimonials","contact"];
function route(){const h=location.hash.slice(1);const ok=valid.includes(h);$("#page").style.display=ok?"":"none";$("#e404").style.display=ok?"none":"block"}
addEventListener("hashchange",route);route();
addEventListener("scroll",()=>{let cur="home";document.querySelectorAll("main section[id]").forEach(s=>{if(s.getBoundingClientRect().top<150)cur=s.id});document.querySelectorAll("#nav a").forEach(a=>a.classList.toggle("on",a.getAttribute("href")==="#"+cur))},{passive:true});

render();
</script>
</body>
</html>
