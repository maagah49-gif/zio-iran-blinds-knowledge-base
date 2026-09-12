# گزارش اجرای تسک‌های مانده دانش‌نامه زیو ایران - 2026-09-12

## خلاصه اجرایی

در این مرحله، تسک‌های مانده پروژه دانش‌نامه/سئوی زیو ایران به‌ترتیب بررسی و تا حد دسترسی موجود انجام شدند. کارهای قابل انجام داخل GitHub تکمیل یا کنترل شدند. کارهایی که نیاز به ورود به وردپرس، GitHub Settings یا Google Search Console دارند، به‌عنوان نیازمند اقدام دستی/مرورگر علامت‌گذاری شدند.

## وضعیت تسک‌ها به‌ترتیب

| شماره | تسک | وضعیت | نتیجه/اقدام |
|---|---|---|---|
| 1 | آماده‌سازی GitHub Pages | انجام شد | فایل `docs/index.html` و راهنمای فعال‌سازی ساخته شده است. |
| 2 | فعال‌سازی GitHub Pages از Settings | نیازمند اقدام دستی | ابزار فعلی دسترسی تنظیمات Pages ندارد؛ باید در GitHub از `Settings > Pages > main > /docs` فعال شود. |
| 3 | انتشار صفحه فارسی دانش‌نامه در وردپرس | نیازمند ورود وردپرس | HTML آماده است: `wordpress-ready/knowledge-base-html-no-internal-links-fa.md`. |
| 4 | تنظیم Rank Math فارسی | نیازمند ورود وردپرس | پک آماده است: `wordpress-ready/knowledge-base-rankmath-schema-paste-pack-fa.md`. |
| 5 | افزودن Schema فارسی | آماده اجرا | JSON ترکیبی فارسی معتبر است: `schema/knowledge-base-combined-schema-zioiran-fa.json`. |
| 6 | تست صفحه فارسی بعد از انتشار | منتظر انتشار | چک‌لیست آماده است: `qa/knowledge-base-live-url-test-cases-fa.md`. |
| 7 | ثبت URL فارسی در Search Console | منتظر انتشار | مراحل آماده است: `indexing/knowledge-base-search-console-submit-steps-fa.md`. |
| 8 | لینک از صفحه اصلی به دانش‌نامه | نیازمند ورود وردپرس | بلوک آماده است: `site-content/homepage-knowledge-base-link-block-fa.md`. |
| 9 | لینک از دسته‌بندی‌ها به دانش‌نامه | نیازمند ورود وردپرس | متن‌ها آماده‌اند: `site-content/category-to-knowledge-base-snippets-fa.md`. |
| 10 | ثبت وضعیت ایندکس | منتظر انتشار | قالب آماده است: `indexing/post-publish-indexing-log-template-fa.md`. |
| 11 | تصویر OG صفحه دانش‌نامه | آماده طراحی/بارگذاری | بریف آماده است: `metadata/knowledge-base-og-image-brief-fa-en.md`. |
| 12 | انتشار نسخه انگلیسی | منتظر فعال شدن بخش انگلیسی سایت | متن و HTML انگلیسی آماده است. |
| 13 | تنظیم Rank Math انگلیسی | منتظر صفحه انگلیسی | فایل آماده است: `metadata/rank-math-knowledge-base-page-en.md`. |
| 14 | افزودن Schema انگلیسی | آماده اجرا بعد از صفحه انگلیسی | JSON انگلیسی معتبر است: `schema/knowledge-base-combined-schema-zioiran-en.json`. |
| 15 | فعال‌سازی hreflang | منتظر انتشار هر دو زبان | راهنما آماده است: `technical-seo/knowledge-base-hreflang-fa-en.md`. |
| 16 | تکمیل About ریپو در GitHub | نیازمند UI یا دسترسی تنظیمات | متن راهنما آماده است: `github/github-ui-update-instructions-fa.md`. |
| 17 | تست URL GitHub Pages | منتظر فعال‌سازی Pages | بعد از فعال‌سازی باید URL `https://maagah49-gif.github.io/zio-iran-blinds-knowledge-base/` تست شود. |
| 18 | لینک از سایت به GitHub/GitHub Pages | نیازمند ورود وردپرس | بلوک‌ها و نقشه لینک‌دهی آماده است. |
| 19 | انتشار مستقیم در Wikipedia | انجام نشده، نیازمند منبع مستقل | فعلاً فقط پیش‌نویس امن آماده است؛ بدون منابع مستقل نباید منتشر شود. |
| 20 | ساخت/تکمیل Wikidata برای برند | انجام نشده، نیازمند منبع مستقل | QuickStatements و ریسک‌سنجی آماده است؛ اجرای مستقیم توصیه نمی‌شود تا منبع مستقل داشته باشیم. |
| 21 | انتشار بیرونی و citation | آماده اجرا | متن‌های امن و برنامه citation آماده شده‌اند. |
| 22 | کنترل ادعاهای تبلیغاتی | انجام شد | در فایل‌های اجرایی تازه ادعای پرریسک دیده نشد. |
| 23 | اعتبارسنجی JSON schema | انجام شد | فایل‌های schema فارسی و انگلیسی با JSON.parse معتبر بودند. |
| 24 | گزارش نهایی وضعیت | انجام شد | همین فایل گزارش وضعیت را ثبت می‌کند. |

## کنترل فنی انجام‌شده

فایل‌های زیر از ریپو خوانده و کنترل شدند:

| فایل | نتیجه |
|---|---|
| `schema/knowledge-base-combined-schema-zioiran-fa.json` | JSON معتبر |
| `schema/knowledge-base-combined-schema-zioiran-en.json` | JSON معتبر |
| `schema/knowledge-base-faq-schema-zioiran.json` | JSON معتبر |
| `schema/knowledge-base-faq-schema-zioiran-en.json` | JSON معتبر |
| `docs/index.html` | شامل لینک سایت و ریپو؛ بدون ادعای تبلیغاتی پرریسک |
| `wordpress-ready/knowledge-base-html-no-internal-links-fa.md` | آماده کپی در وردپرس؛ بدون ادعای تبلیغاتی پرریسک |
| `wordpress-ready-en/knowledge-base-html-no-internal-links-en.md` | آماده کپی در وردپرس؛ بدون ادعای تبلیغاتی پرریسک |

## کارهایی که واقعاً باقی مانده‌اند

1. فعال‌سازی GitHub Pages از Settings مخزن.
2. ورود به وردپرس و انتشار صفحه فارسی.
3. افزودن متا و schema در Rank Math/صفحه.
4. افزودن لینک از صفحه اصلی و دسته‌بندی‌ها.
5. تست URL زنده بعد از انتشار.
6. ثبت URL در Search Console.
7. طراحی یا بارگذاری تصویر OG.
8. اگر بخش انگلیسی سایت فعال شد، انتشار نسخه انگلیسی و سپس hreflang.
9. گرفتن منابع مستقل برای Wikipedia/Wikidata.
10. اجرای citationهای بیرونی با متن‌های امن.

## تصمیم اجرایی پیشنهادی

اولویت بعدی باید انتشار صفحه فارسی روی zioiran.com باشد. تا وقتی صفحه فارسی منتشر نشود، Search Console، لینک‌دهی داخلی، hreflang و گزارش ایندکس قابل تکمیل واقعی نیستند.
