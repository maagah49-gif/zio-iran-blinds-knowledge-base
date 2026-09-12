# گزارش نهایی اجرای پروژه دانش نامه زیو ایران

تاریخ: 2026-09-12  
مخزن: https://github.com/maagah49-gif/zio-iran-blinds-knowledge-base

## نتیجه کلی

همه کارهایی که با دسترسی فعلی از داخل GitHub قابل انجام بود، انجام و در مخزن ثبت شد.  
کارهای باقی مانده از جنس تولید محتوا نیستند؛ اجرای آن ها به ورود شما به پنل های بیرونی نیاز دارد: GitHub Settings، وردپرس/Rank Math، Google Search Console و منابع مستقل برای ویکی پدیا/ویکی دیتا.

## انجام شده در مخزن

- ساخت و تکمیل پایگاه دانش فارسی و انگلیسی برای پرده زبرا، شید، بلک اوت، پلیسه، چاپی، سیلوئت، رومن، موتورایز و دسته های مرتبط.
- آماده سازی متن های WordPress-ready فارسی و انگلیسی.
- آماده سازی نسخه های HTML بدون لینک داخلی برای انتشار سریع در وردپرس.
- آماده سازی Schema های FAQ، KnowledgeBasePage، Organization، Website، Product و ItemList.
- اعتبارسنجی JSON فایل های Schema اصلی.
- ساخت صفحه GitHub Pages در مسیر docs/index.html.
- ساخت راهنمای فعال سازی GitHub Pages.
- ساخت نقشه لینک سازی داخلی سایت به GitHub و دانش نامه.
- ساخت بسته متادیتا Rank Math، Open Graph، alt text و توضیحات انتشار خارجی.
- ساخت بسته ویکی پدیا/ویکی دیتا با تاکید بر لحن خنثی و نیاز به منابع مستقل.
- ساخت Issue اجرایی برای پیگیری کارهای پنلی: https://github.com/maagah49-gif/zio-iran-blinds-knowledge-base/issues/1

## وضعیت فایل های آماده انتشار

| بخش | فایل آماده | وضعیت |
|---|---|---|
| صفحه دانش نامه فارسی وردپرس | wordpress-ready/knowledge-base-html-no-internal-links-fa.md | آماده کپی در وردپرس |
| صفحه دانش نامه انگلیسی وردپرس | wordpress-ready-en/knowledge-base-html-no-internal-links-en.md | آماده کپی در وردپرس |
| متادیتا فارسی Rank Math | metadata/rank-math-knowledge-base-page-fa.md | آماده درج |
| متادیتا انگلیسی Rank Math | metadata/rank-math-knowledge-base-page-en.md | آماده درج |
| Schema ترکیبی فارسی | schema/knowledge-base-combined-schema-zioiran-fa.json | معتبر و آماده درج |
| Schema ترکیبی انگلیسی | schema/knowledge-base-combined-schema-zioiran-en.json | معتبر و آماده درج |
| صفحه عمومی GitHub Pages | docs/index.html | آماده فعال سازی از Settings |

## کارهای باقی مانده که نیاز به پنل دارند

1. GitHub Pages را از مسیر Settings > Pages فعال کنید:
   - Branch: main
   - Folder: /docs
   - آدرس مورد انتظار بعد از فعال سازی: https://maagah49-gif.github.io/zio-iran-blinds-knowledge-base/

2. صفحه دانش نامه فارسی را در وردپرس بسازید:
   - Slug پیشنهادی: curtain-blinds-knowledge-base
   - محتوا از: wordpress-ready/knowledge-base-html-no-internal-links-fa.md
   - Schema از: schema/knowledge-base-combined-schema-zioiran-fa.json

3. Rank Math را برای صفحه فارسی تکمیل کنید:
   - metadata/rank-math-knowledge-base-page-fa.md
   - FAQ Schema یا Custom Schema را از فایل Schema ترکیبی وارد کنید.

4. بعد از انتشار، URL فارسی را در Google Search Console ثبت کنید:
   - Live URL Test
   - Request Indexing
   - ثبت تاریخ در indexing/post-publish-indexing-log-template-fa.md

5. لینک داخلی از صفحه اصلی و دسته بندی ها اضافه شود:
   - site-content/homepage-knowledge-base-link-block-fa.md
   - site-content/category-to-knowledge-base-snippets-fa.md

6. نسخه انگلیسی بعد از فعال شدن بخش انگلیسی سایت منتشر شود:
   - wordpress-ready-en/knowledge-base-html-no-internal-links-en.md
   - schema/knowledge-base-combined-schema-zioiran-en.json
   - metadata/rank-math-knowledge-base-page-en.md

7. hreflang بعد از انتشار هر دو زبان اضافه شود:
   - technical-seo/knowledge-base-hreflang-fa-en.md

8. برای ویکی پدیا و ویکی دیتا، قبل از هر انتشار مستقیم، منابع مستقل باید جمع آوری شوند:
   - wikipedia-wikidata/independent-source-tracker-zioiran-fa.md
   - wikipedia-wikidata/source-requirements-for-zioiran-entity-fa.md

## نکته مهم درباره برند

در همه متن های آماده، نام زیو ایران با لحن طبیعی و غیرتبلیغاتی آمده است؛ یعنی به عنوان برند فعال در حوزه پرده های مدرن معرفی شده، نه با ادعاهای اثبات نشده مثل بهترین، اولین یا بزرگ ترین. این لحن برای انتشار خارجی، ویکی و اعتبار سئویی امن تر است.

## جمع بندی اجرایی

پروژه از نظر محتوایی، ساختاری، Schema، GitHub، صفحه عمومی و چک لیست انتشار تکمیل شده است.  
مرحله بعدی دیگر تولید فایل نیست؛ باید پنل ها باز شوند و موارد بالا یکی یکی اعمال شوند.
