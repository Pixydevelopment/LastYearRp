<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قوانين FiveM | السيرفر الرسمي</title>
    <style>
        :root {
            --main-color: #2c3e50;
            --secondary-color: #e74c3c;
            --accent-color: #f35912;
            --light-color: #ecf0f1;
            --dark-color: #1a252f;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Tajawal', sans-serif;
        }
        
        body {
            background-color: var(--dark-color);
            color: var(--light-color);
            background-image: url('https://media.discordapp.net/attachments/1200079938842279937/1387276828355334155/PLAYER-LIST.gif?ex=685cc1ba&is=685b703a&hm=f5234b5cc4ed6e2b14d8374ba73715da3bb29aa5afaaf45b797a5172e1da093d&=&width=1113&height=579');
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
        }
        
        .overlay {
            background-color: rgba(0, 0, 0, 0.85);
            min-height: 100vh;
            width: 100%;
        }
        
        header {
            padding: 20px 0;
            border-bottom: 2px solid var(--accent-color);
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .logo {
            text-align: center;
            margin-bottom: 20px;
        }
        
        .logo img {
            max-width: 150px;
            border-radius: 50%;
            border: 3px solid var(--accent-color);
            box-shadow: 0 0 20px rgba(243, 138, 18, 0.5);
        }
        
        .logo h1 {
            font-size: 2.5rem;
            margin-top: 10px;
            color: var(--accent-color);
            text-shadow: 0 0 10px rgba(243, 156, 18, 0.7);
        }
        
        .welcome-section {
            text-align: center;
            padding: 50px 0;
            animation: fadeIn 1.5s ease-in-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .welcome-section h2 {
            font-size: 2.2rem;
            margin-bottom: 20px;
            color: var(--accent-color);
        }
        
        .welcome-section p {
            font-size: 1.2rem;
            line-height: 1.8;
            margin-bottom: 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 30px;
            background-color: var(--secondary-color);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            font-size: 1.1rem;
            margin: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .btn:hover {
            background-color: #c0392b;
            transform: translateY(-3px);
            box-shadow: 0 6px 8px rgba(0, 0, 0, 0.15);
        }
        
        .btn-accent {
            background-color: var(--accent-color);
        }
        
        .btn-accent:hover {
            background-color: #e67e22;
        }
        
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin: 50px 0;
        }
        
        .feature-card {
            background-color: rgba(26, 37, 47, 0.8);
            border-radius: 10px;
            padding: 25px;
            width: 300px;
            text-align: center;
            border: 1px solid var(--main-color);
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.3);
            border-color: var(--accent-color);
        }
        
        .feature-icon {
            font-size: 2.5rem;
            color: var(--accent-color);
            margin-bottom: 15px;
        }
        
        .feature-card h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--accent-color);
        }
        
        footer {
            text-align: center;
            padding: 20px 0;
            border-top: 1px solid var(--main-color);
            margin-top: 50px;
        }
        
        .countdown {
            font-size: 1.5rem;
            margin: 30px 0;
            color: var(--accent-color);
        }
        
        /* تأثيرات خاصة */
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            pointer-events: none;
        }
        
        @media (max-width: 768px) {
            .logo h1 {
                font-size: 2rem;
            }
            
            .welcome-section h2 {
                font-size: 1.8rem;
            }
            
            .features {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <div class="overlay">
        <div class="particles" id="particles-js"></div>
        
        <header>
            <div class="container">
                <div class="logo">
                    <img src="https://media.discordapp.net/attachments/784916891822194729/1387236209054580786/logo-anmititon-66.gif?ex=685c9be5&is=685b4a65&hm=a632382907b3996eff88b4eaf28a8269753977411eb3b4415c3208410f904efb&=" alt="شعار السيرفر">
                    <h1>قوانين السيرفر الرسميا</h1>
                </div>
            </div>
        </header>
        
        <main>
            <section class="welcome-section">
                <div class="container">
                    <h2>مرحبا بكم في قوانين سيرفر لاست يير</h2>
                    <p>نقدم لكم تجربة لعب فريدة وممتعة مع أفضل القوانين والأنظمة التي تضمن العدل والمرح للجميع. اقرأ القوانين بعناية قبل الانضمام إلينا.</p>
                    
                    <div class="countdown" id="serverRestart">
                        <i class="fas fa-clock"></i> الوقت المتبقي لإعادة تشغيل السيرفر: <span id="countdown">00:00:00</span>
                    </div>
                    
                    <a href="laws.html" class="btn btn-accent">عرض القوانين</a>
                    <a href="#features" class="btn">المميزات السيرفر</a>
                </div>
            </section>
            
            <section id="features" class="features-section">
                <div class="container">
                    <h2 style="text-align: center; margin-bottom: 40px; font-size: 2rem; color: var(--accent-color);">المميزات السيرفر</h2>
                    
                    <div class="features">
                        <div class="feature-card">
                            <div class="feature-icon">
                                <i class="fas fa-shield-alt"></i>
                            </div>
                            <h3>حماية متقدمة</h3>
                            <p>نظام حماية متكامل ضد الغش والتخريب لضمان تجربة لعب عادلة للجميع</p>
                        </div>
                        
                        <div class="feature-card">
                            <div class="feature-icon">
                                <i class="fas fa-car"></i>
                            </div>
                            <h3>مركبات حصرية</h3>
                            <p>أكثر من 50 مركبة حصرية لا توجد في أي سيرفر آخر مع تفاصيل دقيقة</p>
                        </div>
                        
                        <div class="feature-card">
                            <div class="feature-icon">
                                <i class="fas fa-home"></i>
                            </div>
                            <h3>منازل متطورة</h3>
                            <p>نظام منازل متكامل مع تفاعلات حصرية وخصائص غير موجودة في الخوادم الأخرى</p>
                        </div>
                        
                        <div class="feature-card">
                            <div class="feature-icon">
                                <i class="fas fa-user-secret"></i>
                            </div>
                            <h3>أدوار فريدة</h3>
                            <p>أكثر من 30 دوراً فريداً مع مهام وخصائص خاصة بكل دور</p>
                        </div>
                        
                        <div class="feature-card">
                            <div class="feature-icon">
                                <i class="fas fa-robot"></i>
                            </div>
                            <h3>بوتات ذكية</h3>
                            <p>بوتات مساعدة ذكية لتسهيل تجربة اللعب والإجابة على استفساراتك</p>
                        </div>
                        
                        <div class="feature-card">
                            <div class="feature-icon">
                                <i class="fas fa-trophy"></i>
                            </div>
                            <h3>أحداث دورية</h3>
                            <p>مسابقات وأحداث حصرية مع جوائز قيمة كل أسبوع</p>
                        </div>
                    </div>
                </div>
            </section>
        </main>
        
        <footer>
            <div class="container">
                <p> جميع الحقوق محفوضه لدى لاست يير &copy; قوانين سيرفر لاست يير</p>
                <p>تم التصميم بشكل حصري لسيرفرنا فقط</p>
            </div>
        </footer>
    </div>
    
    <script>
        // عد تنازلي لإعادة تشغيل السيرفر (كل 12 ساعة)
        function updateCountdown() {
            const now = new Date();
            const hours = now.getHours();
            const minutes = now.getMinutes();
            const seconds = now.getSeconds();
            
            // احسب الوقت المتبقي لإعادة التشغيل القادمة (كل 12 ساعة)
            const nextRestart = new Date(now);
            if (hours < 12) {
                nextRestart.setHours(12, 0, 0, 0);
            } else {
                nextRestart.setHours(24, 0, 0, 0);
            }
            
            const diff = nextRestart - now;
            
            const h = Math.floor(diff / (1000 * 60 * 60));
            const m = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
            const s = Math.floor((diff % (1000 * 60)) / 1000);
            
            document.getElementById('countdown').textContent = 
                `${h.toString().padStart(2, '0')}:${m.toString().padStart(2, '0')}:${s.toString().padStart(2, '0')}`;
        }
        
        setInterval(updateCountdown, 1000);
        updateCountdown();
        
        // تأثير الجسيمات البسيط
        document.addEventListener('DOMContentLoaded', function() {
            const particles = document.getElementById('particles-js');
            const particleCount = 50;
            
            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.style.position = 'absolute';
                particle.style.width = Math.random() * 3 + 1 + 'px';
                particle.style.height = particle.style.width;
                particle.style.backgroundColor = `rgba(243, 156, 18, ${Math.random() * 0.5 + 0.1})`;
                particle.style.borderRadius = '50%';
                particle.style.top = Math.random() * 100 + '%';
                particle.style.left = Math.random() * 100 + '%';
                particle.style.opacity = Math.random() * 0.5 + 0.1;
                
                const duration = Math.random() * 20 + 10;
                const delay = Math.random() * 5;
                const xMove = (Math.random() - 0.5) * 100;
                const yMove = (Math.random() - 0.5) * 100;
                
                particle.style.animation = `float ${duration}s ease-in-out ${delay}s infinite alternate`;
                particle.style.setProperty('--x-move', `${xMove}px`);
                particle.style.setProperty('--y-move', `${yMove}px`);
                
                particles.appendChild(particle);
            }
            
            // إضافة أنيميشن للجسيمات
            const style = document.createElement('style');
            style.textContent = `
                @keyframes float {
                    0% {
                        transform: translate(0, 0);
                        opacity: ${Math.random() * 0.5 + 0.1};
                    }
                    100% {
                        transform: translate(var(--x-move), var(--y-move));
                        opacity: ${Math.random() * 0.5 + 0.1};
                    }
                }
            `;
            document.head.appendChild(style);
        });
    </script>
</body>
</html>
