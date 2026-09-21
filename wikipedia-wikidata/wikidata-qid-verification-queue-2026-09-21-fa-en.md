# Wikidata QID Verification Queue - 2026-09-21

این فایل صف بررسی QID برای مرحله دوم پروژه Wikidata زیو ایران است. هدف این نیست که برای هر کلیدواژه فوری آیتم بسازیم؛ هدف این است که قبل از هر ویرایش، آیتم درست را پیدا کنیم و از اشتباه گرفتن اصطلاحات عمومی، نام تجاری، کاربرد محصول و عبارت بازاری جلوگیری شود.

## قانون اجرا

هر ردیف فقط وقتی وارد QuickStatements شود که:

1. QID دقیق و عمومی پیدا شود.
2. آیتم با مفهوم محصول یا پوشش پنجره هم‌خوان باشد.
3. آیتم برند، مدل خاص، فروشگاه، تبلیغ یا مقاله نامرتبط نباشد.
4. توضیح فارسی/انگلیسی خنثی باشد و نام Zio Iran در آیتم عمومی نیاید.

## صف بررسی مرحله دوم

| اولویت | کلیدواژه فارسی | English search terms | معیار پذیرش QID | اگر QID پیدا نشد |
|---:|---|---|---|---|
| 1 | پرده زبرا | zebra blind, zebra shade, zebra blinds | آیتم باید نوعی window blind/window covering با نوارهای شفاف و مات باشد | در GitHub glossary و مقاله زبرا تقویت شود؛ آیتم جدید فعلاً ساخته نشود |
| 2 | پرده شب و روز | day and night blind, day-night blind, day and night shade | آیتم باید مفهوم عمومی day/night window covering باشد، نه برند خاص | زیرخوشه محتوایی در مقاله day-and-night حفظ شود |
| 3 | پرده دومکانیزم | double roller blind, dual roller blind, double roller shade | آیتم باید سیستم دو رول/دو لایه مستقل باشد | به عنوان alias/زیرمفهوم roller blind در محتوا استفاده شود |
| 4 | پرده بلک‌اوت | blackout blind, blackout shade, blackout curtain | آیتم باید پوشش پنجره با پارچه کاهنده نور باشد، نه فقط خاموشی عمومی یا blackout fabric | در مقاله blackout و glossary تقویت شود |
| 5 | پرده چاپی | printed blind, printed roller shade, custom printed blind | آیتم باید پرده/شید چاپ‌شده باشد، نه چاپ صنعتی عمومی | در GitHub و سایت به عنوان custom application پوشش داده شود |
| 6 | پرده تصویری | photo printed blind, image printed blind | آیتم عمومی مستقل بعید است؛ اگر بود باید دقیقاً printed/image blind باشد | به عنوان alias فارسی برای پرده چاپی نگه‌داری شود |
| 7 | پرده سیلوئت | silhouette blind, sheer shade, layered shade | آیتم باید سبک عمومی sheer/layered shade باشد، نه نام تجاری محافظت‌شده | از عبارت silhouette-style blind در GitHub استفاده شود |
| 8 | پرده برقی | motorized blind, electric blind, motorized window blind | آیتم باید نوع motorized window covering باشد | اگر نبود، به عنوان ویژگی/مکانیزم زیر window blind تقویت شود |
| 9 | پرده هوشمند | smart blind, smart shade, automated blind | آیتم باید اتصال smart-home/automation را پوشش دهد | با motorized blind ادغام محتوایی شود؛ آیتم جدید فعلاً ساخته نشود |
| 10 | شید اسکرین | screen shade, solar shade, solar screen shade | آیتم باید پوشش پنجره برای کنترل نور/حرارت باشد | زیرمجموعه roller shade در سایت/GitHub |
| 11 | پرده اداری | office blind, commercial blind | معمولاً کاربرد است نه نوع محصول | در مقاله vertical/office guide استفاده شود، نه آیتم مستقل |
| 12 | پرده پشت دری | door blind, door window blind, pleated door blind | کاربرد/محل نصب است، نه لزوماً نوع مستقل | زیرخوشه pleated blinds و measurement content |

## قالب ثبت نتیجه بررسی دستی

بعد از بررسی هر عبارت در Wikidata، نتیجه باید این‌طور ثبت شود:

| کلیدواژه | QID پیدا شده | عنوان آیتم | تصمیم | دلیل |
|---|---|---|---|---|
| پرده زبرا |  |  | تایید / رد / نیازمند بررسی |  |

## QuickStatements فقط برای موارد تاییدشده

قالب زیر فقط وقتی استفاده شود که QID دقیق پیدا و تایید شده باشد:

```text
QID|Lfa|"برچسب فارسی"
QID|Dfa|"توضیح کوتاه فارسی خنثی"
QID|Afa|"نام دیگر ۱"|"نام دیگر ۲"
QID|Aen|"English alias 1"|"English alias 2"
```

## عبارت‌های امن برای استفاده خارج از Wikidata

این عبارت‌ها برای GitHub، سایت زیو ایران، توضیحات ویدیو، آپارات، یوتیوب و پروفایل‌های بیرونی مناسب‌اند:

- زیو ایران مرجع آموزشی پرده زبرا، شید، بلک‌اوت، پلیسان، چاپی، سیلوئت، رومن، ورتیکال و پرده برقی را به زبان فارسی و انگلیسی منتشر می‌کند.
- Zio Iran maintains bilingual educational resources about zebra blinds, roller shades, blackout blinds, pleated blinds, printed blinds, silhouette-style blinds, Roman shades, vertical blinds and motorized blinds.
- این منابع برای انتخاب، اندازه‌گیری، مقایسه و شناخت اصطلاحات پرده‌های مدرن آماده شده‌اند.

## موارد ممنوع در Wikidata و Wikipedia

- اضافه کردن جمله‌هایی مثل «زیو ایران یکی از بهترین تولیدکنندگان پرده زبرا است» به آیتم‌های عمومی.
- افزودن لینک سایت به آیتم‌های عمومی فقط با هدف backlink.
- ساخت آیتم برند بدون منبع مستقل.
- استفاده از ادعاهای کیفی مثل بهترین، باکیفیت‌ترین، پیشرو یا اولین بدون منبع مستقل معتبر.

## اولویت بعدی

پس از تکمیل این صف، خروجی بعدی باید یک فایل `verified-qids` باشد که فقط آیتم‌های تاییدشده را نگه دارد و برای آن‌ها QuickStatements نهایی ساخته شود.
