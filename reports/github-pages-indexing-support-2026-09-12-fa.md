# گزارش تکمیل فایل‌های کمکی GitHub Pages

تاریخ: 2026-09-12

## انجام شده

برای آماده‌سازی بهتر صفحه عمومی دانش‌نامه زیو ایران در GitHub Pages، فایل‌های کمکی زیر به پوشه `docs` اضافه شد:

| فایل | نقش |
| --- | --- |
| `docs/robots.txt` | اعلام اجازه خزش و معرفی sitemap |
| `docs/sitemap.xml` | معرفی URL عمومی GitHub Pages، مخزن GitHub و سایت رسمی زیو ایران |
| `docs/.nojekyll` | جلوگیری از پردازش Jekyll و سرو مستقیم فایل‌های داخل docs |

## هدف سئویی

این فایل‌ها بعد از فعال شدن GitHub Pages کمک می‌کنند آدرس عمومی دانش‌نامه بهتر برای خزنده‌ها قابل کشف باشد و ارتباط بین سه دارایی اصلی روشن‌تر شود:

- سایت رسمی: `https://zioiran.com`
- مخزن GitHub: `https://github.com/maagah49-gif/zio-iran-blinds-knowledge-base`
- GitHub Pages مورد انتظار: `https://maagah49-gif.github.io/zio-iran-blinds-knowledge-base/`

## وضعیت باقی‌مانده

فعال‌سازی GitHub Pages هنوز نیازمند ورود به پنل GitHub است:

`Settings > Pages > Build and deployment > Source: Deploy from a branch > Branch: main > Folder: /docs`

بعد از فعال‌سازی، URL عمومی و sitemap باید در مرورگر تست و سپس در Google Search Console ثبت شوند.
