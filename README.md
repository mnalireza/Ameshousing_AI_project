<div dir="rtl" align="right">

<div align="center">
  <h1>🏡 مدل ارزیابی خودکار و پیش‌بینی هوشمند قیمت مسکن (Ames Housing AVM)</h1>
  <p><strong>طراحی سیستم تخمین قیمت املاک مبتنی بر یادگیری ماشین | پروژه درس هوش مصنوعی مقدماتی (AI Foundation)</strong></p>
  <p>
  <a href="https://www.w3schools.com/python/default.asp" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" alt="Python">
  </a>
  <a href="https://www.w3schools.com/python/numpy/default.asp" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Data%20Analysis-Pandas%20%7C%20NumPy-150458" alt="Pandas & NumPy">
  </a>
  <a href="https://www.tutorialspoint.com/scikit_learn/scikit_learn_introduction.htm" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white">
  </a>
  <a href="https://www.w3schools.com/python/matplotlib_intro.asp" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-2B5B84" alt="Visualization">
  </a>
  </p>
</div>

<hr />

<h3>📋 سناریو و صورت مسئله</h3>
<p>
در این پروژه، سناریوی کاری یک متخصص یادگیری ماشین در یک استارتاپ حوزه املاک و مستغلات پیاده‌سازی شده است. هدف اصلی، توسعه یک <strong>سیستم ارزیابی خودکار (Automated Valuation Model - AVM)</strong> است که بتواند بر اساس ویژگی‌های ساختاری و محیطی ملک (نظیر متراژ مفید، کیفیت متریال ساخت، سال ساخت و مساحت زیرزمین)، ارزش واقعی مسکن را با خطایی معقول پیش‌بینی کند. استقرار چنین مدلی به تیم‌های فروش و سرمایه‌گذاری اجازه می‌دهد تا سیستم قیمت‌گذاری اولیه املاک را از حالت دستی و سنتی به فرآیندی هوشمند، داده‌محور و پایدار تبدیل نمایند.
</p>

<br />

<h3>📊 مشخصات مجموعه داده (Dataset)</h3>
<p>
مبنای تحلیل در این پروژه، مجموعه داده استاندارد و معتبر <strong>Ames Housing</strong> است. این مجموعه داده اطلاعات معاملاتی مربوط به فروش املاک در شهر ایمز (ایالت آیووا، آمریکا) را در بر می‌گیرد و شامل بیش از <strong>۱۴۰۰ رکورد مسکونی</strong> با نزدیک به <strong>۸۰ ویژگی متنوع</strong> از خصوصیات فیزیکی، کیفی و موقعیت جغرافیایی هر خانه است. این دیتاست به دلیل غنای بالا و سناریوهای واقعی‌تر در پاک‌سازی و مدیریت داده‌ها، به عنوان نسخه‌ای کامل‌تر، مدرن‌تر و آموزنده‌تر نسبت به مجموعه داده کلاسیک Boston Housing شناخته می‌شود.
</p>

<br />

<h3>🎯 اهداف آموزشی و دستاوردهای فنی</h3>
<p>
تمرکز کلیدی این ریپازیتوری بر یادگیری عمیق، استاندارد و کدنویسی تمیز در پایپ‌لاین‌های یادگیری نظارت‌شده (Supervised Learning) است:
</p>
<ul>
  <li>تسلط بر کار با کتابخانه‌های بنیادین علم داده نظیر <strong>Pandas</strong> و <strong>NumPy</strong> برای پالایش و کاوش داده‌ها.</li>
  <li>درک ریاضی و کاربردی الگوریتم <strong>رگرسیون خطی (Linear Regression)</strong> و نحوه حل معادلات آن.</li>
  <li>یادگیری تکنیک‌های پایه‌ای پاک‌سازی داده‌ها (Imputation)، مدیریت مقادیر گم‌شده و تبدیل متغیرهای متنی با <strong>One-Hot Encoding</strong>.</li>
  <li>کسب مهارت در <strong>مهندسی ویژگی (Feature Engineering)</strong> برای ایجاد شاخص‌های پرقدرت عددی از ترکیب ابعاد خام ملک.</li>
  <li>تسلط بر معیارهای استاندارد اعتبارسنجی مدل‌های رگرسیونی از جمله <strong>MAE</strong>، <strong>RMSE</strong> و <strong>R² Score</strong> در کتابخانه <strong>Scikit-learn</strong>.</li>
</ul>

<br />

<h3>📂 ساختار و فازبندی گام‌به‌گام پروژه</h3>
<table width="100%">
  <thead>
    <tr>
      <th width="15%" align="right">فاز</th>
      <th width="35%" align="right">مرحله پیاده‌سازی</th>
      <th width="50%" align="right">شرح اقدامات کلیدی</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>فاز ۱</strong></td>
      <td><strong>آماده‌سازی و کاوش داده‌ها</strong><br /><sub>Preprocessing & Data Exploration</sub></td>
      <td>بارگذاری داده‌ها، تحلیل توزیع آماری قیمت فروش (SalePrice)، مدیریت علمی مقادیر گم‌شده عددی و دسته‌ای، و انکود متغیرهای کیفی.</td>
    </tr>
    <tr>
      <td><strong>فاز ۲</strong></td>
      <td><strong>مهندسی و انتخاب ویژگی‌ها</strong><br /><sub>Feature Engineering & Selection</sub></td>
      <td>خلق ویژگی ترکیبی TotalSF (مجموع متراژ طبقات و زیرزمین)، انتخاب ۵ متغیر کلیدی اثرگذار، و مصورسازی نمودارهای همبستگی.</td>
    </tr>
    <tr>
      <td><strong>فاز ۳</strong></td>
      <td><strong>ساخت و برازش مدل</strong><br /><sub>Model Training & Optimization</sub></td>
      <td>جداسازی اصولی داده‌ها به بخش آموزش و آزمون (Train/Test Split) و آموزش مدل رگرسیون خطی پایه با Scikit-learn.</td>
    </tr>
    <tr>
      <td><strong>فاز ۴</strong></td>
      <td><strong>ارزیابی و تحلیل خطاها</strong><br /><sub>Model Evaluation & Interpretation</sub></td>
      <td>سنجش پیش‌بینی‌ها روی داده تست، استخراج مقادیر عددی MAE و RMSE، محاسبه ضریب تعیین (R²)، و تحلیل چرایی خطای املاک لوکس.</td>
    </tr>
    <tr>
      <td><strong>بخش ویژه</strong></td>
      <td><strong>آزمایش‌های تکمیلی و بنچ‌مارک</strong><br /><sub>Bonus Challenges</sub></td>
      <td>بررسی رفتار مدل‌های درختی (Random Forest و Gradient Boosting)، بررسی اثر استانداردسازی با StandardScaler، و تحلیل نمودار باقیمانده‌ها (Residuals Plot).</td>
    </tr>
  </tbody>
</table>

<br />

<hr />

</div>
<div align="left" dir="ltr">
  <sub>👤 <strong>توسعه‌دهنده:</strong> علیرضا حسینی | <strong>ورودی:</strong> ۱۴۰۴ | <strong>رشته:</strong> مهندسی برق دانشگاه شهید بهشتی</sub>
</div>

</div>
