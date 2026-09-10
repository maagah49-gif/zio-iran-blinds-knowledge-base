# گزارش بسته ایندکس و کنترل لینک - 2026-09-10

این مرحله برای بعد از اجرای لینک‌دهی سایت به GitHub آماده شد. هدف، این است که بعد از انتشار صفحه یا بلوک دانش‌نامه در `zioiran.com`، بدانیم چه URLهایی باید بررسی شوند و کیفیت لینک چطور کنترل شود.

## فایل‌های ساخته‌شده

| فایل | کاربرد |
|---|---|
| `indexing/github-knowledge-base-url-submission-fa.md` | فهرست URLهای مهم GitHub برای بررسی ایندکس و discovery |
| `qa/site-github-link-verification-checklist-fa.md` | چک‌لیست فنی و محتوایی کنترل لینک سایت به GitHub |

## نکته مهم درباره Search Console

چون repository روی دامنه `github.com` است، نمی‌توان URLهای GitHub را مثل URLهای سایت خودمان مستقیماً در Search Console دامنه زیو submit کرد. مسیر عملی‌تر این است:

1. صفحه `zioiran.com/knowledge-base/` یا صفحه درباره ما را در سایت منتشر کنیم.
2. داخل آن صفحه به GitHub knowledge base لینک بدهیم.
3. همان URL سایت را در Search Console inspect و request indexing کنیم.
4. بعداً با جستجوی `site:github.com/maagah49-gif/zio-iran-blinds-knowledge-base Zio Iran` وضعیت دیده شدن GitHub را بررسی کنیم.

## اولویت URLهای سایت برای Inspect

| URL پیشنهادی | اولویت |
|---|---:|
| `https://zioiran.com/knowledge-base/` | خیلی بالا |
| `https://zioiran.com/about/` یا صفحه درباره ما | بالا |
| صفحه پرده زبرا | بالا |
| صفحه پرده شید | بالا |
| صفحه بلک‌اوت | متوسط |

## خروجی مورد انتظار

بعد از اجرای این مرحله، ارتباط بین سایت رسمی زیو ایران و دانش‌نامه GitHub از نظر کاربر، گوگل و موتورهای پاسخ‌گو واضح‌تر می‌شود.