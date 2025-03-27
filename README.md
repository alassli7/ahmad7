<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>السيرة الذاتية - أحمد المليلي</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap');
        
        body {
            font-family: 'Tajawal', sans-serif;
            line-height: 1.8;
            color: #333;
            background-color: #f8fbfe;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            box-shadow: 0 5px 30px rgba(0, 119, 204, 0.15);
            border-radius: 15px;
            overflow: hidden;
        }
        .header {
            background: linear-gradient(135deg, #4da6ff, #2b87da);
            color: white;
            padding: 40px 30px;
            text-align: center;
            position: relative;
        }
        .header::after {
            content: "";
            position: absolute;
            bottom: -20px;
            left: 0;
            right: 0;
            height: 40px;
            background: url('data:image/svg+xml;utf8,<svg viewBox="0 0 1200 120" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none"><path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" fill="%23ffffff" opacity=".25"/></svg>');
            background-size: cover;
        }
        .header h1 {
            margin: 0;
            font-size: 36px;
            font-weight: 700;
        }
        .header p {
            margin: 10px 0 0;
            font-size: 18px;
            opacity: 0.9;
        }
        .contact-bar {
            background: #e6f2ff;
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            text-align: center;
            font-size: 15px;
        }
        .contact-bar div {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }
        .main-content {
            padding: 40px;
        }
        h2 {
            color: #2b87da;
            border-bottom: 2px dashed #4da6ff;
            padding-bottom: 8px;
            font-size: 24px;
            margin-top: 30px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        h2::before {
            content: "■";
            color: #4da6ff;
            font-size: 20px;
        }
        .section {
            margin-bottom: 30px;
        }
        .job {
            margin-bottom: 25px;
            position: relative;
            padding-left: 25px;
        }
        .job::before {
            content: "▹";
            position: absolute;
            left: 0;
            color: #4da6ff;
            font-size: 20px;
        }
        .job-title {
            font-weight: 700;
            margin: 5px 0;
            font-size: 18px;
            color: #2b5f8a;
        }
        .company {
            color: #666;
            margin: 5px 0;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        .company::before {
            content: "🏢";
        }
        .date {
            color: #4da6ff;
            margin: 5px 0 15px;
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 500;
        }
        .date::before {
            content: "📅";
        }
        ul {
            padding-left: 25px;
            list-style-type: none;
        }
        li {
            margin-bottom: 12px;
            position: relative;
            padding-left: 25px;
        }
        li::before {
            content: "•";
            position: absolute;
            left: 0;
            color: #4da6ff;
            font-size: 20px;
        }
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .skill-category {
            background: #f0f7ff;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #4da6ff;
            box-shadow: 0 3px 10px rgba(0, 119, 204, 0.1);
        }
        .skill-category h3 {
            margin-top: 0;
            color: #2b5f8a;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .skill-category h3::before {
            content: "✓";
            color: #4da6ff;
            font-weight: bold;
        }
        .objective {
            background: #f0f7ff;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #4da6ff;
            font-size: 17px;
            line-height: 1.8;
            position: relative;
        }
        .objective::before {
            content: "“";
            position: absolute;
            top: 10px;
            left: 10px;
            font-size: 60px;
            color: rgba(0, 119, 204, 0.1);
            font-family: serif;
            line-height: 1;
        }
        .certificate {
            background: #f0f7ff;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #4da6ff;
            margin-bottom: 20px;
            position: relative;
            box-shadow: 0 3px 10px rgba(0, 119, 204, 0.1);
        }
        .certificate::before {
            content: "📜";
            position: absolute;
            top: 20px;
            left: -15px;
            background: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .cert-title {
            font-weight: 700;
            margin: 0 0 10px;
            color: #2b5f8a;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .cert-title::before {
            content: "🏆";
        }
        .cert-details {
            color: #555;
            margin: 5px 0;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        .cert-details::before {
            content: "📌";
        }
        .footer {
            background: linear-gradient(135deg, #4da6ff, #2b87da);
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 15px;
        }
        .footer::before {
            content: "";
            display: block;
            height: 1px;
            background: rgba(255,255,255,0.2);
            margin-bottom: 15px;
        }
        @media print {
            body {
                background: none;
            }
            .container {
                box-shadow: none;
                margin: 0;
                border-radius: 0;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>أحمد مبارك المليلي</h1>
            <p>فني ميكانيكا | مدرب لياقة بدنية</p>
        </div>
        
        <div class="contact-bar">
            <div>📋 <strong>الهوية:</strong> 1016933974</div>
            <div>🎂 <strong>الميلاد:</strong> 19/08/1989</div>
            <div>🏠 <strong>العنوان:</strong> الأحساء ص.ب 4481</div>
            <div>📱 <strong>الاتصال:</strong> 0564882991</div>
            <div>💍 <strong>الحالة:</strong> أعزب</div>
            <div>📋 <strong>إيميل:</strong> alshoq90@hotmail.com</div>
        </div>
        
        <div class="main-content">
            <div class="section">
                <h2>🎯 الهدف المهني</h2>
                <div class="objective">
                    تحسين وتطوير مهاراتي والخدمة للوصول إلى أفضل مكانة ممكنة وزيادة الخبرة والمهارات العملية والتعرف على أصدقاء في مجال التخصص ووضع بصمة بمعنى أن يكون لي أعمال ذات قيمة بالمنشأة.
                </div>
            </div>
            
            <div class="section">
                <h2>💼 الخبرات العملية</h2>
                <div class="job">
                    <p class="job-title">فني تكييف</p>
                    <p class="company">شركة تكييف الهواء السعودي (فرع شركة العرفج)</p>
                    <p class="date">2015 - 2016 (سنة واحدة)</p>
                </div>
                <div class="job">
                    <p class="job-title">فني صيانة</p>
                    <p class="company">مؤسسة محمد علي الحمود</p>
                    <p class="date">2016 - 2023 (7 سنوات)</p>
                </div>
                <div class="job">
                     <p class="job-title">فني ميكانيكا</p>
                     <p class="company">الشركة السعودية للموانئ</p>
                     <p class="date">2023 - 2024</p>
                 </div>
               <div class="job">
                    <p class="job-title">سائق محترف وصيانة مركبات</p>
                    <p class="company">شركة إيتقان للحلول التقنية</p>
                    <p class="date">2024 - 2025</p>
                </div>
            </div>
            
            <div class="section">
                <h2>🎓 المؤهلات العلمية</h2>
                <ul>
                    <li>شهادة المتوسطة بتقدير جيد</li>
                </ul>
            </div>
            
            <div class="section">
                <h2>📜 الشهادات الحاصل عليها</h2>
                
                <div class="certificate">
                    <p class="cert-title">شهادة تقدير</p>
                    <p class="cert-details">قسم دعم مرافق التدريب</p>
                    <p>تقديرًا للتفاني والمساهمة المتميزة في صيانة مرافق التدريب والتطوير</p>
                </div>
                
                <div class="certificate">
                    <p class="cert-title">DIP E-LEARNING</p>
                    <p class="cert-details">رمز الدورة: 1556 | تاريخ الإتمام: 08/08/2024</p>
                </div>
                
                <div class="certificate">
                    <p class="cert-title">مقدمة في إدارة الرحلات</p>
                    <p class="cert-details">رمز الدورة: 40121805 | تاريخ الإتمام: 08/08/2024</p>
                </div>
                
                <div class="certificate">
                    <p class="cert-title">توجيه لخطة الطوارئ</p>
                    <p class="cert-details">الشركة: إيتقان للحلول التقنية | تاريخ الإتمام: 04/03/2024</p>
                    <p>تدريب على مبادئ العمل في حالات الطوارئ والعزل الآمن</p>
                </div>
            </div>
            
            <div class="section">
                <h2>📜 الرخص</h2>
                <ul>
                    <li>🚛 مركبات أشغال عامة</li>
                    <li>🚚 نقل ثقيل</li>
                </ul>
            </div>
            
            <div class="section">
                <h2>🛠️ المهارات</h2>
                <div class="skills-container">
                    <div class="skill-category">
                        <h3>🔧 المهارات الفنية</h3>
                        <ul>
                            <li>ميكانيكا سيارات</li>
                            <li>صيانة تكييف</li>
                            <li>صيانة منزلية</li>
                        </ul>
                    </div>
                    <div class="skill-category">
                        <h3>💪 المهارات الشخصية</h3>
                        <ul>
                            <li>مدرب لياقة بدنية</li>
                            <li>العمل ضمن فريق</li>
                            <li>إدارة الوقت</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="footer">
            للتواصل: 0564882991 | الأحساء، المملكة العربية السعودية
        </div>
    </div>
</body>
</html>
