# Robots.txt and Sitemap Guidance for Zio Iran

این فایل برای کنترل ایندکس صفحات اصلی zioiran.com و جلوگیری از رقابت یا ایندکس اشتباه آماده شده است.

## اصل مهم

دامنه اصلی برای رشد سئو باید `https://zioiran.com` باشد. اگر `zioiran.ir` نسخه کپی یا مکمل است، باید مراقب باشیم محتوای مشابه آن با دامنه اصلی رقابت نکند.

## پیشنهاد برای zioiran.com

- صفحات محصول و دسته‌های اصلی باید index باشند.
- مقالات آموزشی باید index باشند.
- صفحات جستجوی داخلی، سبد خرید، حساب کاربری و checkout نباید در نتایج جستجو هدف‌گذاری شوند.
- sitemap باید شامل URLهای اصلی و canonical باشد.

## نمونه robots.txt پیشنهادی

```txt
User-agent: *
Disallow: /wp-admin/
Disallow: /cart/
Disallow: /checkout/
Disallow: /my-account/
Disallow: /?s=
Allow: /wp-admin/admin-ajax.php

Sitemap: https://zioiran.com/sitemap_index.xml
```

## بررسی sitemap

| مورد | وضعیت مطلوب |
|---|---|
| صفحه اصلی | داخل sitemap باشد |
| دسته‌های محصول | داخل sitemap باشند |
| محصولات قابل فروش | داخل sitemap باشند |
| مقالات بلاگ | داخل sitemap باشند |
| صفحات noindex | داخل sitemap نباشند |
| URLهای پارامتردار | داخل sitemap نباشند |
| zioiran.ir کپی | با canonical یا noindex مدیریت شود |

## Canonical

برای صفحه‌های اصلی سایت، canonical باید به همان URL اصلی در `zioiran.com` اشاره کند. اگر صفحه مشابهی در `zioiran.ir` وجود دارد، باید بررسی شود که canonical یا noindex باعث رقابت داخلی نشود.

## صفحات پیشنهادی برای index

- صفحه اصلی
- پرده زبرا
- پرده شید
- پرده بلک‌اوت
- پرده چاپی
- پرده پلیسه / پلیسان
- پرده سیلوئت
- پرده رومن
- پرده ورتیکال
- پرده برقی
- راهنمای اندازه‌گیری
- مقالات آموزشی اصلی

## صفحات پیشنهادی برای noindex

- سبد خرید
- تسویه حساب
- حساب کاربری
- صفحه ورود
- نتایج جستجوی داخلی
- صفحات فیلترشده با پارامترهای تکراری
- صفحات تست یا پیش‌نمایش

## چک‌لیست بعد از تغییر

۱. robots.txt را در مرورگر باز کنید.

۲. sitemap را در Search Console بررسی کنید.

۳. یک URL دسته محصول را inspect کنید.

۴. یک URL بلاگ را inspect کنید.

۵. مطمئن شوید صفحات checkout و my-account ایندکس نمی‌شوند.
