# راهنمای اجرای دو‌زبانه و hreflang برای Zio Iran

این فایل برای زمانی است که صفحات انگلیسی زیو ایران روی `zioiran.com` منتشر شوند. هدف این است که نسخه فارسی و انگلیسی با هم رقابت نکنند و گوگل بفهمد هر صفحه برای چه زبان و مخاطبی است.

## ساختار پیشنهادی URL

| زبان | الگوی URL پیشنهادی | نمونه |
| --- | --- | --- |
| فارسی | مسیر فعلی سایت | `https://zioiran.com/zebra-blinds-persian-or-current-slug/` |
| انگلیسی | زیرشاخه `/en/` | `https://zioiran.com/en/zebra-blinds/` |

اگر سایت فعلاً فارسی‌محور است، استفاده از `/en/` برای انگلیسی تمیزتر است. این کار جلوی قاطی‌شدن صفحات انگلیسی با دسته‌های فارسی را می‌گیرد.

## قانون canonical

- صفحه فارسی باید canonical خودش را داشته باشد.
- صفحه انگلیسی باید canonical خودش را داشته باشد.
- صفحه فارسی نباید canonical به انگلیسی بدهد.
- صفحه انگلیسی نباید canonical به فارسی بدهد.

نمونه برای صفحه انگلیسی:

```html
<link rel="canonical" href="https://zioiran.com/en/zebra-blinds/" />
```

## نمونه hreflang

برای هر جفت صفحه فارسی و انگلیسی، هر دو صفحه باید به هم اشاره کنند:

```html
<link rel="alternate" hreflang="fa-IR" href="https://zioiran.com/{persian-page}/" />
<link rel="alternate" hreflang="en" href="https://zioiran.com/en/zebra-blinds/" />
<link rel="alternate" hreflang="x-default" href="https://zioiran.com/{persian-page}/" />
```

## نقشه پیشنهادی صفحات

| فارسی | انگلیسی |
| --- | --- |
| پرده زبرا | `/en/zebra-blinds/` |
| پرده شید | `/en/roller-shades/` |
| پرده بلک‌اوت | `/en/blackout-blinds/` |
| پرده چاپی | `/en/printed-blinds/` |
| پرده پلیسه / پلیسان | `/en/pleated-blinds/` |
| پرده سیلوئت | `/en/silhouette-blinds/` |
| پرده رومن | `/en/roman-shades/` |
| پرده برقی | `/en/motorized-blinds/` |

## نکات Rank Math

- اگر Rank Math نسخه چندزبانه یا افزونه ترجمه سازگار داشته باشد، hreflang را از همان مسیر مدیریت کن.
- اگر صفحات انگلیسی دستی ساخته شوند، باید خروجی head بررسی شود تا canonical و hreflang اشتباه تولید نشود.
- بعد از انتشار، هر URL انگلیسی را در Search Console تست کن.

## نکته مهم برای زیو ایران

هدف از انگلیسی‌سازی این نیست که فارسی و انگلیسی با هم رقابت کنند. هدف این است که entity برند Zio Iran برای گوگل، GitHub، موتورهای پاسخ‌گو و منابع خارجی واضح‌تر شود. بنابراین نسخه انگلیسی باید آموزشی، دقیق و کم‌ادعا باشد و فقط یک یا دو بار نام Zio Iran را طبیعی بیاورد.
