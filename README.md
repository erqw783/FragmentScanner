# FragmentScanner

## Install
```
bash <(curl -fsSL https://raw.githubusercontent.com/Ptechgithub/FragmentScanner/main/install.sh)
```
![28](https://raw.githubusercontent.com/Ptechgithub/configs/main/media/28.jpg)

- پشتیبانی از پروتکل‌های 
- VLESS WS/GRPC
- VMESS WS/GRPC
- TROJAN WS/GRPC

 با انتخاب گزینه 1 کانفیگ ساده ( بدون فرگمنت ) خودتون رو به اسکریپت بدید ، به شما خروجی کاستوم (فرمت json) همراه با فرگمنت میده. که میتونید همون رو کپی کنید و استفاده کنید. این فرمت پیشنیاز گزینه ی 2 میباشد.
 
بعد از اضافه شدن فرگمنت و نمایش فرمت json کانفیگ شما در فایل config.json در همان مسیر ذخیره میشود. حالا شما میتوانید مقادیر مناسب فرگمنت را با گزینه 2 اسکن کنید . یعنی فقط گزینه ی 2 را میزنید فایل کانفیگ ساخته شده در مرحله ی قبل را میخواند و پس از پرسیدن 4 سوال شروع به اسکن میکند و نتایج را به شما نمایش میدهد.

---
سوال 1: تعداد راند های اسکن را تعیین میکند . پیش فرض 10 هست، یعنی 10 ترکیب تصادفی با مقادیر وارد شده را تست میکند.

سوال 2: زمان تایم اوت برای تست های پینگ را تعیین میکند.

سوال 3: فقط در صورتی که Listening port داخل config.json را تغییر دادید پورت را تغییر بدهید. درغیر این صورت فقط Enter بزنید.

سوال 4: تعداد درخواست‌ها را برای هر نمونه وارد کنید، یعنی چند بار یک مجموعه مقادیر باید آزمایش شود.

---

برای نمایش مرتب خروجی و عدم تو رفتگی کد قبل از اجرای اسکریپت Zoom Out کنید.

در صورت خروج از برنامه برای نمایش مجدد فایل config دستور `cat config.json` را وارد کنید و اینتر بزنید. 

 همچنین میتونید کانفیگ فرگمنت دار خودتون رو در فایل config.json ذخیره  کنید و فقط با گزینه 2 اسکن انجام بدید. 

Credits:

[Surfboardv2ray](https://github.com/Surfboardv2ray/batch-fragment-scanner)
