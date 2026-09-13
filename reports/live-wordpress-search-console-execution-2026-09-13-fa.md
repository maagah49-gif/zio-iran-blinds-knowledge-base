# گزارش اجرای زنده وردپرس و Search Console - 2026-09-13

## کارهای انجام‌شده

| ردیف | کار | نتیجه |
|---|---|---|
| 1 | بررسی صفحه دانش‌نامه فارسی روی سایت | URL اصلی `https://zioiran.com/curtain-blinds-knowledge-base/` زنده و قابل مشاهده است. |
| 2 | بررسی نسخه تکراری | URL تکراری `https://zioiran.com/curtain-blinds-knowledge-base-2/` هم زنده است و باید پس از تایید مالک سایت پاکسازی شود. |
| 3 | URL Inspection در Google Search Console | برای URL اصلی انجام شد. |
| 4 | Request Indexing | درخواست indexing برای URL اصلی ثبت شد و پیام موفقیت `Indexing requested` دریافت شد. |
| 5 | Submit sitemap اصلی | `sitemap_index.xml` ثبت شد و در جدول Search Console با وضعیت `Success` دیده شد. |
| 6 | تست فنی sitemap اصلی | `https://zioiran.com/sitemap_index.xml` با HTTP 200 و `text/xml` پاسخ می‌دهد. |
| 7 | تست فنی sitemap صفحات | `https://zioiran.com/page-sitemap.xml` با HTTP 200 و `text/xml` پاسخ می‌دهد. |
| 8 | بررسی حضور URL اصلی در sitemap صفحات | URL اصلی در `page-sitemap.xml` وجود دارد. |
| 9 | بررسی حضور URL تکراری در sitemap صفحات | URL تکراری `-2` نیز در `page-sitemap.xml` وجود دارد. |
| 10 | بررسی propertyهای Search Console | property جدا برای GitHub Pages در حساب فعلی دیده نشد؛ submit مستقیم URLهای GitHub Pages نیازمند افزودن property جدید است. |

## ریسک فوری SEO

هر دو URL زیر هم‌زمان زنده هستند و در sitemap صفحات دیده می‌شوند:

- `https://zioiran.com/curtain-blinds-knowledge-base/`
- `https://zioiran.com/curtain-blinds-knowledge-base-2/`

برای جلوگیری از محتوای تکراری و رقابت داخلی، نسخه `-2` باید با تایید مالک سایت حذف، draft یا به URL اصلی redirect شود.

## پیشنهاد اجرای بعدی

اولویت بعدی، پاکسازی نسخه تکراری `-2` است. بعد از آن باید دوباره `page-sitemap.xml` بررسی شود تا فقط URL اصلی باقی مانده باشد.
