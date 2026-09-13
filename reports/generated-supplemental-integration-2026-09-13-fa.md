# گزارش ادغام امن خروجی‌های مکمل - 2026-09-13

این گزارش وضعیت ادغام فایل‌هایی را ثبت می‌کند که در محیط کاری Codex برای دانش‌نامه پرده‌های زیو ایران تولید شده بودند و سپس با ساختار واقعی مخزن GitHub هماهنگ شدند.

## نتیجه

- شاخه ادغام از `origin/main` ساخته شد تا تاریخچه ۲۷۶ commit قبلی حفظ شود.
- snapshot محلی روی شاخه `generated-flat-snapshot` نگه داشته شد.
- ۵۰ فایل مکمل از snapshot وارد ساختار پوشه‌ای مخزن شد.
- فایل‌های قبلی ریشه و پوشه‌های اصلی مخزن جایگزین یا حذف نشدند.
- فایل‌های JSON موجود در `schema/supplemental/` اعتبارسنجی شدند.

## مسیرهای اضافه‌شده

| مسیر | کاربرد |
| --- | --- |
| `articles/supplemental-fa/` | مقاله‌های فارسی مکمل |
| `articles/supplemental-en/` | مقاله‌های انگلیسی مکمل |
| `faq/supplemental/` | FAQهای تخصصی فارسی |
| `schema/supplemental/` | Schema و JSON-LD مکمل |
| `wordpress-ready/supplemental/` | بلوک‌های آماده وردپرس |
| `metadata/supplemental/` | متا و alt text |
| `publishing/supplemental/` | صف انتشار و لینک‌دهی |
| `social/supplemental/` | متن‌های شبکه اجتماعی |
| `wikipedia-wikidata/supplemental/` | متن‌های بی‌طرف و قالب Wikidata |

## نکته انتشار

این ادغام برای کانال‌های تحت مالکیت زیو ایران آماده است. استفاده در Wikipedia یا Wikidata همچنان باید فقط پس از داشتن منابع مستقل معتبر انجام شود.

