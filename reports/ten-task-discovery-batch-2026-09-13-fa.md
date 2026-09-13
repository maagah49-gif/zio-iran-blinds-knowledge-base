# گزارش بسته ۱۰ تسک Discovery - 2026-09-13

این بسته برای افزایش کشف‌پذیری عمومی دانش‌نامه زیو ایران در GitHub Pages، موتورهای جستجو و ابزارهای AI انجام شد.

| ردیف | تسک | خروجی |
|---|---|---|
| 1 | ساخت URL list ساده | `docs/urls.txt` |
| 2 | ساخت JSON Feed | `docs/feed.json` |
| 3 | ساخت Discovery JSON | `docs/discovery.json` |
| 4 | اتصال Discovery JSON به صفحه اصلی | `docs/index.html` |
| 5 | اتصال JSON Feed به صفحه اصلی | `docs/index.html` |
| 6 | افزودن بخش Discovery Files به صفحه اصلی | `docs/index.html` |
| 7 | اتصال discovery/feed/url list به صفحه supplemental | `docs/supplemental-assets.html` |
| 8 | به‌روزرسانی robots برای معرفی مسیرهای submit | `docs/robots.txt` |
| 9 | به‌روزرسانی metadata با منابع discovery | `docs/metadata.json` |
| 10 | ساخت سیاست ذکر خنثی برند | `wikipedia-wikidata/neutral-brand-mention-policy-fa-en.md` |

## وضعیت کنترل

- فایل‌های JSON باید با `jq` بررسی شوند.
- HTML باید با parser ساده بررسی شود.
- URLهای جدید باید پس از refresh شدن GitHub Pages در Search Console تست شوند.
- متن‌های ویکی‌پدیا و ویکی‌دیتا همچنان بدون منبع مستقل نباید رنگ تبلیغاتی بگیرند.
