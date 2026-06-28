<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AUNG CHAN MIN - ACM & LUKE VLOG</title>
    <style>
        /* Global Reset & Base Styles */
        * { box-sizing: border-box; margin: 0; padding: 0; }
        html { scroll-behavior: smooth; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #0b111e; color: #f3f4f6; line-height: 1.6; }

        /* Navigation Bar */
        nav { background-color: rgba(17, 24, 39, 0.95); padding: 20px 8%; display: flex; justify-content: space-between; align-items: center; position: fixed; top: 0; width: 100%; z-index: 1000; border-bottom: 2px solid #2563eb; backdrop-filter: blur(10px); }
        .logo { font-size: 24px; font-weight: bold; color: #3b82f6; text-transform: uppercase; letter-spacing: 1.5px; }
        .nav-links { list-style: none; display: flex; gap: 25px; }
        .nav-links a { text-decoration: none; color: #9ca3af; font-weight: 500; font-size: 16px; transition: color 0.3s, border-bottom 0.3s; padding-bottom: 5px; }
        .nav-links a:hover { color: #3b82f6; border-bottom: 2px solid #3b82f6; }

        /* Hero / Header Section */
        header { background: radial-gradient(circle at center, #1e293b 0%, #0b111e 100%); text-align: center; padding: 180px 20px 120px; }
        header h1 { font-size: 52px; color: #ffffff; margin-bottom: 20px; font-weight: 800; text-shadow: 0 0 15px rgba(59, 130, 246, 0.6); }
        header p { font-size: 22px; color: #9ca3af; margin-bottom: 35px; max-width: 600px; margin-left: auto; margin-right: auto; }
        .btn-primary { display: inline-block; background-color: #2563eb; color: white; padding: 14px 40px; text-decoration: none; font-weight: bold; border-radius: 30px; transition: all 0.3s; box-shadow: 0 4px 20px rgba(37, 99, 235, 0.4); font-size: 18px; }
        .btn-primary:hover { background-color: #1d4ed8; transform: translateY(-3px); box-shadow: 0 6px 25px rgba(37, 99, 235, 0.6); }

        /* General Section Layout */
        section { padding: 100px 8% 60px; text-align: center; }
        section h2 { font-size: 36px; margin-bottom: 40px; color: #ffffff; position: relative; display: inline-block; }
        section h2::after { content: ''; display: block; width: 60px; height: 4px; background-color: #2563eb; margin: 12px auto 0; border-radius: 2px; }

        /* About Section */
        #about { background-color: #111827; }
        .about-text { max-width: 800px; margin: 0 auto; font-size: 18px; color: #d1d5db; line-height: 1.8; text-align: justify; }

        /* Videos Section (Grid) */
        .video-grid { display: flex; justify-content: center; gap: 30px; flex-wrap: wrap; margin-top: 20px; }
        .video-card { background-color: #1f2937; border-radius: 16px; overflow: hidden; width: 340px; text-align: left; border: 1px solid #374151; transition: all 0.3s; }
        .video-card:hover { transform: translateY(-8px); border-color: #3b82f6; box-shadow: 0 10px 20px rgba(0,0,0,0.3); }
        .thumbnail { background: linear-gradient(135deg, #1e293b 0%, #2563eb 100%); height: 190px; display: flex; align-items: center; justify-content: center; color: #ffffff; font-weight: bold; font-size: 18px; position: relative; }
        .thumbnail::before { content: '▶'; font-size: 40px; color: rgba(255,255,255,0.8); position: absolute; }
        .video-info { padding: 25px; }
        .video-info h3 { font-size: 20px; margin-bottom: 12px; color: #ffffff; font-weight: 600; }
        .video-info p { color: #9ca3af; font-size: 15px; }

        /* Contact Section */
        #contact { background-color: #111827; }
        .contact-info { max-width: 600px; margin: 0 auto; font-size: 18px; color: #d1d5db; }
        .contact-info p { margin: 15px 0; }
        .social-links { display: flex; justify-content: center; gap: 20px; margin-top: 25px; }
        .social-btn { background-color: #1f2937; color: #ffffff; padding: 10px 25px; text-decoration: none; border-radius: 8px; border: 1px solid #374151; transition: all 0.3s; }
        .social-btn:hover { background-color: #2563eb; border-color: #2563eb; }

        /* Footer */
        footer { background-color: #030712; text-align: center; padding: 35px; color: #6b7280; font-size: 15px; border-top: 1px solid #1f2937; }
    </style>
</head>
<body>

    <nav>
        <div class="logo">ACM & LUKE</div>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#videos">Videos</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header id="home">
        <h1>ACM&LUKE VLOGမှ ကြိုဆိုပါတယ်</h1>
        <p>Welcome to Our Official Website. ကျွန်တော်တို့ရဲ့ စိတ်လှုပ်ရှားစရာ ဗီဒီယိုတွေနဲ့ ခရီးသွား Vlog များကို ဤနေရာတွင် တစ်စုတစ်စည်းတည်း ကြည့်ရှုနိုင်ပါသည်။</p>
        <a href="#videos" class="btn-primary">Watch Vlogs</a>
    </header>

    <section id="about">
        <h2>ကျွန်ုပ်တို့အကြောင်း (About Us)</h2>
        <div class="about-text">
            <p>မင်္ဂလာပါဗျာ။ ACM & LUKE VLOG စာမျက်နှာမှ ကြိုဆိုပါတယ်။ ကျွန်တော်တို့ကတော့ ပရိသတ်တွေအတွက် ပျော်ရွှင်စရာ ခရီးသွားဗီဒီယိုများ၊ စိန်ခေါ်မှု (Challenges) အစီအစဉ်များနှင့် စိတ်ဝင်စားဖွယ် နေ့စဉ်ဘဝ Vlog များကို အမြဲတမ်း တင်ဆက်ပေးနေတဲ့ Content Creator များ ဖြစ်ကြပါတယ်။ ရှေ့ဆက်ပြီးတော့လည်း ပိုမိုကောင်းမွန်တဲ့ အစီအစဉ်ကောင်းတွေကို ကြိုးစားတင်ဆက်သွားမှာ ဖြစ်လို့ အမြဲစောင့်မျှော်အားပေးကြပါဦးခင်ဗျာ။</p>
        </div>
    </section>

    <section id="videos">
        <h2>လတ်တလော ဗီဒီယိုများ (Latest Vlogs)</h2>
        <div class="video-grid">
            
            <div class="video-card">
                <div class="thumbnail"></div>
                <div class="video-info">
                    <h3>ပထမဆုံး Vlog ခရီးစဉ်</h3>
                    <p>ကျွန်တော်တို့ အဖွဲ့သားတွေရဲ့ စိတ်လှုပ်ရှားစရာ ကမ္ဘာလှည့်ခရီးစဉ် စတင်ခြင်းအကြောင်း...</p>
                </div>
            </div>

            <div class="video-card">
                <div class="thumbnail"></div>
                <div class="video-info">
                    <h3>Street Food Challenge</h3>
                    <p>မြို့အနှံ့က အကောင်းဆုံးနဲ့ အရသာအရှိဆုံး အစားအစာများကို လိုက်လံမြည်းစမ်းခြင်း...</p>
                </div>
            </div>

            <div class="video-card">
                <div class="thumbnail"></div>
                <div class="video-info">
                    <h3>Special Travel Vlog</h3>
                    <p>သဘာဝအလှတရားတွေနဲ့ ပြည့်နှက်နေတဲ့ တောင်ပေါ်ဒေသအလှအပ ခရီးစဉ်...</p>
                </div>
            </div>

        </div>
    </section>

    <section id="contact">
        <h2>ဆက်သွယ်ရန် (Contact Us)</h2>
        <div class="contact-info">
            <p>💡 လုပ်ငန်းကြော်ငြာများနှင့် Space ပံ့ပိုးကူညီမှုများအတွက် အောက်ပါ Social မီဒီယာများမှတစ်ဆင့် တိုက်ရိုက်ဆက်သွယ်နိုင်ပါတယ်ခင်ဗျာ။</p>
            <div class="social-links">
                <a href="#" class="social-btn">YouTube</a>
                <a href="#" class="social-btn">Facebook</a>
                <a href="#" class="social-btn">Email</a>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 ACM & LUKE. All Rights Reserved. Designed for Aung Chan Min.</p>
    </footer>

</body>
</html>
