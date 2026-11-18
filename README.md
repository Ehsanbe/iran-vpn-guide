# راهنمای VPN در ایران: کدوم پروتکل، کدوم اپ

راهنمای کوتاه و به‌روز (آبان ۱۴۰۵) از تیم فنی [توربونت](https://turbonet-vpn.pages.dev).

## کدوم پروتکل؟

| اینترنت | پیشنهاد | چرا |
|---|---|---|
| ایرانسل / همراه اول | VLESS + XHTTP، بعد Reality | روی TCP؛ اپراتورها UDP به خارج را بعد از ~۳۰ ثانیه می‌بُرند |
| وای‌فای / فیبر خونگی | Hysteria2 | روی UDP/QUIC؛ در تست ما ۲۹٫۹ از ۳۰ مگابیت |

داده‌ها: [بررسیِ لاگ سرور، ۲۳ تا ۲۶ آبان ۱۴۰۵](https://turbonet-vpn.pages.dev/vpn-irancell-hamrah-aval) ·
[تست سرعتِ سه پروتکل](https://turbonet-vpn.pages.dev/xhttp-reality-hysteria)

## کدوم اپ؟

- اندروید و ویندوز: Hiddify یا v2rayNG
- آیفون: Streisand یا V2Box

## اتصال با Hiddify در ۵ قدم

1. Hiddify را از گوگل‌پلی یا گیت‌هابِ رسمیِ Hiddify نصب کن.
2. لینکِ اشتراک (subscription) را کپی کن.
3. در Hiddify دکمهٔ «+» ← «افزودن از کلیپ‌بورد».
4. روی موبایل یک کانفیگِ XHTTP، روی وای‌فای Hysteria2 را انتخاب کن.
5. دکمهٔ اتصال را بزن؛ اگر وصل نشد کانفیگِ بعدی را امتحان کن.

آموزشِ تصویری: https://turbonet-vpn.pages.dev/hiddify-guide

## درباره

توربونت VPN برای کاربرانِ ایران است: سرورهای هلند، فنلاند و آمریکا، هر سه پروتکل در یک اشتراک،
تستِ رایگانِ یک‌روزه، خرید خودکار از ربات تلگرام [@TurboNetIR_bot](https://t.me/TurboNetIR_bot).

> توربونت (TurboNet) سرویسی مستقل است و هیچ ارتباطی با کانال‌ها، ربات‌ها یا فروشنده‌های هم‌نامِ دیگر ندارد. تنها ربات رسمی: [@TurboNetIR_bot](https://t.me/TurboNetIR_bot) · کانال رسمی: [@turbocloudvpn](https://t.me/turbocloudvpn)
