# تعليمات تركيب تصميم GitHub

## 1) إنشاء Repository الصحيح

افتح https://github.com/new ثم أنشئ مستودعاً عاماً **Public** واسمه بالضبط:

`samirmihoubi2003`

وفعّل خيار Add a README إذا رغبت. يجب أن يطابق اسم المستودع اسم حسابك.

## 2) الطريقة الأسهل لنشر الملفات دفعة واحدة

1. فك ضغط الملف ZIP على حاسوبك.
2. افتح PowerShell داخل مجلد `samir_github_profile`.
3. نفّذ الأوامر التالية بعد إنشاء المستودع الفارغ من GitHub (يفضل إنشاؤه بلا README لتجنب التعارض):

```powershell
git init
git branch -M main
git add .
git commit -m "Create engineering and analytics profile"
git remote add origin https://github.com/samirmihoubi2003/samirmihoubi2003.git
git push -u origin main
```

إذا أنشأت المستودع وفيه README مسبقًا، استخدم طريقة رفع الملفات من المتصفح، أو استنسخ المستودع أولًا.

## 3) تفعيل حركة Snake

1. افتح مستودع profile على GitHub.
2. Settings → Actions → General → Workflow permissions.
3. اختر **Read and write permissions** واضغط Save إن كان هذا الخيار متاحًا.
4. Actions → Generate contribution snake → Run workflow.
5. تأكد أن التنفيذ نجح، وأن فرع `output` قد تم إنشاؤه؛ بعدها يظهر الرسم أسفل الملف.

*إذا بقيت الصورة لا تظهر، افتح رابط الصورة مباشرة وتأكد أن الفرع output موجود وأن GitHub Actions تعمل.*

## 4) تخصيص تفاصيل المشروع

- روابط المشاريع المذكورة بُنيت على أسماء مستودعاتك من محادثات سابقة؛ راجعها بعد النشر، خاصة أسماء المجلدات أو المستودعات التي غيرتها مؤخرًا.
- عدّل سطر التوفر للتدريب وملخص المهارات وقت الحاجة.
- يمكنك حذف أي مشروع لا تريد إبرازه أو استبداله بمشروع آخر.

## 5) تعديل Bio في واجهة GitHub

Bio مقترح:

`Aspiring Data Engineer & Data Analyst | Python · SQL · PostgreSQL · Power BI | Building pipelines & analytics solutions`

Location: `France`

Website: رابط LinkedIn إن رغبت.

## 6) تثبيت المشاريع (Pins)

Profile → Customize your pins، ثم اختر أولًا المشاريع المتعلقة بـ ETL وData Engineering، يليها مشاريع Analytics وMachine Learning.

## 7) ملاحظات

- الملف `assets/hero-animated.gif` يضمن حركة الترويسة في GitHub؛ كما أضفنا نسخة SVG أصلية قابلة للتعديل وملف مخطط SVG آخر.
- تأثيرات SVG المتحركة قد تختلف بحسب المتصفح وسياسات GitHub للصور.
- حركات Snake تتطلب نجاح workflow؛ لن تظهر في أول معاينة حتى يُنشأ فرع `output`.
- بعض بطاقات badges تعتمد على خدمة shields.io؛ إذا كانت الخدمة لا تعمل، يبقى المحتوى نصيًا واضحًا.
