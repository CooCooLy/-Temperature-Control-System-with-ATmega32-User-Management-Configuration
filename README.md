پروژه کنترل دما با ATmega32


این پروژه طراحی و پیاده‌سازی سیستمی است که با استفاده از میکروکنترلر ATmega32، امکان کنترل دما، مدیریت کاربران، و تنظیمات مختلفی را فراهم می‌کند. هدف از این پروژه، ارائه سیستمی هوشمند و انعطاف‌پذیر برای مدیریت دما در محیط‌های مختلف است.

تجهیزات و ابزارهای مورد استفاده
سخت‌افزار:
میکروکنترلر ATmega32
سنسور دما
LCD کاراکتری
کیبورد ماتریسی
حافظه EEPROM مدل AT24512
فن و هیتر (در صورت نیاز)
نرم‌افزار:
CodeVision AVR برای برنامه‌نویسی
پروتئوس برای شبیه‌سازی

شرح عملکرد پروژه
ورود به سیستم:
پروژه دارای دو نوع کاربر است:

کاربر عادی با رمز عبور مشخص
کاربر سازنده (Admin) با رمز عبور ویژه
در صورت ورود صحیح، پیام‌های مناسب مانند "Correct User Logged in" یا "Admin Logged in" روی LCD نمایش داده می‌شود.
نمایش اطلاعات:
پس از ورود کاربر، اطلاعات زیر روی LCD نشان داده می‌شود:

دمای محیط (فعلی، حداقل و حداکثر)
تنظیمات ساعت و دما
تنظیمات منو:

تنظیم ساعت: با فشردن کلید 1، وارد منوی تنظیم ساعت می‌شوید.
تنظیم دما: با فشردن کلید 2، وارد منوی تنظیم دما شده و دمای موردنظر را با استفاده از کیبورد وارد می‌کنید.
مدیریت کاربران:

در بخش Add User، کاربر جدیدی را با رمز عبور دلخواه تعریف می‌کنید. اطلاعات در حافظه EEPROM ذخیره می‌شود.
تنظیمات پیشرفته:
در منوی Temp Config، امکان تغییر سنسور دما یا تنظیمات آن فراهم است. اطلاعات مربوط به دما روی LCD نمایش داده می‌شود.



نحوه راه‌اندازی و استفاده
اتصال سخت‌افزار طبق شماتیک مدار.
برنامه‌ریزی میکروکنترلر با استفاده از CodeVision AVR.
تست و اجرای پروژه با بررسی خروجی روی LCD و عملکرد صحیح سخت‌افزار.
