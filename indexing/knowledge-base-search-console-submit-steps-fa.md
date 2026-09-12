# مراحل ثبت صفحه دانش‌نامه در Google Search Console

## پیش‌نیاز

صفحه باید روی سایت منتشر شده باشد و با کد 200 باز شود. اگر صفحه هنوز draft است یا نیاز به ورود دارد، درخواست ایندکس ثبت نشود.

## URL فارسی پیشنهادی

`https://zioiran.com/curtain-blinds-knowledge-base/`

## URL انگلیسی پیشنهادی بعد از فعال شدن

`https://zioiran.com/en/modern-blinds-knowledge-base/`

## مراحل ثبت دستی

1. وارد Google Search Console شوید.
2. property مربوط به `https://zioiran.com/` را انتخاب کنید.
3. URL صفحه دانش‌نامه را در بخش URL Inspection وارد کنید.
4. روی Test Live URL بزنید.
5. اگر صفحه قابل ایندکس بود، Request Indexing را بزنید.
6. بعد از ثبت، وضعیت را در فایل پیگیری روزانه وارد کنید.

## مواردی که باید قبل از Request Indexing چک شود

| مورد | وضعیت مطلوب |
|---|---|
| صفحه نیاز به ورود ندارد | بله |
| کد وضعیت | 200 |
| canonical | همان URL صفحه |
| robots meta | index, follow |
| لینک GitHub | داخل متن صفحه وجود دارد |
| عنوان صفحه | شامل دانش‌نامه و زیو ایران است |
| FAQ | در انتهای صفحه وجود دارد |
| schema | بدون خطای JSON-LD است |

## بعد از ثبت

- روز اول: URL Inspection دوباره بررسی شود.
- روز سوم: بررسی شود آیا URL در sitemap دیده شده است یا نه.
- روز هفتم: با جستجوی `site:zioiran.com دانش‌نامه زیو ایران` وضعیت دیده شدن بررسی شود.

## نکته

اگر Search Console خطای Crawled - currently not indexed داد، متن صفحه، لینک داخلی از صفحه اصلی و لینک از چند صفحه دسته‌بندی تقویت شود.
