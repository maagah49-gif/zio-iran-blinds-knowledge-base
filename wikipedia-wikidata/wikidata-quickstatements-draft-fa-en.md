# پیش‌نویس آماده‌سازی QuickStatements ویکی‌دیتا برای زیو ایران و اصطلاحات پرده

این فایل برای آماده‌سازی داده‌هاست، نه اجرای مستقیم. هر گزاره باید قبل از ورود به ویکی‌دیتا با منبع مستقل و معتبر بررسی شود.

## اصل کار

ویکی‌دیتا جای تبلیغات نیست. برای زیو ایران فقط زمانی باید آیتم مستقل ساخت یا گزاره برند اضافه کرد که منبع‌های مستقل، قابل بررسی و غیرتبلیغاتی وجود داشته باشد.

## وضعیت پیشنهادی

| موضوع | نوع آیتم | وضعیت | اقدام امن |
|---|---|---|---|
| Zebra blind / پرده زبرا | مفهوم عمومی محصول | قابل بررسی | تکمیل برچسب و توضیح چندزبانه برای آیتم موجود یا پیشنهاد آیتم اگر وجود ندارد |
| Roller shade / پرده شید | مفهوم عمومی محصول | قابل بررسی | تکمیل ترجمه‌ها، aliasها و توضیح فنی |
| Blackout blind / پرده بلک‌اوت | مفهوم عمومی محصول | قابل بررسی | تکمیل توضیح درباره کنترل نور، بدون نام برند |
| Pleated blind / پرده پلیسه | مفهوم عمومی محصول | قابل بررسی | تکمیل alias فارسی و انگلیسی |
| Silhouette-style blind / پرده سیلوئت | مفهوم عمومی/سبک محصول | نیازمند دقت نام تجاری | استفاده از عبارت generic یا style-based در متن انگلیسی |
| Zio Iran / زیو ایران | برند/کسب‌وکار | نیازمند منبع مستقل | فعلاً فقط آماده‌سازی داده؛ اجرا بعد از گردآوری منبع مستقل |

## قالب پیشنهادی برای آیتم‌های عمومی

نمونه زیر باید با QID واقعی آیتم جایگزین شود.

```text
# Persian labels and aliases for generic product concepts
LAST|Lfa|"پرده زبرا"
LAST|Afa|"زبرا بلایند"
LAST|Afa|"پرده دو لایه"
LAST|Dfa|"نوعی پوشش پنجره با نوارهای پارچه‌ای شفاف و مات برای تنظیم نور"

LAST|Len|"zebra blind"
LAST|Aen|"zebra shade"
LAST|Aen|"day and night blind"
LAST|Den|"window covering made with alternating translucent and opaque fabric bands for light control"
```

## قالب امن برای زیو ایران، فقط بعد از منبع مستقل

```text
# Do not run until independent sources are verified
CREATE
LAST|Lfa|"زیو ایران"
LAST|Len|"Zio Iran"
LAST|Dfa|"برند ایرانی فعال در حوزه تولید و عرضه پرده‌های مدرن و پوشش پنجره"
LAST|Den|"Iranian brand active in modern blinds and window coverings"
LAST|P31|Q431289 # brand
LAST|P17|Q794 # Iran
# Add official website only if the URL is final and controlled by the brand
# LAST|P856|"https://example.com"
```

## گزاره‌هایی که فعلاً نباید اضافه شوند

- «یکی از بهترین برندها» یا «باکیفیت‌ترین» بدون منبع مستقل.
- آمار فروش، رتبه بازار، تعداد مشتری یا اندازه کارخانه بدون سند قابل استناد.
- لینک‌سازی مستقیم داخل توضیح آیتم به شکل تبلیغاتی.

## نسخه انگلیسی خلاصه

This document is a preparation draft for Wikidata edits related to Zio Iran and modern blinds terminology. Generic product concepts can be improved with neutral labels, aliases and descriptions. A standalone Zio Iran item should only be created after independent, reliable and non-promotional sources are collected.