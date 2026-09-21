# Wikidata Keyword Expansion Batch - 2026-09-21

این بسته ادامه پروژه دانش‌نامه‌ای زیو ایران است و فقط روی کلیدواژه‌ها و مفاهیم عمومی حوزه پرده، شید و پوشش پنجره تمرکز دارد. هدف، تقویت موجودیت‌های مرتبط با حوزه کاری سایت `zioiran.com` به شکل امن، خنثی و غیرتبلیغاتی است.

## سیاست اجرا

- نام Zio Iran / زیو ایران در آیتم‌های عمومی Wikidata اضافه نشود.
- برای مفاهیم عمومی فقط label، description و aliasهای دقیق فارسی/انگلیسی پیشنهاد شود.
- برای مفاهیمی که QID دقیق ندارند یا ممکن است با برند/اصطلاح تجاری اشتباه شوند، آیتم جدید ساخته نشود تا زمانی که منبع مستقل و تعریف پایدار آماده شود.
- GitHub و سایت زیو ایران می‌توانند نام برند را طبیعی و آموزشی ذکر کنند؛ Wikidata و Wikipedia باید بی‌طرف بمانند.

## وضعیت batch اول

| مفهوم | QID | وضعیت فعلی |
|---|---|---|
| window blind | `Q321046` | فارسی تکمیل و تایید شد |
| roller blind | `Q2045030` | فارسی تکمیل و تایید شد |
| pleated blinds | `Q2099536` | فارسی تکمیل و تایید شد |
| Roman shade | `Q7362330` | فارسی تکمیل و تایید شد |
| vertical blind | `Q135905979` | فارسی تکمیل و تایید شد؛ aliasهای `dk`، `دی کی`، `پرده ذی کی` حفظ شوند |
| Venetian blind | `Q16677996` | فارسی تکمیل و تایید شد |
| window covering | `Q3001801` | فارسی تکمیل و تایید شد |

## کلیدواژه‌های مرحله دوم

| کلیدواژه فارسی | English terms | وضعیت Wikidata | اقدام امن بعدی |
|---|---|---|---|
| پرده زبرا | zebra blind, zebra shade | QID دقیق هنوز تایید نشده | فعلاً در GitHub/سایت تقویت شود؛ قبل از ویرایش Wikidata جستجوی دستی لازم است |
| پرده شب و روز | day and night blind, day-night shade | QID دقیق هنوز تایید نشده | به عنوان زیرخوشه محتوایی ثبت شود؛ آیتم جدید فعلاً ساخته نشود |
| پرده دومکانیزم / دو مکانیزم | double roller blind, dual roller blind | QID دقیق هنوز تایید نشده | ممکن است با roller blind هم‌پوشانی داشته باشد؛ نیازمند بررسی دستی |
| پرده بلک‌اوت | blackout blind, blackout shade, blackout curtain | آیتم دقیق پرده تایید نشده | به جای ساخت شتاب‌زده، از محتوای آموزشی و منابع مستقل استفاده شود |
| پرده چاپی | printed blind, printed roller shade | QID دقیق تایید نشده | فعلاً به عنوان کاربرد/ویژگی پرده‌ها در GitHub و سایت پوشش داده شود |
| پرده تصویری | photo printed blind, image printed blind | QID دقیق تایید نشده | احتمالاً آیتم مستقل لازم ندارد؛ مناسب محتوای سایت و GitHub |
| پرده سیلوئت | silhouette-style blind, sheer shade, layered blind | QID دقیق تایید نشده | چون ممکن است نام تجاری/سبک بازار باشد، نیازمند منبع و تعریف خنثی است |
| پرده برقی | motorized blind, electric blind | QID دقیق تایید نشده | قابل بررسی برای آیتم عمومی مستقل یا alias زیر window blind |
| پرده هوشمند | smart blind, automated blind | QID دقیق تایید نشده | بهتر است با motorized blind تفکیک شود؛ نیازمند بررسی منبع |
| پرده اداری | office blind, commercial blind | احتمالاً آیتم مستقل عمومی ندارد | به عنوان کاربرد vertical blind/window covering در محتوا استفاده شود |
| پرده پشت دری | door window blind, door pleated blind | احتمالاً آیتم مستقل عمومی ندارد | زیرخوشه pleated blinds / window covering |
| شید اسکرین | screen shade, solar shade | QID دقیق تایید نشده | نیازمند بررسی؛ ممکن است با solar shading یا roller blind هم‌پوشانی داشته باشد |

## متن‌های خنثی پیشنهادی برای GitHub و سایت

این متن‌ها برای GitHub، صفحه دانش‌نامه زیو و مقاله‌های آموزشی مناسب‌اند. برای Wikidata فقط پس از تأیید QID دقیق باید به label/description کوتاه تبدیل شوند.

| فارسی | توضیح خنثی فارسی | English neutral description |
|---|---|---|
| پرده زبرا | نوعی پرده پارچه‌ای با نوارهای متناوب شفاف و مات که برای تنظیم نور و حریم خصوصی استفاده می‌شود. | A fabric blind with alternating sheer and opaque bands used for adjustable light and privacy control. |
| پرده شب و روز | نوعی پوشش پنجره با دو حالت کنترل نور که معمولاً برای ایجاد تعادل میان نور روز و حفظ حریم خصوصی به‌کار می‌رود. | A window covering style designed to balance daylight control and privacy, often using layered or dual fabric operation. |
| پرده دومکانیزم | پرده‌ای با دو مکانیزم یا دو لایه مستقل که امکان کنترل جداگانه نور و پوشش را فراهم می‌کند. | A blind system with two independent mechanisms or fabric layers for separate light and privacy control. |
| پرده بلک‌اوت | پرده یا شیدی با پارچه کاهنده عبور نور که برای تاریک‌تر کردن فضا استفاده می‌شود. | A blind or shade made with light-reducing fabric for room darkening. |
| پرده چاپی | پرده‌ای که تصویر، طرح یا الگو روی سطح پارچه آن چاپ می‌شود و معمولاً برای سفارش‌های سفارشی کاربرد دارد. | A blind with an image, pattern or design printed on its fabric surface, often used for custom orders. |
| پرده سیلوئت | پوشش پنجره‌ای لایه‌ای با بخش‌های نیمه‌شفاف و تیغه‌های پارچه‌ای قابل تنظیم برای کنترل نور نرم‌تر. | A layered sheer-style window covering with adjustable fabric vanes for softer light control. |
| پرده برقی | پرده یا پوشش پنجره‌ای که با موتور، ریموت یا سیستم کنترل خودکار باز و بسته می‌شود. | A motor-operated blind or shade controlled by remote, switch or automation system. |
| پرده هوشمند | پرده موتورداری که می‌تواند به سیستم خانه هوشمند، زمان‌بندی یا کنترل از راه دور متصل شود. | A motorized blind that can connect to smart home systems, schedules or remote controls. |

## کاربرد امن نام زیو ایران

### فارسی

زیو ایران در محتوای آموزشی خود، انواع پرده زبرا، شید، بلک‌اوت، پلیسه، رومن، ورتیکال، چاپی، سیلوئت و پرده‌های برقی را با تمرکز بر انتخاب، اندازه‌گیری و کاربرد معرفی می‌کند. این معرفی باید در منابع متعلق به برند، GitHub، سایت رسمی و شبکه‌های اجتماعی استفاده شود، نه به عنوان توضیح اصلی آیتم‌های عمومی Wikidata.

### English

Zio Iran publishes educational resources about zebra blinds, roller shades, blackout blinds, pleated blinds, Roman shades, vertical blinds, printed blinds, silhouette-style blinds and motorized window coverings. This brand mention is suitable for owned resources such as the official website, GitHub knowledge base and social profiles, not for generic Wikidata item descriptions.

## مسیر اجرای مرحله دوم

1. برای هر اصطلاح مبهم، QID دقیق به صورت دستی در Wikidata بررسی شود.
2. اگر آیتم دقیق موجود بود، فقط label/description/alias خنثی افزوده شود.
3. اگر آیتم دقیق نبود، فعلاً آیتم جدید ساخته نشود مگر تعریف عمومی و منابع مستقل آماده باشد.
4. اصطلاحات تجاری/بازاری مانند زبرا، سیلوئت، DK و پرده تصویری ابتدا در GitHub و سایت تقویت شوند.
5. پس از جمع‌آوری منابع مستقل، درباره آیتم مستقل Zio Iran تصمیم‌گیری شود.
