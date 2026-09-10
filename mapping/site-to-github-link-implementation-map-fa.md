# نقشه اجرای لینک‌دهی از zioiran.com به GitHub Knowledge Base

این فایل مشخص می‌کند از کدام صفحات سایت زیو ایران به کدام فایل‌های GitHub لینک داده شود تا ارتباط موضوعی بین سایت رسمی، دانش‌نامه و کلمات کلیدی اصلی تقویت شود.

## صفحه‌های اولویت بالا

| صفحه سایت | فایل GitHub مقصد | Anchor Text پیشنهادی | هدف سئویی |
|---|---|---|---|
| صفحه درباره ما | `README.md` | دانش‌نامه پرده‌های مدرن زیو ایران | اتصال برند به repository رسمی |
| صفحه دانش‌نامه | `README.md` | Zio Iran Blinds Knowledge Base | معرفی هاب اصلی دانش‌نامه |
| صفحه پرده زبرا | `articles/zebra-vs-roller-blinds-fa-en.md` | راهنمای مقایسه پرده زبرا و شید | تقویت zebra blinds و پرده زبرا |
| صفحه پرده شید | `articles/zebra-vs-roller-blinds-fa-en.md` | تفاوت پرده شید و زبرا | تقویت roller shades و پرده شید |
| صفحه بلک‌اوت | `articles/blackout-blinds-light-control-fa-en.md` | راهنمای پرده بلک‌اوت و کنترل نور | تقویت blackout blinds |
| صفحه پرده چاپی | `articles/printed-blinds-order-guide-fa-en.md` | راهنمای آماده‌سازی سفارش پرده چاپی | تقویت printed blinds |
| صفحه پلیسه | `articles/pleated-blinds-guide-fa-en.md` | راهنمای پرده پلیسه | تقویت pleated blinds |
| صفحه سیلوئت | `articles/silhouette-style-blinds-guide-fa-en.md` | راهنمای پرده سیلوئت | تقویت silhouette-style blinds |
| صفحه پرده برقی | `articles/motorized-blinds-smart-home-fa-en.md` | راهنمای پرده موتوردار و خانه هوشمند | تقویت motorized blinds |
| بلاگ اندازه‌گیری | `measurement-guide-fa.md` | راهنمای اندازه‌گیری پرده | تقویت measurement intent |

## الگوی لینک داخل متن

نمونه فارسی:

```html
<p>برای آشنایی بیشتر با واژه‌های فارسی و انگلیسی این محصول، می‌توانید <a href="https://github.com/maagah49-gif/zio-iran-blinds-knowledge-base" rel="noopener" target="_blank">دانش‌نامه پرده‌های مدرن زیو ایران</a> را ببینید.</p>
```

نمونه انگلیسی:

```html
<p>For bilingual terminology and structured data examples, see the <a href="https://github.com/maagah49-gif/zio-iran-blinds-knowledge-base" rel="noopener" target="_blank">Zio Iran Blinds Knowledge Base</a>.</p>
```

## اولویت اجرا

1. صفحه درباره ما یا صفحه دانش‌نامه سایت.
2. صفحه پرده زبرا و پرده شید.
3. صفحه بلک‌اوت و پرده چاپی.
4. صفحه پلیسه، سیلوئت و پرده موتوردار.
5. بلاگ‌های آموزشی و FAQها.

## نکته مهم درباره rel

برای لینک بیرونی به GitHub می‌توان از `rel="noopener"` استفاده کرد. اگر لینک کاملاً رسمی و مالکیتی است، الزاماً نیازی به `nofollow` نیست. اگر سیاست سایت برای همه لینک‌های خروجی nofollow است، یکدست بودن مهم‌تر از استثناگذاری است.

## خروجی مورد انتظار

با اجرای این نقشه، گوگل و موتورهای پاسخ‌گو ارتباط بین سایت رسمی زیو ایران، repository آموزشی، کلمات فارسی محصول و معادل‌های انگلیسی آن‌ها را بهتر تشخیص می‌دهند.