# AI_Project
A repo for the AI course project.
### Project Phase 1

روی مسئله‌ی سگمنتیشن جاده تمرکز دارد و سه معماری را از صفر می‌سازد: `UNet`، `AttentionUNet` و `ResidualAttentionUNet`. داده‌ها از دیتاست Massachusetts Roads (Kaggle) بارگیری می‌شوند، Loaderها ساخته می‌شوند و مدل‌ها با ترکیب ضرایب `Dice + IoU + BCE` آموزش و ارزیابی می‌گردند. معیارها (Loss، IoU، Dice) گزارش می‌شوند و نمودار روند آموزش/اعتبارسنجی برای مدل Residual Attention نشان داده می‌شود. برای اجرا، سلول دریافت داده، آماده‌سازی و سپس آموزش هر مدل را به‌ترتیب اجرا کنید.

### Project Phase 2

پیاده‌سازی کامل الگوریتم Soft Actor-Critic را ارائه می‌دهد: دو منتقد (Twin Q)، شبکه‌ی ارزش و هدف، و یک بازیگر گوسی با فشرده‌سازی Tanh. تجربه‌ها در `ReplayBuffer` ذخیره می‌شوند و عامل روی محیط‌های PyBullet (مثل `HalfCheetahBulletEnv-v0`) آموزش می‌بیند. خروجی‌ها شامل نمودار یادگیری و در صورت فعال‌بودن، ویدئوی اپیزود پایانی در مسیر `tmp/<env>/videos/` است. برای اجرا، نوت‌بوک را باز کنید، سلول نصب وابستگی‌ها را بزنید و سپس آموزش را شروع کنید؛ ابرپارامترها در ابتدای نوت‌بوک قابل تنظیم‌اند.

اجرای و ترین این پروژه ها روی kaggle صورت گرفته.

### Presentation Videos
ویدیوهای مربوط به ارائه پروژه در لینک زیر آپلود شده اند:
https://drive.google.com/drive/folders/1FFMCsEeqGGtGApwalCjF2wRQ3LrjC_0M?usp=sharing
