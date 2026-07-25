# GitHub Pages راه‌اندازی

## ساختار فایل‌ها
این پوشه را همان‌طور که هست در ریشه‌ی ریپو قرار بده:

- dashboard.html
- data.js
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png

## مراحل
1. در GitHub یک repository جدید بساز.
2. فایل‌های داخل این پوشه را upload کن.
3. از Settings > Pages:
   - Source = Deploy from a branch
   - Branch = main
   - Folder = /(root)
4. چند دقیقه صبر کن تا لینک ساخته شود.

## لینک نهایی
اگر نام کاربری `USERNAME` و نام ریپو `REPO` باشد، آدرس معمولاً این است:

`https://USERNAME.github.io/REPO/dashboard.html`

## افزودن به صفحه اصلی آیفون
1. لینک را در Safari باز کن.
2. Share را بزن.
3. Add to Home Screen را انتخاب کن.

## نکته مهم
- برای عملکرد PWA باید حتماً با HTTPS باز شود.
- بعضی قابلیت‌های قیمت زنده ممکن است به اینترنت و API خارجی وابسته باشند.
