# 🐍 پایتون شگفت‌انگیز – مجموعه‌ای از ابزارها و کتابخانه‌های کاربردی پایتون

> نسخه‌ی فارسی ریپازیتوری محبوب [awesome-python](https://github.com/vinta/awesome-python) برای فارسی‌زبانان

---

## 📝 مقدمه

پایتون یکی از زبان‌های برنامه‌نویسی محبوب و پرکاربرد در دنیاست. از ساخت وب‌سایت گرفته تا تحلیل داده، یادگیری ماشین، اتوماسیون، و حتی ساخت بازی، پایتون حرف‌های زیادی برای گفتن داره.

این ریپازیتوری یک لیست دسته‌بندی‌شده از بهترین و کاربردی‌ترین کتابخانه‌ها و ابزارهای پایتون به زبان فارسیه. هدف اینه که برنامه‌نویس‌های فارسی‌زبان راحت‌تر بتونن ابزار مناسب کارشون رو پیدا کنن و وارد دنیای اوپن‌سورس بشن.
---

## ☕ از این ریپازیتوری خوشتون اومد؟ برام یه کافی بخر!

اگر این پروژه به شما کمک کرده و مفید واقع شده، خوشحال می‌شم که با خرید یک فنجان قهوه از من حمایت کنید! این کمک به من انگیزه می‌ده تا پروژه‌های بیشتری بسازم و منابع مفیدتری به اشتراک بذارم.

👉 [برام یه کافی بخر!](https://www.coffeebede.com/mrrobat)

از حمایت شما بی‌نهایت سپاسگزارم! 😊


---

## 📚 فهرست

- [وب و توسعه وب](#وب-و-توسعه-وب)
- [تحلیل داده](#تحلیل-داده)
- [یادگیری ماشین](#یادگیری-ماشین)
- [تست و دیباگ](#تست-و-دیباگ)
- [ابزارهای خط فرمان](#ابزارهای-خط-فرمان)
- [هوش مصنوعی و nlp](#هوش-مصنوعی-و-nlp)
- [ویرایش و کار با ویدیوها](#ویرایش-و-کار-با-ویدیوها)
- [پردازش تصویر](#پردازش-تصویر)
- [هک و امنیت](#هک-و-امنیت)
- [وب اسکرپینگ](#وب-اسکرپینگ)
- [کار با اکسل](#کار-با-اکسل)
- [کار با پی‌دی‌اف](#کار-با-پی‌دی‌اف)


---

### وب و توسعه وب  
کتابخانه‌هایی برای ساخت و توسعه اپلیکیشن‌های وب.

- [**Django**](https://github.com/django/django) - فریم‌ورک سطح بالا برای ساخت وب‌سایت‌های امن و مقیاس‌پذیر. از ساختار MVC (Model-View-Controller) استفاده می‌کند و شامل ابزارهای متنوع برای تسهیل کارهای معمول در توسعه وب است.
- [**Flask**](https://github.com/pallets/flask) - فریم‌ورک سبک و ماژولار برای ساخت اپلیکیشن‌های وب. بیشتر برای ساخت اپلیکیشن‌های ساده و مقیاس‌پذیر مناسب است و انعطاف‌پذیری بالایی دارد.
- [**FastAPI**](https://github.com/tiangolo/fastapi) - فریم‌ورک سریع برای ساخت APIهای مدرن با پایتون 3.7+. از استانداردهای OpenAPI و JSON Schema پشتیبانی می‌کند و با سرعت بسیار بالا و قابلیت‌های تایپ‌دهی عالی همراه است.
- [**Bottle**](https://github.com/bottlepy/bottle) - فریم‌ورک وب بسیار ساده و کم‌حجم برای اپلیکیشن‌های کوچک و تک‌فایلی. برای پروتوتایپ‌سازی سریع یا پروژه‌های کوچک بسیار مناسب است.
- [**Tornado**](https://github.com/tornadoweb/tornado) - کتابخانه‌ای برای ساخت اپلیکیشن‌های وب غیرهمزمان و مقیاس‌پذیر. مناسب برای پروژه‌هایی که نیاز به پردازش تعداد زیادی درخواست همزمان دارند.
- [**Pyramid**](https://github.com/Pylons/pyramid) - فریم‌ورک توسعه وب انعطاف‌پذیر که به شما این امکان را می‌دهد که از هر چیزی برای پیاده‌سازی استفاده کنید. برای ساخت اپلیکیشن‌های بزرگ و پیچیده بسیار مناسب است.
- [**Sanic**](https://github.com/sanic-org/sanic) - فریم‌ورک سریع برای ساخت اپلیکیشن‌های وب با پشتیبانی از درخواست‌های همزمان (Asynchronous requests) با استفاده از async/await.
- [**CherryPy**](https://github.com/cherrypy/cherrypy) - فریم‌ورک وب با فلسفه‌ی ساده که برای ساخت وب‌سایت‌ها و اپلیکیشن‌های کوچک مناسب است. این فریم‌ورک به شما اجازه می‌دهد تا برنامه‌های خود را با کمترین پیچیدگی پیاده‌سازی کنید.
- [**Falcon**](https://github.com/falconry/falcon) - فریم‌ورک وب برای توسعه APIهای سریع و مقیاس‌پذیر. به‌ویژه برای اپلیکیشن‌هایی که نیاز به عملکرد بالا و پردازش سریع درخواست‌ها دارند.
- [**Web2py**](https://github.com/web2py/web2py) - فریم‌ورک توسعه وب با قابلیت‌های بسیار بالا که تمام امکانات مورد نیاز برای توسعه وب اپلیکیشن‌ها را به صورت یکپارچه فراهم می‌کند.

---

### تحلیل داده  
کتابخانه‌هایی برای تحلیل، پردازش و کار با داده‌ها.

- [**pandas**](https://github.com/pandas-dev/pandas) - تحلیل و دستکاری داده‌های جدولی؛ استاندارد طلایی در پایتون.
- [**NumPy**](https://github.com/numpy/numpy) - آرایه‌های چندبعدی و عملیات عددی سریع.
- [**Polars**](https://github.com/pola-rs/polars) - کتابخانه‌ای بسیار سریع و مدرن برای تحلیل داده‌های حجیم.
- [**OpenPyXL**](https://github.com/openpyxl/openpyxl) - خواندن و نوشتن فایل‌های اکسل (.xlsx).
- [**tabulate**](https://github.com/astanin/python-tabulate) - نمایش داده‌ها به صورت جدول در ترمینال.

---

### یادگیری ماشین  
کتابخانه‌هایی برای توسعه مدل‌های یادگیری ماشین و پردازش داده‌ها.

- [**scikit-learn**](https://github.com/scikit-learn/scikit-learn) - کتابخانه‌ای برای یادگیری ماشین در پایتون که شامل ابزارهایی برای مدل‌های طبقه‌بندی، رگرسیون، کاهش ابعاد، خوشه‌بندی و بسیاری از الگوریتم‌های دیگر است.
- [**TensorFlow**](https://github.com/tensorflow/tensorflow) - یک فریم‌ورک متن‌باز برای یادگیری عمیق که توسط گوگل توسعه داده شده است و برای ساخت و آموزش مدل‌های پیچیده یادگیری ماشین و شبکه‌های عصبی استفاده می‌شود.
- [**Keras**](https://github.com/keras-team/keras) - API سطح بالا برای یادگیری عمیق که به عنوان یک لایه‌ی جلویی برای TensorFlow استفاده می‌شود و ساخت و آزمایش مدل‌ها را ساده‌تر می‌کند.
- [**PyTorch**](https://github.com/pytorch/pytorch) - فریم‌ورک یادگیری عمیق با قابلیت‌های پیشرفته که از توابع مختلف پشتیبانی می‌کند و برای مدل‌سازی شبکه‌های عصبی پیچیده عالی است.
- [**XGBoost**](https://github.com/dmlc/xgboost) - کتابخانه‌ای برای یادگیری تقویتی با استفاده از الگوریتم‌های درخت تصمیم که در مسابقات داده‌کاوی به دلیل کارایی بالای خود شناخته شده است.
- [**LightGBM**](https://github.com/microsoft/LightGBM) - فریم‌ورکی سریع و کارآمد برای یادگیری ماشین مبتنی بر درخت تصمیم که برای داده‌های حجیم بهینه شده است.
- [**CatBoost**](https://github.com/catboost/catboost) - کتابخانه‌ای برای یادگیری ماشین که بر روی داده‌های طبقه‌بندی‌شده بهینه شده و قادر به پردازش داده‌های دسته‌ای است.
- [**fastai**](https://github.com/fastai/fastai) - یک کتابخانه برای یادگیری عمیق که بر اساس PyTorch ساخته شده و تمرکز اصلی آن بر روی سادگی استفاده و تسهیل توسعه مدل‌های پیچیده است.
- [**H2O.ai**](https://github.com/h2oai/h2o-3) - پلتفرمی برای یادگیری ماشین که ابزارهایی برای مدل‌سازی داده‌های حجیم و تحلیل‌های پیچیده ارائه می‌دهد.
- [**spaCy**](https://github.com/explosion/spaCy) - یک کتابخانه قدرتمند برای پردازش زبان طبیعی (NLP) که از مدل‌های پیشرفته یادگیری ماشین برای تحلیل متن‌ها استفاده می‌کند.


---

### تست و دیباگ  
کتابخانه‌هایی برای تست، دیباگ و بهبود کیفیت کد.

- [**pytest**](https://github.com/pytest-dev/pytest) - یک فریم‌ورک برای نوشتن و اجرای تست‌های واحد و دیگر انواع تست‌ها در پایتون. این کتابخانه امکانات زیادی مانند تست پارامترها، تست‌های همزمان و قابلیت‌های پیشرفته برای گزارش‌گیری دارد.
- [**unittest**](https://github.com/python/cpython/tree/main/Lib/unittest) - کتابخانه استاندارد پایتون برای انجام تست‌های واحد. با توجه به اینکه بخشی از پایتون است، برای تست‌های پایه و ساده مناسب است.
- [**nose2**](https://github.com/nose-devs/nose2) - فریم‌ورکی برای تست در پایتون که از طریق پلاگین‌ها قابل گسترش است و امکاناتی نظیر تست‌های خودکار و گزارش‌گیری پیشرفته را ارائه می‌دهد.
- [**tox**](https://github.com/tox-dev/tox) - ابزار خودکار برای تست در چند محیط پایتونی. این کتابخانه به شما کمک می‌کند تا کد خود را در نسخه‌های مختلف پایتون تست کنید.
- [**mock**](https://github.com/testing-cabal/mock) - کتابخانه‌ای برای شبیه‌سازی اشیاء در هنگام نوشتن تست. این ابزار برای تست‌هایی که نیاز به اشیاء خارجی یا توابع پیچیده دارند، بسیار مفید است.
- [**coverage.py**](https://github.com/nedbat/coveragepy) - ابزاری برای اندازه‌گیری پوشش کد در هنگام اجرای تست‌ها. به شما کمک می‌کند که بفهمید کدام قسمت‌های کدتان تحت تست قرار نگرفته‌اند.
- [**pdb**](https://docs.python.org/3/library/pdb.html) - دیباگر استاندارد پایتون برای عیب‌یابی کدها در محیط تعاملی. با استفاده از pdb می‌توانید متغیرها را بررسی کرده و خطایابی را به صورت مرحله‌به‌مرحله انجام دهید.
- [**loguru**](https://github.com/Delgan/loguru) - کتابخانه‌ای برای ثبت لاگ‌ها در پایتون. این کتابخانه قابلیت‌های پیشرفته‌ای برای مدیریت لاگ‌ها و دیباگ کدها در خود دارد.
- [**pyspy**](https://github.com/benfred/py-spy) - ابزار دیباگینگ برای پایتون که می‌تواند وضعیت اجرای برنامه‌ها را بدون تغییر کد بررسی کند و از اطلاعات مربوط به مصرف حافظه و زمان استفاده کند.
- [**flaky**](https://github.com/cherrypi/flaky) - کتابخانه‌ای برای مدیریت تست‌های غیرقابل اعتماد (flaky tests) که می‌تواند مشکلاتی که به‌طور تصادفی در تست‌ها به وجود می‌آید را شبیه‌سازی کند.


---

### ابزارهای خط فرمان  
کتابخانه‌هایی برای توسعه ابزارهای خط فرمان و تعامل با سیستم‌ها.

- [**Click**](https://github.com/pallets/click) - کتابخانه‌ای برای ساخت ابزارهای خط فرمان (CLI) در پایتون. Click قابلیت‌های پیشرفته‌ای برای پارس کردن ورودی‌ها، تنظیمات، و ارائه خروجی به صورت زیبا را فراهم می‌کند.
- [**argparse**](https://github.com/python/cpython/tree/main/Lib/argparse) - کتابخانه استاندارد پایتون برای پردازش آرگومان‌های خط فرمان. argparse به شما اجازه می‌دهد که ورودی‌های مختلفی از کاربر دریافت کنید و با تنظیمات خاصی آن‌ها را پردازش کنید.
- [**docopt**](https://github.com/docopt/docopt) - کتابخانه‌ای برای تعریف رابط‌های خط فرمان به صورت اسنادی. با استفاده از docopt می‌توانید رابط‌های کاربری ساده و خوانا برای برنامه‌های خط فرمان بسازید.
- [**PyInquirer**](https://github.com/CITGuru/PyInquirer) - کتابخانه‌ای برای ساخت رابط‌های تعاملی خط فرمان با استفاده از سوالات مختلف به صورت تعاملی. این کتابخانه به شما کمک می‌کند تا ابزارهای CLI با رابط کاربری جذاب بسازید.
- [**rich**](https://github.com/Textualize/rich) - کتابخانه‌ای برای تولید خروجی‌های زیبا و رنگی در ترمینال. rich قابلیت‌هایی برای چاپ متن، جداول، نمودارها و حتی پروگرس بار را به شما می‌دهد.
- [**sh**](https://github.com/amoffat/sh) - کتابخانه‌ای برای تعامل ساده و راحت با دستورهای سیستم از داخل پایتون. این ابزار به شما اجازه می‌دهد که به راحتی دستورات سیستم عامل را از طریق پایتون اجرا کنید.
- [**fabric**](https://github.com/fabric/fabric) - کتابخانه‌ای برای خودکارسازی وظایف از راه دور از طریق SSH. این کتابخانه برای اتوماسیون عملیات سیستم، استقرار سرور، و مدیریت سرورها مفید است.
- [**plumbum**](https://github.com/tomita/plumbum) - کتابخانه‌ای برای تعامل با سیستم و مدیریت خط فرمان. plumbum به شما امکاناتی برای کار با سیستم فایل‌ها، پردازش‌های سیستم، و ساخت اسکریپت‌های خط فرمان می‌دهد.
- [**cement**](https://github.com/datafolklabs/cement) - فریم‌ورک برای ساخت ابزارهای خط فرمان با ویژگی‌های پیشرفته. Cement از الگوهای طراحی استفاده می‌کند و امکاناتی برای ساخت برنامه‌های CLI با قابلیت‌های زیاد و پیکربندی فراهم می‌آورد.
- [**paramiko**](https://github.com/paramiko/paramiko) - کتابخانه‌ای برای ایجاد ارتباط SSH در پایتون. با استفاده از paramiko می‌توانید اتصالات SSH را برقرار کرده و دستورات از راه دور را اجرا کنید.


---

### هوش مصنوعی و NLP  
کتابخانه‌هایی برای توسعه مدل‌های هوش مصنوعی و پردازش زبان طبیعی.

- [**TensorFlow**](https://github.com/tensorflow/tensorflow) - یک فریم‌ورک منبع باز برای یادگیری ماشین و هوش مصنوعی که توسط گوگل توسعه داده شده است. TensorFlow به شما این امکان را می‌دهد که مدل‌های پیچیده یادگیری عمیق بسازید و آموزش دهید.
- [**PyTorch**](https://github.com/pytorch/pytorch) - فریم‌ورکی منبع باز برای یادگیری عمیق که توسط فیس‌بوک توسعه داده شده است. PyTorch به دلیل سهولت استفاده و قابلیت‌های پیشرفته در پردازش گراف‌های محاسباتی دینامیک محبوب است.
- [**scikit-learn**](https://github.com/scikit-learn/scikit-learn) - کتابخانه‌ای برای یادگیری ماشین در پایتون که شامل الگوریتم‌های مختلف برای رگرسیون، دسته‌بندی، خوشه‌بندی و کاهش ابعاد است.
- [**spaCy**](https://github.com/explosion/spaCy) - کتابخانه‌ای برای پردازش زبان طبیعی که با سرعت بالا و دقت بالا طراحی شده است. spaCy شامل ابزارهایی برای تجزیه و تحلیل جمله، شناسایی موجودیت‌های نام‌دار و تقسیم‌بندی متن است.
- [**nltk**](https://github.com/nltk/nltk) - کتابخانه‌ای برای پردازش زبان طبیعی در پایتون که شامل مجموعه‌ای از ابزارها و منابع برای کار با متن، جمله‌بندی، تجزیه و تحلیل معنایی و غیره است.
- [**Hugging Face Transformers**](https://github.com/huggingface/transformers) - کتابخانه‌ای برای استفاده از مدل‌های پیشرفته NLP مانند BERT، GPT، T5 و دیگر مدل‌های مبتنی بر ترنسفورمرها. این کتابخانه به شما امکان استفاده از مدل‌های پیش‌آموزش‌دیده را می‌دهد.
- [**Gensim**](https://github.com/RaRe-Technologies/gensim) - کتابخانه‌ای برای مدل‌سازی و تجزیه و تحلیل مدل‌های موضوعی و مدل‌های واژه‌برداری مانند Word2Vec و Doc2Vec.
- [**fastai**](https://github.com/fastai/fastai) - کتابخانه‌ای برای یادگیری عمیق که روی PyTorch ساخته شده و تمرکز آن روی تسهیل استفاده از مدل‌های پیچیده است. fastai به شما این امکان را می‌دهد که مدل‌های یادگیری عمیق را به سرعت ایجاد کنید.
- [**AllenNLP**](https://github.com/allenai/allennlp) - کتابخانه‌ای برای پردازش زبان طبیعی که بر روی PyTorch ساخته شده و برای ساخت مدل‌های NLP پیشرفته و تحقیقاتی طراحی شده است.
- [**TextBlob**](https://github.com/sloria/TextBlob) - کتابخانه‌ای برای پردازش متن که شامل ابزارهایی برای تحلیل احساسات، برچسب‌گذاری، تقسیم‌بندی جملات و دیگر کاربردهای NLP است.
- [**Pattern**](https://github.com/clips/pattern) - کتابخانه‌ای برای پردازش زبان طبیعی که شامل ابزارهایی برای تحلیل متن، یادگیری ماشین، داده‌کاوی و دیگر کاربردهای مرتبط با NLP است.
- [**CoreNLP**](https://github.com/stanfordnlp/CoreNLP) - ابزار پردازش زبان طبیعی توسعه داده شده توسط دانشگاه استنفورد. این کتابخانه برای تحلیل جمله‌بندی، استخراج موجودیت‌های نام‌دار، تجزیه و تحلیل ساختاری و دیگر تکنیک‌های پیشرفته NLP به کار می‌رود.


---
### ویرایش و کار با ویدیوها  
کتابخانه‌هایی برای پردازش و ویرایش ویدیو، شامل بریدن، ترکیب، افزودن افکت‌ها و تبدیل فرمت‌ها.

- [**moviepy**](https://github.com/Zulko/moviepy) - کتابخانه‌ای برای ویرایش فیلم‌ها با پایتون. moviepy به شما این امکان را می‌دهد که ویدیوها را برش دهید، افکت‌ها را اعمال کنید، صدا را ویرایش کنید و ویدیوهای جدید بسازید. این کتابخانه از فرمت‌های مختلف پشتیبانی می‌کند و امکانات زیادی برای پردازش و ویرایش ویدیو دارد.
  
- [**scikit-video**](https://github.com/scikit-video/scikit-video) - کتابخانه‌ای برای پردازش ویدیوها در پایتون با استفاده از SciPy. این کتابخانه شامل توابعی برای پردازش فریم‌های ویدیو، تبدیل فرمت‌ها و اعمال فیلترهای مختلف است.

- [**vidgear**](https://github.com/abhiTronix/vidgear) - یک فریم‌ورک قدرتمند و چندرشته‌ای برای پردازش ویدیو. vidgear به شما این امکان را می‌دهد که ویدیوها را با کیفیت بالا پردازش کنید، با استفاده از multi-threading برای پردازش موازی سریع‌تر عمل کنید و از چندین پلتفرم و فرمت ویدیویی پشتیبانی می‌کند.

- [**opencv-python**](https://github.com/opencv/opencv-python) - نسخه پایتون کتابخانه معروف OpenCV است که برای پردازش و تحلیل تصویر و ویدیو به کار می‌رود. این کتابخانه امکانات زیادی برای کار با ویدیو، شناسایی اشیاء، اعمال فیلترها و اصلاحات ویدیو و پردازش تصاویر دارد.

- [**ffmpeg-python**](https://github.com/kkroening/ffmpeg-python) - یک رابط پایتون برای ابزار معروف ffmpeg است. این کتابخانه به شما امکان می‌دهد تا عملیات‌های مختلفی مثل تبدیل فرمت، ویرایش و فشرده‌سازی ویدیوها را با استفاده از ffmpeg از طریق پایتون انجام دهید.
---
### پردازش تصویر  
کتابخانه‌هایی برای کار با تصاویر، انجام اعمال مختلف مانند فیلترگذاری، تغییر اندازه، شناسایی اشیاء و تحلیل تصاویر.

- [**opencv-python**](https://github.com/opencv/opencv-python) - نسخه پایتون کتابخانه معروف OpenCV است که برای پردازش تصاویر و ویدیوها استفاده می‌شود. این کتابخانه ابزارهای قدرتمندی برای شناسایی اشیاء، تحلیل تصاویر و انجام تبدیل‌های هندسی روی تصاویر دارد.

- [**Pillow**](https://github.com/python-pillow/Pillow) - کتابخانه‌ای برای کار با تصاویر در پایتون که بر پایه کتابخانه Python Imaging Library (PIL) ساخته شده است. Pillow به شما امکان می‌دهد تا تصاویری را باز کنید، ویرایش کنید، ذخیره کنید و تبدیل‌های مختلفی روی آن‌ها انجام دهید.

- [**scikit-image**](https://github.com/scikit-image/scikit-image) - یک کتابخانه برای پردازش تصاویر در پایتون که بر پایه SciPy ساخته شده است. این کتابخانه شامل توابع متنوع برای فیلترگذاری، تبدیل‌های هندسی، پردازش تصاویر رنگی و تحلیل ویژگی‌های تصاویر است.

- [**imageio**](https://github.com/imageio/imageio) - یک کتابخانه ساده و سریع برای خواندن و نوشتن تصاویر و ویدیوها به فرمت‌های مختلف. این کتابخانه برای خواندن و ذخیره تصاویر و ویدیوها به صورت چندرسانه‌ای طراحی شده است.

- [**pyTorch**](https://github.com/pytorch/pytorch) - پلتفرم محبوب برای یادگیری ماشین که قابلیت‌های زیادی برای پردازش تصاویر با استفاده از شبکه‌های عصبی عمیق (CNNs) دارد. PyTorch برای انجام وظایف پیچیده پردازش تصویر مثل شناسایی اشیاء و دسته‌بندی تصاویر بسیار مفید است.

---
### هک و امنیت  
کتابخانه‌هایی برای کار با امنیت سیستم‌ها، شبیه‌سازی حملات، انجام تست‌های نفوذ و تحلیل آسیب‌پذیری‌ها.

- [**Scapy**](https://github.com/secdev/scapy) - یک ابزار قدرتمند برای پردازش بسته‌های شبکه و انجام تست‌های نفوذ. این کتابخانه به شما این امکان را می‌دهد که بسته‌های شبکه را دستکاری کنید، آنها را ارسال کنید و پاسخ‌ها را تجزیه و تحلیل کنید. Scapy برای کار با پروتکل‌های شبکه و تست آسیب‌پذیری‌های شبکه بسیار مفید است.

- [**Requests**](https://github.com/psf/requests) - یک کتابخانه ساده برای ارسال درخواست‌های HTTP. این کتابخانه به طور گسترده‌ای در تست‌های امنیتی، به ویژه در زمینه آسیب‌پذیری‌های مربوط به وب، مورد استفاده قرار می‌گیرد. شما می‌توانید از Requests برای ارسال درخواست‌های HTTP به وب‌سایت‌ها و شبیه‌سازی حملات مثل XSS و CSRF استفاده کنید.

- [**Paramiko**](https://github.com/paramiko/paramiko) - یک کتابخانه برای پیاده‌سازی SSH در پایتون. Paramiko به شما این امکان را می‌دهد که ارتباطات SSH را برقرار کرده و از آن برای مدیریت سیستم‌ها به صورت از راه دور استفاده کنید. این کتابخانه به طور ویژه در تست‌های نفوذ از راه دور کاربرد دارد.

- [**pwntools**](https://github.com/Gallopsled/pwntools) - کتابخانه‌ای برای نوشتن اسکریپت‌های پایتون جهت کار با برنامه‌های آسیب‌پذیر در هک و امنیت. pwntools ابزارهای مفیدی برای کار با بافرها، رمزگذاری‌ها، و فرایندهای ارتباطی بین برنامه‌ها فراهم می‌کند و به ویژه در زمینه تست نفوذ و تحلیل آسیب‌پذیری‌ها کاربرد دارد.

- [**hashlib**](https://github.com/python/cpython/tree/main/Lib/hashlib) - کتابخانه‌ای برای انجام عملیات رمزنگاری هش. hashlib به شما این امکان را می‌دهد که هش‌های مختلفی مانند MD5، SHA-1 و SHA-256 را تولید کرده و از آنها در آزمایش‌ها و بررسی‌های امنیتی استفاده کنید.
---
### وب اسکرپینگ
کتابخانه‌هایی برای استخراج داده‌ها از وب‌سایت‌ها و پردازش آن‌ها.

- [**BeautifulSoup**](https://github.com/wention/BeautifulSoup4) - یک کتابخانه ساده برای پردازش HTML و XML. BeautifulSoup به شما کمک می‌کند تا داده‌های مورد نظر خود را از صفحات وب استخراج کنید. این کتابخانه یکی از محبوب‌ترین ابزارها در وب اسکرپینگ است.

- [**Scrapy**](https://github.com/scrapy/scrapy) - یک فریم‌ورک کامل برای وب اسکرپینگ و استخراج داده از وب‌سایت‌ها. Scrapy می‌تواند درخواست‌های HTTP ارسال کند، داده‌ها را پردازش کرده و نتایج را ذخیره کند. این ابزار برای پروژه‌های بزرگ وب اسکرپینگ بسیار مفید است.

- [**Selenium**](https://github.com/SeleniumHQ/selenium) - کتابخانه‌ای برای کنترل مرورگرهای وب. Selenium به شما این امکان را می‌دهد که مرورگرهای وب را به طور خودکار کنترل کنید، صفحات را بارگذاری کرده و داده‌ها را از آن‌ها استخراج کنید. این ابزار معمولاً در وب اسکرپینگ سایت‌هایی که جاوااسکریپت سنگین دارند، استفاده می‌شود.

- [**requests**](https://github.com/psf/requests) - کتابخانه‌ای برای ارسال درخواست‌های HTTP به وب‌سایت‌ها و دریافت پاسخ‌ها. شما می‌توانید با استفاده از این کتابخانه داده‌ها را از APIها یا صفحات HTML دریافت کنید و برای پردازش بیشتر از کتابخانه‌های دیگر استفاده کنید.

- [**lxml**](https://github.com/lxml/lxml) - کتابخانه‌ای برای پردازش و تجزیه فایل‌های XML و HTML. lxml عملکرد بسیار بالایی دارد و برای پروژه‌های بزرگ و پیچیده وب اسکرپینگ مناسب است.

- [**PyQuery**](https://github.com/gawel/pyquery) - یک کتابخانه مشابه jQuery برای پایتون که به شما امکان می‌دهد به راحتی به محتوای HTML صفحات دسترسی پیدا کرده و آن را پردازش کنید.

- [**Puppeteer**](https://github.com/puppeteer/puppeteer) - یک ابزار برای کنترل مرورگر Chrome یا Chromium از طریق پایتون. Puppeteer به شما این امکان را می‌دهد که به طور خودکار صفحات وب را بارگذاری کرده و داده‌ها را استخراج کنید. این ابزار به ویژه در استخراج داده از صفحات جاوااسکریپت‌دار مفید است.

- [**Newspaper3k**](https://github.com/codelucas/newspaper) - یک کتابخانه برای استخراج مقالات خبری از وب‌سایت‌ها. این کتابخانه به طور خودکار بخش‌های مختلف یک مقاله را استخراج کرده و آن را برای پردازش بیشتر آماده می‌کند.

- [**Grab**](https://github.com/lorien/grab) - یک فریم‌ورک برای وب اسکرپینگ که از درخواست‌های HTTP، کشف لینک‌ها، ذخیره داده‌ها و انجام وظایف پیچیده‌تری پشتیبانی می‌کند. Grab برای پروژه‌های پیچیده‌تر وب اسکرپینگ بسیار مفید است.

- [**pyppeteer**](https://github.com/miyakogi/pyppeteer) - نسخه پایتونی Puppeteer برای کنترل مرورگر Chromium و استخراج داده‌ها از صفحات وب. این کتابخانه به شما این امکان را می‌دهد که از JavaScript-heavy صفحات وب داده‌ها را استخراج کنید.

---
### کار با اکسل
کتابخانه‌هایی برای کار با فایل‌های Excel و انجام پردازش‌های مختلف روی داده‌ها.

- [**openpyxl**](https://github.com/openpyxl/openpyxl) - یک کتابخانه برای خواندن و نوشتن فایل‌های Excel در فرمت `.xlsx`. این کتابخانه امکانات زیادی برای کار با داده‌ها، فرمت‌دهی، و ساخت نمودارها در Excel فراهم می‌آورد.

- [**pandas**](https://github.com/pandas-dev/pandas) - یکی از کتابخانه‌های محبوب برای تحلیل داده‌ها که قابلیت کار با فایل‌های Excel را نیز دارد. شما می‌توانید به راحتی داده‌ها را از فایل‌های Excel بارگذاری کرده و آن‌ها را پردازش و تحلیل کنید.

- [**xlrd**](https://github.com/python-excel/xlrd) - کتابخانه‌ای برای خواندن فایل‌های Excel در فرمت‌های `.xls` و `.xlsx`. این کتابخانه بیشتر برای خواندن داده‌ها از فایل‌های Excel قدیمی استفاده می‌شود.

- [**xlwt**](https://github.com/python-excel/xlwt) - کتابخانه‌ای برای نوشتن داده‌ها به فایل‌های Excel با فرمت `.xls`. برای ذخیره‌سازی داده‌ها در قالب Excel از این کتابخانه می‌توانید استفاده کنید.

- [**pyexcel**](https://github.com/pyexcel/pyexcel) - یک کتابخانه کوچک و ساده برای کار با داده‌ها در فرمت‌های مختلف Excel. این کتابخانه کار با Excel را ساده‌تر می‌کند و به شما این امکان را می‌دهد که داده‌ها را به راحتی بارگذاری و ذخیره کنید.

- [**xlsxwriter**](https://github.com/jmcnamara/XlsxWriter) - کتابخانه‌ای برای نوشتن داده‌ها به فایل‌های Excel در فرمت `.xlsx`. این کتابخانه امکانات پیشرفته‌ای برای فرمت‌دهی داده‌ها و ایجاد نمودارها و جداول پیچیده در Excel فراهم می‌کند.

- [**pyxlsb**](https://github.com/jeremydmiller/pyxlsb) - کتابخانه‌ای برای خواندن فایل‌های Excel در فرمت `.xlsb` (فرمت باینری Excel). این کتابخانه به شما این امکان را می‌دهد که داده‌ها را از فایل‌های Excel باینری بارگذاری کنید.

- [**openpyxl-styles**](https://github.com/lord63/openpyxl-styles) - یک کتابخانه کمکی برای افزودن استایل‌ها به سلول‌ها در فایل‌های Excel با استفاده از کتابخانه `openpyxl`. این ابزار می‌تواند برای فرمت‌دهی سریع فایل‌های Excel مفید باشد.

- [**excalibur-py**](https://github.com/codelucas/excalibur-py) - کتابخانه‌ای برای استخراج داده‌ها از فایل‌های PDF و تبدیل آن‌ها به فرمت‌های Excel. این کتابخانه می‌تواند برای پردازش داده‌های PDF و تبدیل آن‌ها به فرمت‌های قابل ویرایش بسیار مفید باشد.

---
### کار با پی‌دی‌اف
کتابخانه‌هایی برای کار با فایل‌های PDF، شامل استخراج داده‌ها، ویرایش، و تبدیل آن‌ها به فرمت‌های مختلف.

- [**PyPDF2**](https://github.com/mstamy2/PyPDF2) - یک کتابخانه محبوب برای پردازش فایل‌های PDF که قابلیت‌هایی مانند تقسیم، ادغام، رمزگذاری و استخراج متن از PDF‌ها را فراهم می‌کند.

- [**pdfminer**](https://github.com/euske/pdfminer) - یک ابزار بسیار قدرتمند برای استخراج متن و اطلاعات ساختاری از فایل‌های PDF. این کتابخانه می‌تواند به شما کمک کند تا از محتوای PDF داده‌هایی استخراج کنید که به صورت متنی یا حتی جدول باشند.

- [**pdfrw**](https://github.com/pmaupin/pdfrw) - کتابخانه‌ای برای خواندن و نوشتن فایل‌های PDF. این کتابخانه به شما این امکان را می‌دهد که صفحات PDF را ویرایش کنید، تصاویر را استخراج کنید و PDF جدید بسازید.

- [**PyMuPDF**](https://github.com/pymupdf/PyMuPDF) - یک کتابخانه سریع و کارآمد برای پردازش فایل‌های PDF و سایر فرمت‌های مستندات. PyMuPDF به شما امکان می‌دهد که به راحتی متن، تصاویر، و متاداده‌ها را از فایل‌های PDF استخراج کرده و فایل‌های PDF را ویرایش کنید.

- [**pdfkit**](https://github.com/JazzCore/python-pdfkit) - کتابخانه‌ای برای تبدیل HTML به PDF با استفاده از ابزار wkhtmltopdf. این کتابخانه به شما کمک می‌کند تا محتوای HTML خود را به یک فایل PDF تبدیل کنید.

- [**reportlab**](https://github.com/rrdtech/reportlab) - یک کتابخانه قدرتمند برای ساخت و تولید فایل‌های PDF با استفاده از کد پایتون. شما می‌توانید با استفاده از این کتابخانه PDF‌هایی با گرافیک، نمودارها و جداول پیچیده بسازید.

- [**PyPDF4**](https://github.com/claird/PyPDF4) - یک نسخه به‌روزرسانی شده از PyPDF2 که شامل اصلاحات و بهبودهای بیشتری است. PyPDF4 نیز به شما این امکان را می‌دهد که فایل‌های PDF را ترکیب و تقسیم کرده و متنی از آن‌ها استخراج کنید.

- [**fitz**](https://github.com/pymupdf/pymupdf) - ابزار کمکی برای پردازش PDF‌ها که بر پایه PyMuPDF است و به شما این امکان را می‌دهد تا به سادگی فایل‌های PDF را باز کرده، ویرایش کنید و محتوای آن‌ها را استخراج نمایید.

- [**Slate**](https://github.com/timClicks/slate) - یک کتابخانه ساده برای استخراج متن از فایل‌های PDF. Slate به شما این امکان را می‌دهد که محتوای PDF را به شکل ساده و متن‌محور استخراج کنید.
---


## ✍️ مشارکت در پروژه

اگه کتابخونه یا ابزاری سراغ داری که جاش اینجا خالیه، حتماً یه Pull Request بزن یا Issue ثبت کن.  
هر کمکی به بهتر شدن این لیست باعث میشه جامعه‌ی پایتون فارسی رشد کنه 🙌

---

## ☕ حمایت

اگر از این پروژه خوشت اومده، می‌تونی با ستاره دادن ⭐، اشتراک‌گذاری 💬، یا مشارکت مستقیم ⌨️ ازش حمایت کنی.
---

## ☕ از این ریپازیتوری خوشتون اومد؟ برام یه کافی بخر!

اگر این پروژه به شما کمک کرده و مفید واقع شده، خوشحال می‌شم که با خرید یک فنجان قهوه از من حمایت کنید! این کمک به من انگیزه می‌ده تا پروژه‌های بیشتری بسازم و منابع مفیدتری به اشتراک بذارم.

👉 [برام یه کافی بخر!](https://www.coffeebede.com/mrrobat)

از حمایت شما بی‌نهایت سپاسگزارم! 😊

---

## 🧑‍💻 لایسنس

این پروژه تحت لایسنس [MIT](./LICENSE) منتشر شده.
