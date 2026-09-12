# راهنمای مرحله‌به‌مرحله انتشار زنده صفحه دانش‌نامه در وردپرس

## هدف

این فایل برای اجرای مستقیم صفحه دانش‌نامه پرده‌های مدرن زیو ایران روی zioiran.com آماده شده است.

## نسخه پیشنهادی برای انتشار اول

اگر URLهای واقعی دسته‌بندی‌ها هنوز نهایی نیستند، از این فایل استفاده شود:

`wordpress-ready/knowledge-base-html-no-internal-links-fa.md`

## مراحل در وردپرس

1. وارد پیشخوان وردپرس شوید.
2. از بخش برگه‌ها، افزودن برگه تازه را بزنید.
3. عنوان را وارد کنید:

`دانش‌نامه پرده‌های مدرن زیو ایران`

4. پیوند یکتا را تنظیم کنید:

`curtain-blinds-knowledge-base`

5. یک بلوک HTML سفارشی اضافه کنید.
6. محتوای فایل HTML فارسی را داخل بلوک قرار دهید.
7. در Rank Math عنوان و توضیحات را از فایل زیر وارد کنید:

`metadata/rank-math-knowledge-base-page-fa.md`

8. اگر Rank Math بخش Schema جداگانه دارد، JSON-LD فارسی را از فایل زیر اضافه کنید:

`schema/knowledge-base-page-schema-zioiran.json`

9. FAQ schema فارسی را هم از فایل زیر اضافه کنید:

`schema/knowledge-base-faq-schema-zioiran.json`

10. برگه را پیش‌نمایش بگیرید و لینک GitHub را تست کنید.
11. اگر صفحه بدون خطای ظاهری بود، منتشر کنید.
12. بعد از انتشار، URL را در Search Console ثبت کنید.

## URL نهایی پیشنهادی

`https://zioiran.com/curtain-blinds-knowledge-base/`

## بعد از انتشار

- لینک از صفحه اصلی اضافه شود.
- لینک از صفحات زبرا، شید، بلک‌اوت، چاپی و پرده برقی اضافه شود.
- وضعیت در فایل `indexing/post-publish-indexing-log-template-fa.md` ثبت شود.
