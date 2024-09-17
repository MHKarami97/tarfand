---
title: 'غیر فعال کردن Lock Screen در ویندوز ۱۰'
image: /files/2016/09/itarfand-82.jpg
categories:
    - 'ترفند ویندوز'
tags:
    - 'change lock screen'
    - 'lock screen'
    - 'ترفند ویندوز'
    - 'تغییر لوک اسکرین ویندوز'
    - 'غیر فعال کردن lock screen ویندوز 10'
    - 'غیرفعال کردن lock screen'
    - 'لوک اسکرین'
    - 'ورژن جدید ویندوز 10'
    - 'ویندوز 10'
---

*Lock Screen* صفحه ای می باشد که قبل از وارد کردن پسورد ویندوز نمایش داده می شود که دارای یک منظره به همراه ساعت می باشد. یکی از تغییراتی که در ورژن جدید ویندوز ۱۰ ایجاد شده است عدم امکان غیر فعال کردن *Lock Screen* به صورت پیش فرض در تنظیمات ویندوز ۱۰ می باشد. در این پست از آی ترفند آموزش غیر فعال کردن *Lock Screen* را برای شما آماده کرده ایم.

**<span style="color: #0000ff;">روش اول غیر فعال سازی لوک اسکرین</span>**

ابتدا کلمه *Edit Group Policy* را در ویندوز ۱۰ جستجو کنید و سپس آن را اجرا کنید.

![itarfand-75](/files/2016/09/itarfand-75.jpg)

اکنون به قسمت مشخص شده در عکس زیر بروید و گزینه *Do Not Display The Lock Screen* را انتخاب کنید.

![itarfand-76](/files/2016/09/itarfand-76.jpg)

برای غیر فعال کردن *Lock Screen* بر روی *Enabled* کلیک کنید.

![itarfand-77](/files/2016/09/itarfand-77.jpg)

<span style="color: #0000ff;">**روش دوم غیر فعال سازی لوک اسکرین**</span>

ابتدا کلمه *Regedit* را در ویندوز ۱۰ جستجو کنید.

![itarfand-78](/files/2016/09/itarfand-78.jpg)

اکنون به آدرس زیر بروید.

<span style="color: #993300;">*HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows*</span>

بر روی *Windows* راست کلیک کنید و یک *Key* جدید با نام *Personalization* بسازید تا یک پوشه ساخته شود.

![itarfand-79](/files/2016/09/itarfand-79.jpg)

اکنون مانند عکس زیر در پوشه ساخته شده راست کلیک کنید و گزینه مشخص شده را ایجاد کنید و نام آن را *NoLockScreen* قرار دهید.

![itarfand-80](/files/2016/09/itarfand-80-1.jpg)

بر روی فایل ایجاد شده کلیک کنید و عدد ۰ را به عدد ۱ تغییر دهید.

![itarfand-81](/files/2016/09/itarfand-81.jpg)

بعد از انجام یکی از کارهای بالا *Lock Screen* شما غیر فعال می شود.