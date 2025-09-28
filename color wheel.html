<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🎨 عجلة الألوان الاحترافية</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700&display=swap" rel="stylesheet">

<style>

/* التنسيق العام */
body {
    font-family: 'Cairo', sans-serif;
    background: linear-gradient(135deg, #eef4ff, #ffffff);
    color: #333;
    padding: 30px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

/* البطاقة الرئيسية */
.color-tool-card {
    background: #ffffff;
    max-width: 550px;
    width: 100%;
    padding: 30px 25px;
    border-radius: 16px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.08);
    text-align: center;
    margin-bottom: 40px;
}

/* العنوان */
h2 {
    color: #1a73e8;
    font-size: 1.8em;
    margin-bottom: 25px;
    font-weight: 700;
}

/* عجلة الألوان */
canvas {
    cursor: crosshair;
    margin: 25px auto;
    border-radius: 50%;
    box-shadow: 0 5px 15px rgba(0,0,0,0.15);
}

/* شريط الكود اللوني */
.color-info {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 25px;
    gap: 15px;
    padding: 12px 15px;
    background: #f7f9fc;
    border-radius: 10px;
    font-weight: 600;
}

#hex {
    color: #1a73e8;
    direction: ltr;
    font-size: 1.2em;
}

/* قائمة الاختيار */
#scheme {
    padding: 12px 16px;
    border-radius: 8px;
    border: 1px solid #ccc;
    background-color: #ffffff;
    font-size: 1em;
    cursor: pointer;
    width: 85%;
    max-width: 280px;
    margin: 10px auto 20px;
    transition: all 0.2s;
}

#scheme:hover {
    border-color: #1a73e8;
    box-shadow: 0 3px 6px rgba(26, 115, 232, 0.2);
}

/* لوحة الألوان */
.palette {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
    margin-top: 20px;
}

.color-box {
    width: 70px;
    height: 70px;
    border-radius: 12px;
    border: 1px solid #ddd;
    transition: transform 0.2s, box-shadow 0.2s;
    cursor: pointer;
}

.color-box:hover {
    transform: translateY(-4px);
    box-shadow: 0 6px 15px rgba(0,0,0,0.12);
}

/* مربع الشرح */
#scheme-tip {
    margin: 20px auto 15px;
    max-width: 95%;
    padding: 18px;
    background: #f0f7ff;
    border-left: 6px solid #1a73e8;
    border-radius: 12px;
    font-size: 0.95em;
    line-height: 1.7;
    text-align: right;
}

/* الأزرار */
.action-buttons {
    margin-top: 30px;
    display: flex;
    justify-content: center;
    gap: 18px;
    flex-wrap: wrap;
}

.btn {
    padding: 12px 25px;
    border: none;
    border-radius: 8px;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.2s;
    font-size: 1em;
}

.btn-primary {
    background-color: #1a73e8;
    color: white;
}

.btn-primary:hover {
    background-color: #0b5ac3;
    transform: translateY(-2px);
}

.btn-secondary {
    background-color: #e0e0e0;
    color: #333;
}

.btn-secondary:hover {
    background-color: #ccc;
    transform: translateY(-2px);
}

/* منطقة التصدير */
#palette-export-area {
    background-color: #ffffff;
    padding: 25px;
    border-radius: 14px;
    margin-top: 20px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    transition: box-shadow 0.2s;
}

#palette-export-area:hover {
    box-shadow: 0 8px 20px rgba(0,0,0,0.12);
}

/* قسم المقال */
.article-section {
    max-width: 700px;
    text-align: right;
    line-height: 1.8;
    margin-bottom: 50px;
    background: #f7f9fc;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
}

.article-section h3 {
    color: #1a73e8;
    margin-bottom: 15px;
    font-weight: 700;
}

.article-section table {
    width: 100%;
    border-collapse: collapse;
    margin: 15px 0;
}

.article-section table, th, td {
    border: 1px solid #ddd;
}

.article-section th, td {
    padding: 10px;
    text-align: center;
}

.article-section th {
    background-color: #e8f0fe;
}

</style>
</head>
<body>
    <div class="color-tool-card">
        <h2>🎨 عجلة الألوان الاحترافية</h2>
        <canvas id="wheel" width="300" height="300"></canvas>
        
        <label>اختر نوع لوحة الألوان:</label>
        <select id="scheme">
            <option value="complementary" selected>مكمل</option>
            <option value="analogous">مماثل</option>
            <option value="monochromatic">أحادي اللون</option>
            <option value="triadic">ثلاثي</option>
            <option value="tetradic">رباعي</option>
        </select>

        <div id="palette-export-area">
            <div class="color-info">
                <p>الكود اللوني: <span id="hex">#000000</span></p>
            </div>
            
            <div class="palette" id="palette"></div>
        </div>
        
        <div id="scheme-tip">
            اختر نوع لوحة الألوان لمعرفة متى تستخدمه في تصاميمك.
        </div>
        
        <div class="action-buttons">
            <button class="btn btn-primary" id="exportBtn">تصدير لوحة الألوان (PDF)</button>
            <button class="btn btn-secondary">إنشاء رسم بياني</button>
        </div>

    </div>

<!-- قسم المقال -->
<div class="article-section">
    <h3>🎨 دليل اختيار الألوان المناسبة في التصميم وما تعنيه</h3>
    <p>اختيار الألوان في التصميم ليس مجرد مسألة ذوق شخصي، بل هو علم وفن يؤثر على شعور المستخدم وتفاعل الجمهور مع المنتج أو المحتوى. الألوان تنقل رسائل وتثير مشاعر، لذلك اختيارها بشكل صحيح يمكن أن يجعل التصميم أكثر جاذبية وفعالية.</p>
    
    <h3>1. فهم عجلة الألوان</h3>
    <p>عجلة الألوان هي أداة أساسية لأي مصمم، حيث تُظهر العلاقة بين الألوان الأساسية والثانوية والثالثية. الألوان تقسم عادة إلى:</p>
    <ul>
        <li><strong>ألوان أساسية</strong>: أحمر، أزرق، أصفر.</li>
        <li><strong>ألوان ثانوية</strong>: أخضر، برتقالي، بنفسجي (ناتجة عن خلط الألوان الأساسية).</li>
        <li><strong>ألوان ثالثية</strong>: مزيج من الأساسي والثانوي.</li>
    </ul>
    
    <h3>2. أنواع لوحات الألوان</h3>
    <p>يمكن استخدام عدة أنظمة لاختيار الألوان معًا في تصميم واحد:</p>
    <ul>
        <li><strong>الألوان المكملة</strong>: يخلق تباينًا قويًا وملفتًا للنظر. مثال: أزرق وبرتقالي. الاستخدام: إعلانات، عروض ترويجية.</li>
        <li><strong>الألوان المماثلة</strong>: تعطي شعورًا بالانسجام والهدوء. مثال: أزرق، أزرق-أخضر، أخضر. الاستخدام: محتوى تعليمي، صفحات هادئة.</li>
        <li><strong>الألوان الأحادية</strong>: درجات مختلفة لنفس اللون. يعطي إحساسًا بالأناقة والبساطة. الاستخدام: تصميمات Minimal، صفحات تقنية.</li>
        <li><strong>الألوان الثلاثية</strong>: ثلاثة ألوان متباعدة بالتساوي على العجلة. تضيف حيوية وطاقة للتصميم. الاستخدام: محتوى شبابي، ترفيهي، مطاعم.</li>
        <li><strong>الألوان الرباعية</strong>: مجموعتين من الألوان المكملة. توفر تنوعًا كبيرًا لكن يصعب التحكم فيها. الاستخدام: براندات كبيرة ذات محتوى متعدد وغني.</li>
    </ul>
    
    <h3>3. فهم معاني الألوان</h3>
    <table>
        <tr>
            <th>اللون</th>
            <th>المعنى والشعور</th>
        </tr>
        <tr><td>الأحمر</td><td>القوة، الحماس، الطاقة، الطوارئ</td></tr>
        <tr><td>الأزرق</td><td>الثقة، الهدوء، الاحترافية</td></tr>
        <tr><td>الأخضر</td><td>الطبيعة، الصحة، النمو، الاستقرار</td></tr>
        <tr><td>الأصفر</td><td>التفاؤل، الإبداع، الانتباه</td></tr>
        <tr><td>البرتقالي</td><td>المرح، الحيوية، الحماس</td></tr>
        <tr><td>البنفسجي</td><td>الفخامة، الإبداع، الغموض</td></tr>
        <tr><td>الأسود</td><td>القوة، الرسمية، الأناقة</td></tr>
        <tr><td>الأبيض</td><td>النقاء، البساطة، الصفاء</td></tr>
    </table>
    
    <h3>4. نصائح عملية لاختيار الألوان</h3>
    <ul>
        <li>حدد هدف التصميم أولًا: إعلان، محتوى تعليمي، شعار؟</li>
        <li>استخدم الألوان وفق العلامة التجارية للحفاظ على الهوية.</li>
        <li>تجنب استخدام ألوان متنافرة جدًا إلا إذا كان هدفك لفت الانتباه.</li>
        <li>اختبر التباين لتسهيل القراءة والتمييز بين العناصر.</li>
        <li>الاستفادة من أدوات اختيار الألوان الرقمية لتجربة التركيبات قبل التنفيذ.</li>
    </ul>
    
    <h3>5. خلاصة</h3>
    <p>الألوان لغة بصرية قوية. اختيار الألوان المناسبة يمكن أن يعزز تجربة المستخدم، يوضح الرسائل، ويزيد من فعالية التصميم. فهم علاقات الألوان ومعانيها هو خطوة أساسية للنجاح في أي تصميم.</p>
</div>
    <script>
        const canvas = document.getElementById('wheel');
        const ctx = canvas.getContext('2d');
        const radius = canvas.width / 2;

        // رسم عجلة الألوان
        for (let angle = 0; angle < 360; angle++) {
            let startAngle = (angle - 1) * Math.PI / 180;
            let endAngle = angle * Math.PI / 180;
            ctx.beginPath();
            ctx.moveTo(radius, radius);
            ctx.arc(radius, radius, radius, startAngle, endAngle);
            ctx.closePath();
            ctx.fillStyle = `hsl(${angle}, 100%, 50%)`;
            ctx.fill();
        }

        const hexSpan = document.getElementById('hex');
        const paletteDiv = document.getElementById('palette');
        const schemeSelect = document.getElementById('scheme');
        const schemeTip = document.getElementById('scheme-tip');

        // حفظ قيمة الزاوية الأخيرة (لإعادة حساب اللوحة عند تغيير نوعها)
        let lastSelectedHue = 0; 
        
        function hslToHex(h, s, l) {
            s /= 100; l /= 100;
            const k = n => (n + h / 30) % 12;
            const a = s * Math.min(l, 1 - l);
            const f = n => l - a * Math.max(-1, Math.min(k(n)-3, Math.min(9-k(n),1)));
            return "#" + [f(0),f(8),f(4)].map(x =>
                Math.round(x*255).toString(16).padStart(2,"0")).join('');
        }

        function updateSchemeTip(scheme) {
            let tip = "";
            switch (scheme) {
                case "complementary":
                    tip = "مكمل 🎯: يستخدم للـ **إعلانات والعروض الترويجية** لخلق تباين قوي وجذاب يشد الانتباه.";
                    break;
                case "analogous":
                    tip = "مماثل 🌿: يعطي إحساسًا بالانسجام والهدوء. مثالي للـ **محتوى التعليمي أو التوعوي** (الصحة، الطبيعة).";
                    break;
                case "monochromatic":
                    tip = "أحادي اللون ✨: لون واحد بتدرجاته. ممتاز للتصاميم **الأنيقة، البسيطة (Minimal)** أو الصفحات التقنية.";
                    break;
                case "triadic":
                    tip = "ثلاثي 🥳: يضفي طاقة وحيوية. الأفضل للحسابات **الشبابية، الترفيهية** أو العلامات التجارية المرحة (مطاعم).";
                    break;
                case "tetradic":
                    tip = "رباعي 🧩: صعب التحكم فيه. يوفر تنوعًا كبيرًا للـ **براندات الكبيرة** ذات المحتوى المتعدد.";
                    break;
                default:
                    tip = "اختر نوع لوحة الألوان لمعرفة متى تستخدمه في تصاميمك.";
            }
            schemeTip.innerHTML = tip;
        }

        function showPalette(hue) {
            paletteDiv.innerHTML = "";
            const scheme = schemeSelect.value;
            let hues = [];

            if (scheme === "complementary") hues = [hue, (hue+180)%360];
            if (scheme === "analogous") hues = [(hue-30+360)%360, hue, (hue+30)%360];
            
            if (scheme === "monochromatic") {
                let s = 80; 
                let l = 50;
                // إنشاء تدرجات مختلفة للسطوع والتشبع
                let colors = [
                    hslToHex(hue, s, l + 20), // فاتح جداً
                    hslToHex(hue, s, l + 10), // فاتح
                    hslToHex(hue, s, l),     // عادي
                    hslToHex(hue, s, l - 10), // غامق
                    hslToHex(hue, s, l - 20)  // غامق جداً
                ];
                colors.forEach(hex => {
                    let div = document.createElement("div");
                    div.className = "color-box";
                    div.style.background = hex;
                    paletteDiv.appendChild(div);
                });
                return;
            }
            if (scheme === "triadic") hues = [hue, (hue+120)%360, (hue+240)%360];
            if (scheme === "tetradic") hues = [hue, (hue+90)%360, (hue+180)%360, (hue+270)%360];

            hues.forEach(h => {
                let hex = hslToHex((h+360)%360, 100, 50);
                let div = document.createElement("div");
                div.className = "color-box";
                div.style.background = hex;
                paletteDiv.appendChild(div);
            });
        }

        canvas.addEventListener('click', (e) => {
            let x = e.offsetX - radius;
            let y = e.offsetY - radius;
            let angle = Math.atan2(y, x) * 180 / Math.PI;
            if (angle < 0) angle += 360;
            
            lastSelectedHue = angle; 
            
            let hex = hslToHex(angle, 100, 50);
            hexSpan.textContent = hex;
            showPalette(angle);
        });

        schemeSelect.addEventListener('change', () => {
            showPalette(lastSelectedHue); 
            updateSchemeTip(schemeSelect.value);
        });

        // ----------------------------------------------------
        // 🌟 دالة ووظائف التصدير إلى PDF 🌟
        // ----------------------------------------------------
        const exportBtn = document.getElementById('exportBtn');
        const paletteExportArea = document.getElementById('palette-export-area');
        
        // تأكد من أن window.jsPDF هو المرجع الصحيح للمكتبة
        const { jsPDF } = window.jspdf; 

        function exportPaletteAsPdf() {
            const schemeName = schemeSelect.options[schemeSelect.selectedIndex].text;
            
            html2canvas(paletteExportArea, { 
                scale: 2, // زيادة الدقة
                useCORS: true, // ضروري إذا كانت الصور تأتي من مصادر مختلفة (غير قابلة للتطبيق هنا مباشرة لكن جيد)
                backgroundColor: '#ffffff' // تأكد من أن الخلفية بيضاء للوضوح
            }).then(canvas => {
                const imgData = canvas.toDataURL('image/png');
                const pdf = new jsPDF('p', 'mm', 'a4'); 

                const pdfWidth = pdf.internal.pageSize.getWidth();
                const pdfHeight = pdf.internal.pageSize.getHeight();

                const imgWidth = 180; // عرض الصورة في PDF (بالملليمتر)
                const imgHeight = (canvas.height * imgWidth) / canvas.width;
                
                const marginX = (pdfWidth - imgWidth) / 2; // توسيط أفقي

                // إضافة العنوان (تأكد من دعم الخطوط العربية إذا كنت تريدها في الـ PDF)
                // jsPDF يحتاج إلى خطوط عربية مخصصة لعرض النص العربي بشكل صحيح.
                // للتبسيط، سأستخدم خطاً افتراضياً، وقد لا يظهر النص العربي بشكل مثالي.
                pdf.setFont("helvetica", "bold");
                pdf.setFontSize(16);
                pdf.text('لوحة الألوان: ' + schemeName, pdfWidth / 2, 20, { align: 'center' }); 
                
                // إضافة الصورة الملتقطة إلى PDF
                pdf.addImage(imgData, 'PNG', marginX, 30, imgWidth, imgHeight); 

                pdf.save(`ColorPalette_${schemeName}.pdf`);
                
                alert(`تم تصدير لوحة الألوان (${schemeName}) كملف PDF بنجاح!`);
            }).catch(error => {
                console.error("خطأ في تصدير PDF:", error);
                alert("حدث خطأ أثناء تصدير ملف PDF. يرجى المحاولة مرة أخرى.");
            });
        }

        // ربط دالة التصدير PDF بالزر
        exportBtn.addEventListener('click', exportPaletteAsPdf);

        // تشغيل أولي عند تحميل الصفحة
        updateSchemeTip(schemeSelect.value);
        showPalette(0); // عرض لوحة ألوان أولية (أزرق) عند التحميل
    </script>
</body>
</html>
