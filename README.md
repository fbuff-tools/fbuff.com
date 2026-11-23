# fbuff

Free online tools that run in your browser: https://fbuff.com

No signup, no uploads. Every tool processes your files and data locally with web APIs.

## For Christmas
- [Christmas Card Maker](https://fbuff.com/tools/christmas-card-maker/): pick a design, add your names, message and photo, then download a PNG or print it on 4x6.
- [Family Christmas Shirt Maker](https://fbuff.com/tools/family-christmas-shirt-maker/): matching family Christmas shirt designs with your family name.
- [Photo Calendar Maker](https://fbuff.com/tools/photo-calendar-maker/): a printable 2027 monthly calendar with your own photos, family name and important dates. A last-minute gift for grandparents.
- [Christmas Countdown](https://fbuff.com/tools/countdown-timer/): how many days, hours and minutes until Christmas, plus a timer with alarm.
- [Kids Typing Game](https://fbuff.com/tools/kids-typing-game/): for winter break. Easy words read aloud, pets, vehicles and superheroes to collect. No ads, no account.

## Everyday paperwork
- [Sign PDF](https://fbuff.com/tools/sign-pdf/): draw or type your signature and place it on any page. The file never leaves your device.
- [Redact PDF](https://fbuff.com/tools/pdf-redactor/): black out names and numbers so the text is really gone, not just covered.
- [Passport Photo Maker](https://fbuff.com/tools/passport-photo-maker/): 2x2 inch or 35x45 mm photos, laid out on a 4x6 print.
- [How to Write a Check](https://fbuff.com/tools/check-writing-helper/): turns an amount into words, with cents, and shows where each line goes.
- [Shipping Label Cropper](https://fbuff.com/tools/shipping-label-cropper/): crop a full-page shipping label PDF to 4x6 for a thermal printer.

## Developer and security
Each security page explains what causes the bug before how to check and fix it.

- [Chrome Zero-Day Check](https://fbuff.com/tools/chrome-zero-day-check/): is your Chrome patched against CVE-2026-125350, the zero-day exploited in attacks? Safe version numbers and how to update and relaunch.
- [SSHole Checker](https://fbuff.com/tools/sshole-checker/): is an Alpine Linux server open to the OpenSSH password bypass CVE-2026-123158? Fixed openssh package for each branch and how to turn password logins off.
- [CVE-2026-98432 Checker](https://fbuff.com/tools/cve-2026-98432-checker/): the Linux IPv4 TCP use-after-free (CVSS 9.8) that Anthropic exploited over MPTCP. What causes it, which servers are at risk, how to patch or harden. Script: [fbuff-tools/cve-2026-98432-checker](https://github.com/fbuff-tools/cve-2026-98432-checker).
- [HTTP2Shell Checker](https://fbuff.com/tools/http2shell-checker/): is your Node.js, Bun, Python Brotli or libbrotli affected by CVE-2026-111497? Script and fixed versions: [fbuff-tools/http2shell-checker](https://github.com/fbuff-tools/http2shell-checker).
- [KSMBD Exposure Checker](https://fbuff.com/tools/ksmbd-checker/): is a Linux server running KSMBD and open to ZDI-CAN-33774 / ZDI-CAN-33549? Script and mitigations: [fbuff-tools/ksmbd-checker](https://github.com/fbuff-tools/ksmbd-checker).
- [DarkSword iPhone Check](https://fbuff.com/tools/darksword-check/): type your iOS version to see if your iPhone is open to DarkSword or P7 DarkSword spyware and which update fixes it.
- [PHP2Shell Checker](https://fbuff.com/tools/php2shell-checker/): paste php -v or phpinfo() to check CVE-2026-109618 and CVE-2026-109619. Script and fixed packages: [fbuff-tools/php2shell-checker](https://github.com/fbuff-tools/php2shell-checker).

## Cars and science
- [Downforce Calculator](https://fbuff.com/tools/downforce-calculator/): how much downforce, fan suction or thrust a car needs to drive upside down, like the 2026 Tesla Roadster.

## Popular tools
- [QR Code Generator](https://fbuff.com/tools/qr-generator/): links, text and Wi-Fi, with a logo and colors. Static codes that never expire.
- [Image Compressor](https://fbuff.com/tools/image-compressor/): compress JPG, PNG and WebP to a target size such as 100 KB.
- [Barcode Generator](https://fbuff.com/tools/barcode-generator/): Code 128, EAN-13, EAN-8, UPC-A, PDF417.
- [2FA Code Generator](https://fbuff.com/tools/2fa-code/): TOTP codes from a secret key.

[All 110+ tools →](https://fbuff.com/tools/)

## How it works
A static Next.js site on Cloudflare Pages with no backend. Heavy libraries (PDF, barcode, image processing) load only when a tool needs them.
