# fbuff

Free online tools that run in your browser: https://fbuff.com

No signup, no uploads. Every tool processes your data locally with web APIs.

## Popular tools
- [QR Code Generator](https://fbuff.com/tools/qr-generator/): links, text and Wi-Fi, with a logo and colors. Static codes that never expire.
- [Barcode Generator](https://fbuff.com/tools/barcode-generator/): Code 128, EAN-13, EAN-8, UPC-A, PDF417.
- [Barcode Scanner](https://fbuff.com/tools/barcode-scanner/): read barcodes and QR codes from an image.
- [2FA Code Generator](https://fbuff.com/tools/2fa-code/): TOTP codes from a secret key.
- [UUID Generator](https://fbuff.com/tools/guid-uuid-generator/): UUID v4 and short GUIDs.

[All 85+ tools →](https://fbuff.com/tools/)

## How it works
A static Next.js site on Cloudflare Pages with no backend. Heavy libraries (ZXing, bwip-js) load only when a tool needs them.
