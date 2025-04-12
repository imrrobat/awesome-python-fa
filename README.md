# 🐍 پایتون شگفت‌انگیز – مجموعه‌ای از ابزارها و کتابخانه‌های کاربردی پایتون

> نسخه‌ی فارسی ریپازیتوری محبوب [awesome-python](https://github.com/vinta/awesome-python) برای فارسی‌زبانان

---

## 📝 مقدمه

پایتون یکی از زبان‌های برنامه‌نویسی محبوب و پرکاربرد در دنیاست. از ساخت وب‌سایت گرفته تا تحلیل داده، یادگیری ماشین، اتوماسیون، و حتی ساخت بازی، پایتون حرف‌های زیادی برای گفتن داره.

این ریپازیتوری یک لیست دسته‌بندی‌شده از بهترین و کاربردی‌ترین کتابخانه‌ها و ابزارهای پایتون به زبان فارسیه. هدف اینه که برنامه‌نویس‌های فارسی‌زبان راحت‌تر بتونن ابزار مناسب کارشون رو پیدا کنن و وارد دنیای اوپن‌سورس بشن.

---

## 📚 فهرست

- [وب و توسعه وب](#وب-و-توسعه-وب)
- [تحلیل داده](#تحلیل-داده)
- [یادگیری ماشین](#یادگیری-ماشین)
- [تست و دیباگ](#تست-و-دیباگ)
- [ابزارهای خط فرمان](#ابزارهای-خط-فرمان)
- [هوش مصنوعی و nlp](#هوش-مصنوعی-و-nlp)
- [سایر دسته‌ها](#سایر-دسته‌ها)


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

## 🤖 یادگیری ماشین

*(در حال نگارش...)*

---

## 🧪 تست و دیباگ

*(در حال نگارش...)*

---

## 💻 ابزارهای خط فرمان

*(در حال نگارش...)*

---

## 🧠 هوش مصنوعی و NLP

*(در حال نگارش...)*

---

## 🧰 سایر دسته‌ها

*(در حال نگارش...)*

---

## ✍️ مشارکت در پروژه

اگه کتابخونه یا ابزاری سراغ داری که جاش اینجا خالیه، حتماً یه Pull Request بزن یا Issue ثبت کن.  
هر کمکی به بهتر شدن این لیست باعث میشه جامعه‌ی پایتون فارسی رشد کنه 🙌

---

## ☕ حمایت

اگر از این پروژه خوشت اومده، می‌تونی با ستاره دادن ⭐، اشتراک‌گذاری 💬، یا مشارکت مستقیم ⌨️ ازش حمایت کنی.

---

## 🧑‍💻 لایسنس

این پروژه تحت لایسنس [MIT](./LICENSE) منتشر شده.
