---
title: 'استفاده از LapTop به عنوان مودم WiFi'
cover_image: /files/2017/04/itarfand-170.jpg
categories:
    - 'ترفند ویندوز'
tags:
    - WIFI
    - 'اشتراک اینترنت'
    - 'اشتراک گذاری'
    - 'اشتراک گذاری اینترنت گوشی'
    - 'اشتراک گذاری اینترنت لپ تاپ'
    - اینترنت
    - 'اینترنت لپ تاپ'
    - 'تبدیل گوشی به مودم وای فای'
    - 'تبدیل لپ تاپ به مودم وای فای'
    - 'تبدیل لپ تاپ به مودم وایرلس'
    - گوشی
    - 'لپ تاپ'
    - مودم
    - 'مودم سیم دار'
    - 'مودم مجازی در لپ تاپ'
    - 'مودم وای فای'
    - 'هات اسپات'
    - 'وای فای hotspot'
    - 'وای فای اشتراک گذاری اینترنت لپ تاپ'
---

گاهی مواقع شما نیاز به استفاده از اینترنت در دستگاه های مختلف دارید اما مودم *WiFi* همراه خود ندارید و یا می خواهید اینترنت لپ تاپ خود را به اشتراک بگذارید. در این پست از آی ترفند روش هایی را به شما آموزش می دهیم که توسط آن می توانید اینترنت *LapTop* خود را توسط *HotSpot* به راحتی به اشتراک بگذارید.

<span style="color: #0000ff;">**Hot Spot ویندوز ۱۰**</span>

ویندوز ۱۰ دارای امکانی است که توسط آن می توانید بدون هیچگونه نرم افزاری اینترنت خود را به اشتراک بگذارید.

برای این کار جمله *Change Mobile HotSpot Setting* را جستجو کنید تا صفحه زیر باز شود و پس از مطمئن شدن از وصل بودن به اینترنت می توانید گزینه مشخص شده را فعال کنید.

![mhkarami97](/files/2017/04/itarfand-164.jpg)  

اکنون می توانید بر روی *WiFi* به اشتراک گذاشته شده رمز قرار دهید و یا اگر از قبل ساخته اید رمز و نام آن را تغییر دهید.

![mhkarami97](/files/2017/04/itarfand-165.jpg)  

<span style="color: #0000ff;">**استفاده از نرم افزار Virtual Router**</span>

این نرم افزار را می توانید از[ ( این لینک )](https://virtualrouter.codeplex.com/) دانلود نمایید.

پس از اجرا با صفحه زیر روبرو می شوید که در آن می توانید نام و رمز عبور اینترنت به اشتراک گذاشته شده را تعیین کنید و همچنین افراد متصل به اینترنت را در آن مشاهده کنید.

![mhkarami97](/files/2017/04/itarfand-166.jpg)  

<span style="color: #0000ff;">**استفاده از کانفیگ ویندوز**</span>

این روش به هیچگونه نرم افزاری نیاز ندارد و توسط هر ویندوزی می توان آن را انجام داد.

برای این کار ابتدا *CMD* را به صورت *Run As Admin* اجرا کنید.

اکنون کد زیر را برای دانستن پشتیبانی کارت شبکه از این کار وارد کنید.

<span style="color: #008000;">netsh wlan show drivers</span>

اکنون باید در برابر گزینه مشخص شده کلمه *Yes* نوشته شده باشد.

![mhkarami97](/files/2017/04/itarfand-167.jpg)  

پس از پشتیبانی کارت شبکه باید برای شبکه به اشتراک گذاشته شده یک نام کاربری و یک رمز عبور قرار داد. برای این کار از کد زیر استفاده کنید.

<span style="color: #008000;">netsh wlan set hostednetwork mode=allow ssid=**YOURID** key=**PASSWORD**</span>

پس از این کار شما باید صفحه زیر را مشاهده کنید.

![mhkarami97](/files/2017/04/itarfand-168.jpg)  

اکنون برای فعال سازی شبکه ساخته شده کد زیر را وارد کنید.

<span style="color: #008000;">netsh wlan start hostednetwork</span>

هم اکنون شبکه شما ساخته شده است اما برای فعال سازی قابلیت استفاده از آن باید کارهای زیر را انجام دهید.

ابتدا با راست کلیک کردن بر روی آیکون اینترنت در کنار ساعت ویندوز در سمت چپ پایین گزینه *<span class="fontstyle0">Network and sharing center</span>* را انتخاب کنید و سپس از سمت چپ گزینه *Change Adapter Setting* را انتخاب کنید.

اکنون بر روی اینترنتی که از آن استفاده می کنید و می خواهید آن را به اشتراک بگذارید راست کلیک کنید مانند عکس زیر عمل کنید.

![mhkarami97](/files/2017/04/itarfand-169.jpg)  

برای غی فعال سازی این امکان می توانید از کد زیر استفاده کنید.

<span class="fontstyle0" style="color: #008000;"> netsh wlan stop hostednetwork </span>