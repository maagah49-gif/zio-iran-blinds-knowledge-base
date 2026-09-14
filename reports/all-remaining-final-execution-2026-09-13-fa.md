# گزارش اجرای نهایی کارهای مانده - 2026-09-13

این بسته برای جمع کردن همه کارهای مانده پروژه دانش‌نامه، GitHub Pages، وردپرس، Search Console، انتشار بیرونی و ویکی‌دیتا آماده شد.

| ردیف | کار | وضعیت | خروجی |
|---|---|---|---|
| 1 | ساخت داشبورد عمومی اجرای نهایی | انجام شد | `docs/final-launch-dashboard.html` |
| 2 | اتصال داشبورد به صفحه اصلی | انجام شد | `docs/index.html` |
| 3 | افزودن داشبورد به sitemap | انجام شد | `docs/sitemap.xml` |
| 4 | افزودن داشبورد به URL list | انجام شد | `docs/urls.txt` |
| 5 | افزودن داشبورد به discovery/feed/metadata | انجام شد | `docs/discovery.json`، `docs/feed.json`، `docs/metadata.json` |
| 6 | آماده‌سازی بسته نهایی وردپرس فارسی | انجام شد | `wordpress-ready/knowledge-base-final-publish-pack-fa.md` |
| 7 | آماده‌سازی بسته نهایی وردپرس انگلیسی | انجام شد | `wordpress-ready-en/modern-blinds-knowledge-base-final-pack-en.md` |
| 8 | آماده‌سازی schema نهایی | انجام شد | `schema/knowledge-base-final-combined-schema-zioiran.json` |
| 9 | آماده‌سازی Search Console و URL/canonical map | انجام شد | `indexing/final-search-console-submit-batch-fa.md` و `mapping/final-live-url-canonical-map-fa-en.md` |
| 10 | آماده‌سازی انتشار بیرونی و گیت ویکی‌دیتا | انجام شد | `publishing/final-wordpress-menu-home-link-instructions-fa.md`، `distribution/final-external-citation-outreach-batch-fa-en.md`، `wikipedia-wikidata/final-wikidata-readiness-gate-fa-en.md` و `qa/final-launch-qa-checklist-fa-en.md` |

## مواردی که نیازمند ورود بیرونی هستند

- انتشار صفحه فارسی در WordPress روی `zioiran.com`: انجام شد. URL اصلی موجود و زنده است: `https://zioiran.com/curtain-blinds-knowledge-base/`.
- ثبت URL اصلی در Google Search Console: انجام شد و برای URL اصلی درخواست indexing ثبت شد.
- submit دوباره sitemap در Search Console: انجام شد. `https://zioiran.com/sitemap_index.xml` در Search Console با وضعیت `Success` دیده شد.
- پاکسازی نسخه تکراری وردپرس: انجام شد. نسخه تکراری `https://zioiran.com/curtain-blinds-knowledge-base-2/` به زباله‌دان منتقل شد، در تست عمومی `HTTP 404` داد و از `page-sitemap.xml` حذف شد.
- ساخت آیتم برند در Wikidata فقط بعد از جمع شدن منابع مستقل.

## جمع‌بندی

از سمت repository، GitHub Pages، فایل‌های discovery، متن‌های وردپرس، schema، QA، نقشه URL، بسته انتشار بیرونی، انتشار وردپرس، submit در Search Console و پاکسازی صفحه تکراری، کارهای اصلی اجرا شده‌اند. ریسک فوری محتوای تکراری برای صفحه دانش‌نامه فارسی برطرف شد.
