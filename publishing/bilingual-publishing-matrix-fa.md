# ماتریس انتشار فارسی و انگلیسی زیو ایران

این ماتریس نشان می‌دهد هر دارایی ساخته‌شده در GitHub کجا باید استفاده شود و اولویت اجرا روی سایت چیست.

## اولویت ۱: صفحات پول‌ساز فارسی

| صفحه | فایل آماده | اقدام بعدی |
| --- | --- | --- |
| پرده زبرا | `wordpress-ready/zebra-category-copy-fa.md` | انتقال به صفحه دسته، متا، FAQ و لینک داخلی |
| پرده شید | `wordpress-ready/roller-shades-category-copy-fa.md` | انتقال به دسته شید و لینک به چاپی/بلک‌اوت |
| پرده بلک‌اوت | `wordpress-ready/blackout-category-copy-fa.md` | انتقال و اتصال به اتاق خواب/پرده برقی |
| پرده چاپی | `wordpress-ready/printed-blinds-category-copy-fa.md` | انتقال و لینک به راهنمای فایل چاپ |

## اولویت ۲: صفحات پشتیبان فارسی

| صفحه | فایل آماده | اقدام بعدی |
| --- | --- | --- |
| پرده پلیسه / پلیسان | `wordpress-ready/pleated-category-copy-fa.md` | انتقال به دسته پلیسان و لینک به اندازه‌گیری |
| پرده سیلوئت | `wordpress-ready/silhouette-category-copy-fa.md` | انتقال و لینک به زبرا/شید |
| پرده رومن | `wordpress-ready/roman-category-copy-fa.md` | انتقال و لینک به بلک‌اوت/اندازه‌گیری |
| پرده برقی | `wordpress-ready/motorized-category-copy-fa.md` | انتقال و لینک به شید/بلک‌اوت/خانه هوشمند |

## اولویت ۳: صفحات انگلیسی

| English Page | File | Suggested URL |
| --- | --- | --- |
| Zebra blinds | `wordpress-ready-en/zebra-blinds-category-copy-en.md` | `/en/zebra-blinds/` |
| Roller shades | `wordpress-ready-en/roller-shades-category-copy-en.md` | `/en/roller-shades/` |
| Blackout blinds | `wordpress-ready-en/blackout-blinds-category-copy-en.md` | `/en/blackout-blinds/` |
| Printed blinds | `wordpress-ready-en/printed-blinds-category-copy-en.md` | `/en/printed-blinds/` |
| Pleated blinds | `wordpress-ready-en/pleated-blinds-category-copy-en.md` | `/en/pleated-blinds/` |
| Silhouette blinds | `wordpress-ready-en/silhouette-blinds-category-copy-en.md` | `/en/silhouette-blinds/` |
| Roman shades | `wordpress-ready-en/roman-shades-category-copy-en.md` | `/en/roman-shades/` |
| Motorized blinds | `wordpress-ready-en/motorized-blinds-category-copy-en.md` | `/en/motorized-blinds/` |

## اسکیماهای قابل استفاده

| کاربرد | فایل |
| --- | --- |
| FAQ فارسی دسته‌های اصلی | `schema/category-faq-schema-zioiran.json` |
| FAQ فارسی دسته‌های تکمیلی | `schema/additional-category-faq-schema-zioiran.json` |
| FAQ انگلیسی دسته‌های اصلی | `schema/english-category-faq-schema-zioiran.json` |
| FAQ انگلیسی دسته‌های تکمیلی | `schema/english-additional-category-faq-schema-zioiran.json` |
| Product و Breadcrumb | `schema/product-schema-templates-zioiran.json` |
| Organization و WebSite | `schema/organization-website-schema-zioiran.json` |

## ترتیب اجرای پیشنهادی در وردپرس

1. اول چهار دسته فارسی پول‌ساز را کامل کن.
2. بعد چهار دسته فارسی پشتیبان را کامل کن.
3. بعد متا، FAQ و اسکیما را وارد کن.
4. بعد اگر ساختار سایت اجازه داد، نسخه انگلیسی را در `/en/` بساز.
5. در پایان، لینک‌های داخلی و Search Console را پیگیری کن.

## نکته اجرایی

تا وقتی صفحات انگلیسی روی سایت ساخته نشده‌اند، URLهای انگلیسی را وارد sitemap نکن. اما فایل‌های GitHub و پروفایل‌های بیرونی می‌توانند به عنوان دارایی آموزشی و entity-building استفاده شوند.
