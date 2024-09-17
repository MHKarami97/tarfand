---
title: 'غیر فعال کردن پورت usb در رایانه های ویندوزی'
img: /files/2017/09/itarfand-497-min.jpg
categories:
    - 'ترفند ویندوز'
tags:
    - 'disable usb drives group policy server 2008 r2'
    - 'disable usb drives group policy server 2012 r2'
    - 'disable usb ports group policy server 2012'
    - 'disable usb ports windows 7 local group policy'
    - 'group policy'
    - 'group policy disable usb storage but not keyboard mouse'
    - 'how to block usb port for domain user'
    - 'how to block usb through group policy in windows server 2008 r2'
    - 'how to block usb through group policy in windows server 2012'
    - usb
    - 'باز كردن پورت usb'
    - 'بستن پورت usb از طریق group policy در windows server 2008 r2'
    - 'بستن پورت usb از طریق رجیستری'
    - 'بستن پورت usb در active directory'
    - 'بستن پورت usb در ویندوز 7'
    - 'بستن پورت usb در ویندوز سرور 2008'
    - 'پورت USB'
    - 'ترفند usb'
    - 'ترفند رجیستری'
    - 'ترفند ویندوز'
    - 'درگاه USB'
    - رجیستری
    - 'روش بستن پورت usb در شبکه از طریق group policy'
    - 'نرم افزار بستن پورت usb در شبکه'
    - 'ویندوز 10'
    - 'یو اس بی'
---

یکی از مهمترین رابط های در دستگاه ها ، *usb* می باشد. هرچند این پورت ورودی مهمی در لپ تاپ ها و کامپیوتر ها می باشد اما در برخی ادارات و سازمان ها برای جلوگیری از خراب کاری و جلوگیری از سرقت آن را غیرفعال می کنند. در این پست از آی ترفند روش غیر فعال کردن این پورت را به شما آموزش می دهیم.

<span style="color: #0000ff;">**استفاده از Device Manager**</span>

برای این کار ابتدا کلمه *Computer Management* را در ویندوز جستجو کنید تا صفحه زیر باز شود. در صفحه باز شده از سمت چپ به قسمت *Device Manager* بروید و قسمت *Universal Serial Bus Controller* را پیدا کنید. اکنون هر کدام از پورت ها را که می خواهید با راست کلیک بر روی و گزینه *Disable* غیر فعال کنید.

![mhkarami97](/files/2017/09/itarfand-491-min.jpg)  

<span style="color: #0000ff;">**استفاده از Register**</span>

ابتدا کلمه *regedit* را در ویندوز جستجو کنید تا بخش رجیستری ویندوز باز شود. در صفحه باز شده از سمت چپ به آدرس زیر بروید.

<span style="color: #339966;">HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\USBSTOR</span>

اکنون بر روی *Start* دو بار کلیک کنید.

![mhkarami97](/files/2017/09/itarfand-492-min.jpg)  

برای غیر فعال کردن تمام پورت های *usb* مقدار ۴ را در صفحه باز شده وارد کنید.

![mhkarami97](/files/2017/09/itarfand-493-min.jpg)  

<span style="color: #0000ff;">**استفاده از Local Group Polcy**</span>

ابتدا به مسیر بخش *Device Manager* بروید و بر روی پورتی که می خواهید غیر فعال کنید راست کلیک کنید و گزینه *Properties* را انتخاب کنید.

در صفحه باز شده به تب *Details* بروید و گزینه *Hardware Ids* را انتخاب کنید و کد مشخص شده در عکس را کپی کنید.

![mhkarami97](/files/2017/09/itarfand-494-min.jpg)  

اکنون کلمه *Edit Group Policy* را در ویندوز جستجو کنید. اکنون از سمت چپ به آدرس زیر بروید.

<span style="color: #339966;">Administrative Templates / System / Device Installation Restrictions</span>

اکنون بر روی گزینه *Prevent Installation Of Device That Match Any These Devices* کلیک کنید.

![mhkarami97](/files/2017/09/itarfand-495-min.jpg)  

اکنون ابتدا بر روی *Enable* و سپس *Show* کلیک کنید و کدی را که کپی کرده بودید را مانند عکس وارد کنید و سپس بر روی *Ok* کلیک کنید.

![mhkarami97](/files/2017/09/itarfand-496-min.jpg)  

بعد از انجام کارهای بالا پورت *usb* دستگاه شما کاملا بسته خواهد شد.