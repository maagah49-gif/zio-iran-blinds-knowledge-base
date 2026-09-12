# راهنمای hreflang صفحه دانش‌نامه فارسی و انگلیسی

## هدف

این فایل برای زمانی است که نسخه فارسی و انگلیسی صفحه دانش‌نامه زیو ایران هر دو روی سایت فعال شده‌اند. تا وقتی نسخه انگلیسی منتشر نشده، hreflang نباید برای URL غیرواقعی فعال شود.

## URLهای پیشنهادی

| زبان | URL پیشنهادی | وضعیت |
|---|---|---|
| فارسی | `https://zioiran.com/curtain-blinds-knowledge-base/` | قابل انتشار |
| انگلیسی | `https://zioiran.com/en/modern-blinds-knowledge-base/` | بعد از فعال شدن بخش انگلیسی |

## نمونه تگ‌ها

```html
<link rel="alternate" hreflang="fa-IR" href="https://zioiran.com/curtain-blinds-knowledge-base/" />
<link rel="alternate" hreflang="en" href="https://zioiran.com/en/modern-blinds-knowledge-base/" />
<link rel="alternate" hreflang="x-default" href="https://zioiran.com/curtain-blinds-knowledge-base/" />
```

## قواعد اجرا

1. فقط URLهای واقعی و منتشرشده را در hreflang قرار بدهید.
2. هر صفحه باید به خودش و نسخه زبان دیگر اشاره کند.
3. canonical صفحه فارسی باید فارسی باشد و canonical صفحه انگلیسی باید انگلیسی باشد.
4. اگر سایت چندزبانه فعلاً غیرفعال است، فقط صفحه فارسی را index کنید و نسخه انگلیسی را نگه دارید.
5. بعد از انتشار نسخه انگلیسی، هر دو URL را در Search Console inspect کنید.

## کنترل بعد از انتشار

| مورد | نتیجه مطلوب |
|---|---|
| کد وضعیت صفحه فارسی | 200 |
| کد وضعیت صفحه انگلیسی | 200 |
| canonical فارسی | URL فارسی |
| canonical انگلیسی | URL انگلیسی |
| hreflang برگشتی | هر دو صفحه به هم اشاره کنند |
| sitemap | هر دو URL داخل sitemap باشند |
