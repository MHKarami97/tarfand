---
title: 'جلوگیری از نصب نرم افزار ها و بازکردن فلش در ویندوز'
cover_image: /files/2016/12/itarfand-109.jpg
categories:
    - 'ترفند ویندوز'
tags:
    - '1st Security Software Center'
    - 'stop inastall software'
    - 'استاپ اینستالیشن تول'
    - 'ایجاد ممنوعیت برای نصب نرم افزارها'
    - 'ترفند ویندوز'
    - 'ترفند ویندوز 10'
    - 'ترفند ویندوز 8'
    - 'ترفندهای ابزار Windows Group Policy'
    - 'تنظیمات group policy در ویندوز 7'
    - 'تنظیمات ویندوز'
    - 'جلوگیری از باز کردن حافظه های جانبی'
    - 'جلوگیری از نصب نرم افزار'
    - 'جلوگیری از ویروسی شدن ویندوز'
    - 'جلویگری از نصب بازی در رایانه'
    - 'حفاظت از رایانه ها'
    - 'دانلود نرم افزار Stop Software Installation Tool'
    - 'ممانعت از نصب'
    - 'نرم افزار stop instsllsation'
    - 'نرم افزار محافظت از سیستم در برابر نصب برنامه های ناخواسته'
    - ویندوز
---

گاهی مواقع شما از یک رایانه برای شغل خود استفاده می کنید و نصب نرم افزار یا بازی بر روی آن باعث خراب شدن ویندوز و پاک شدن اطلاعات آن می شود و یا در صورت فصل یک حافظه جانبی مانند فلش ممکن است رایانه شما ویروسی شود. همچنین شما نمی خواهید که کودکانتان هر بازی یا نرم افزاری را بر روی رایانه نصب کنند. در این پست از آی ترفند این کار را بدون نیاز به هیچ گونه نرم افزاری را به شما آموزش می دهیم.

ابتدا توسط کلید های ترکیبی *Win+R* قسمت *Run* ویندوز را باز کنید و سپس کلمه *gpedit.msc* را در آن بنویسید.

![mhkarami97](/files/2016/12/itarfand-110.jpg)  

<span style="color: #0000ff;">**غیر فعال کردن امکان نصب نرم افزار و بازی**</span>

ابتدا به بخش زیر بروید و سپس گزینه *Turn Of Windows Installer* را انتخاب کنید.

<span style="color: #993300;">Administrative Templates + Windows Components + Windows Installer</span>

![mhkarami97](/files/2016/12/itarfand-111.jpg)  

اکنون گزینه *Enable* و سپس گزینه *Always* را انتخاب کنید.

 ![mhkarami97](/files/2016/12/itarfand-112.jpg)  

<span style="color: #0000ff;">**غیر فعال کردن امکان وصل شدن فلش به رایانه**</span>

برای این کار ابتدا به مسیر زیر بروید.

<span style="color: #993300;">Administrative Templates + System</span>

اکنون با توجه به نیاز خود یکی از گزینه ها را انتخاب کنید.

<span style="color: #800080;">۱)Removable Disks: Deny exeute access</span>

<span style="color: #800080;">۲)Removable Disks: Deny read access</span>

<span style="color: #800080;">۳)Removable Disks: Deny write access</span>

<span style="color: #800080;">۱)جلوگیری از باز شدن فلش</span>

<span style="color: #800080;">۲)جلوگیری از خواندن اطلاعات فلش</span>

<span style="color: #800080;">۳)جلوگیری از ریختن اطلاعات به فلش</span>

![mhkarami97](/files/2016/12/itarfand-113.jpg)  