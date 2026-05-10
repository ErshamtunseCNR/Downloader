<div align="center">
  <img src="https://raw.githubusercontent.com/nikzad-avasam/downloader/refs/heads/main/dl-icon.gif" width="400" alt="wide-2" />
</div>


🎬 برای دانلود ویدیوهای یوتیوب از این پروژه استفاده کنید :‌
https://github.com/nikzad-avasam/youtube-dl


 


## ⬇️ دانلود کننده فایل + 🌐 مرورگر وب 

- ✅  دانلود کننده هر فایلی از هرکجا درون گیتهاب شما  
- ✅  پشتیبانی از فایل های بزرگ چند گیگابایتی
- 🔐 امکان رمزگذاری روی فایل های دانلود شده جهت محافظت
- ✅  استفاده از پکیج aria2 جهت دانلود بدون مشکل 
- ✅  دانلود هر نوع فایلی و فشرده سازی اتوماتیک و تحویل بصورت زیپ شده و پارت بندی شده ( هر پارت ۹۰ مگابایت )
- ✅ انجام تمام کارها بصورت خودکار و بدون نیاز به تنظیمات خاص
- ✅ پشتیبانی از دانلود همزمان چندین لینک
- ✅ امکان دسته بندی فایل های zip درون پوشه های هم نام با فایل
- ✅ امکان حذف یکجای تمام فایلهای دانلود شده 
- ✅ ذخیره سازی دائمی فایل ها در گیتهاب خودتان
- حتما بخش بروزرسانی ها را در پایین صفحه بخوانید.
- لطفا توجه کنید که برخی سرورهای ایرانی ای پی های خارج را مسدود کرده است مثلا سافت ۹۸ و امکان دانلود فایلهای آنها با استفاده از این ابزار نیست.
- 🌐 مرورگر وب اضافه شد به قسمت بروزرسانی مراجعه کنید و نحوه ی استفاده را مطلع شوید.
- 📹 آموزش ویدیویی استفاده از این ابزار به انتهای همین مطلب اضافه شد.
a
---

## 🔧 آموزش نصب

- درون این ریپازیتوری و در قسمت بالا روی دکمه ی fork بزنید.
- سپس در صورت نیاز میتوانید نام فورک را عوض کنید و در نهایت روی دکمه ی Create Fork بزنید.
- ریپازیتوری شما آماده است و اکنون میتوانید هر فایلی را که لینک دانلود آنرا دارید درون ریپازیتوری خود دانلود کنید و سپس از درون ریپازیتوری به سیستم خودتان دانلود کنید.

---

## 🎯 نحوه ی دانلود کردن فایل درون ریپازیتوری

- ۱- لینک خود را بصورت مستقیم مثل example.com/files/something.zip آماده کنید.
- ۲- به گیتهاب خود رفته و روی ریپازیتوری فورک شده بزنید و قسمت Actions را انتخاب کنید.
- ۳- در قسمت Actions شما لیست workflow ها را میبینید که یک عدد workflow داریم به اسم AVASAM - Download from URLs & Save to Repo  . روی آن بزنید و بعد از باز شدن روی Run Workflow بزنید آدرس دانلود از شما خواسته میشود و سپس شروع به دانلود .....

---


## 📂 فایلها را از کجا دانلود کنیم

همه فایلهای دانلود شده در پوشه ی downloads درون ریپازیتوری شما اضافه میشوند.فایل ها بصورت تکه های ۹۰ مگابایتی تقسیم بندی میشود مثلا اگر فایل شما ۳۰۰ مگابایت باشد باید ۴ عدد فایل دانلود شود و شما باید هر ۴ فایل را دانلود و سپس اکسترکت بکنید. برای اکسترکت کردن از 7zip استفاده کنید در لینوکس با دستور 7z x file.zip میتوانید همه ی فایل های تکه تکه را درون یک پوشه اکسترکت بکنید.
فایل اصلی دارای پسوند zip و پارت های دیگر دارای فرمت شماره گذاری شده به شکل z01 z02  و ... هستند. در ویندوز یا مک با نصب برنامه هایی مثل 7zip یا دیگر ابزارهای فشرده سازی میتوانید این فایلهای تکه تکه شده را یکجا اکسترکت بکنید.

---

## 🔔 بروزرسانی جدید: 

- امکان دسته بندی فایل های زیپ درون پوشه ها فراهم شد. اگر چندین فایل دانلود کنید و هر کدام به پارت های مختلف تقسیم بندی شوند این امکان بصورت اتوماتیک هر کدام را درون پوشه ای جدا دسته بندی میکند برای این امکان به بخش Actions رفته و روی گزینه ی Sort files بزنید و سپس گزینه ی run workflow را اجرا کنید.
- پاک کننده ی پوشه ی downloads اضافه شد در بخش Actions روی گزینه ی Clean download folder بزنید و سپس Run workflow را اجرا کنید تا پوشه ی downloads خالی شود.
- نام دانلودر در بخش Actions به Download from url تغییر پیدا کرده است.
- 🌐 مرورگر وب اضافه شد . برای استفاده از مرورگر به قسمت Actions روی گزینه ی browse web بزنید و سپس در قسمت run workflow ادرس سایت مقصد را بزنید. با این کار یک آرشیو با نام ادرس سایت و تاریخ آن لحظه ساخته میشود که درون آن اسکرین شات کامل صفحه به همراه فایل ها و لینک های صفحه قرار میگیره . همچنین فایل zip جهت دانلود در کنار پوشه ی تاریخ ساخته میشود که میتوانید یکجا دانلود کنید. یک فایل browse.md هم در مسیر اصلی ریپازیتوری اضافه میشود که شامل لیست تمام سایت هایی هست که دانلود کرده اید.


---

> راه های تکراری نتایج جدید رقم نمیزند. برای نتیجه ای جدید باید راهی جدید امتحان کرد

 
# <a href="https://avasam.ir/post/get-files-by-github" target="_blank" rel="do-follow follow sponsered">🔗 آموزش ویدیویی استفاده از این ابزار </a>

برای دریافت آموزش های بیشتر در پیام رسان بله عضو کانال ما باشید :‌
# 🔗 https://ble.ir/avasam_edu


موفق باشید.


---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

## فایل های دانلود شده در گیتهاب شما :

1 - [1WVPB7x9UlErXDnndwgNIJ](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/1WVPB7x9UlErXDnndwgNIJ)
2 - [25th.Hour.Dynamic](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/25th.Hour.Dynamic)
3 - [720P_4000K_45192525](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/720P_4000K_45192525)
4 - [892b70e5-78cb-4b3c-8e24-6b04c7e35100](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/892b70e5-78cb-4b3c-8e24-6b04c7e35100)
5 - [Cyberpunk.Edgerunners.Moon](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/Cyberpunk.Edgerunners.Moon)
6 - [Download](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/Download)
7 - [Git-2.54.0-64-bit](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/Git-2.54.0-64-bit)
8 - [Living.Room](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/Living.Room)
9 - [Music.TV.HQ](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/Music.TV.HQ)
10 - [PCSX2-v2.6.3-windows-x64-installer](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/PCSX2-v2.6.3-windows-x64-installer)
11 - [Release](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/Release)
12 - [Simple.System.3D](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/Simple.System.3D)
13 - [VBCABLE_Driver_Pack45](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/VBCABLE_Driver_Pack45)
14 - [YouTube-Music-Web-Setup-3.11.0](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/YouTube-Music-Web-Setup-3.11.0)
15 - [_moon_5133](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/_moon_5133)
16 - [doaction](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/doaction)
17 - [download64f](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/download64f)
18 - [index](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/index)
19 - [index-v1-a1](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/index-v1-a1)
20 - [lively_setup_x86_full_v2210](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/lively_setup_x86_full_v2210)
21 - [rpcs3-v0.0.40-19344-29b4577f_win64_aarch64_clang](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/rpcs3-v0.0.40-19344-29b4577f_win64_aarch64_clang)
22 - [rvV2.1](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/rvV2.1)
23 - [titanium_wallpaper_v122](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/titanium_wallpaper_v122)
24 - [v2rayN-windows-64](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/v2rayN-windows-64)
25 - [youtube-music-3.11.0-x64.nsis](https://github.com/ErshamtunseCNR/Downloader/tree/main/downloads/youtube-music-3.11.0-x64.nsis)

---
