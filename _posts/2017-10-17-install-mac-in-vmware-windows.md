---
title: 'نصب سیستم عامل مک بر روی VMWare به صورت مجازی'
cover_image: /files/2017/10/itarfand-560-min-1.jpg
categories:
    - 'ترفند نرم افزار'
tags:
    - 'آموزش نصب مکینتاش روی ویندوز'
    - 'آموزش نصب هکینتاش'
    - 'دانلود mac os sierra برای vmware'
    - 'دانلود مک برای pc'
    - 'دانلود مک برای vmware'
    - 'نصب sierra روی vmware'
    - 'نصب مک روی pc'
    - 'نصب مک روی لپ تاپ'
---

یکی از معروف ترین سیستم عامل های موجود که افراد دارای لپ تاپ های اپل می باشند استفاده می کنند سیستم عامل مک می باشد. در این پست از آی ترفند روشی را به شما آموزش می دهیم که توسط آن می توانید این سیستم عامل را بدون نیاز به خرید لپ تاپی دیگر و در کنار ویندوز خود نصب کنید.

<span style="color: #0000ff;">**پیش نیاز**</span>

ابتدا از *[(این لینک)](https://mega.nz/#F!kZd01ZRC!j49bznphGjK3mOGXo9c7Vw)* نرم افزار *Unlocker* را برای نصب شدن مک بر روی *vmware* را دانلود کنید. سپس *win-install.cmd* را به صورت *Admin* اجرا کنید.

![mhkarami97](/files/2017/10/itarfand-534-min.jpg)  

اکنون از [*(این لینک)* ](https://drive.google.com/drive/folders/0Bxo4zVlSzKr6c0hSSDhjR2pFVzg?usp=sharing)و یا [*(این لینک)*](https://drive.google.com/drive/folders/0Bxo4zVlSzKr6dXBreFZKcFRHR0U?usp=sharing) فایل *vmdk* نصب مک را دانلود کنید.

<span style="color: #0000ff;">**نصب Mac**</span>

سپس نرم افزار *vmware* را اجرا کنید و سپس مانند عکس های زیر عمل کنید:

![mhkarami97](/files/2017/10/itarfand-535-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-536-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-537-min.jpg)  

اکنون در صفحه باز شده نام و محل نصب مک را انتخاب کنید.

![mhkarami97](/files/2017/10/itarfand-538-min.jpg)  

در صفحه باز شده می توانید مقدار حافظه سیستم عامل را انتخاب کنید.

![mhkarami97](/files/2017/10/itarfand-539-min.jpg)  

سپس بر روی *Finish* کلیک کنید.

![mhkarami97](/files/2017/10/itarfand-540-min.jpg)  

اکنون بر روی *Edit* کلیک کنید.

![mhkarami97](/files/2017/10/itarfand-541-min.jpg)  

اکنون گزینه *Hard Disk* را انتخاب کنید و سپس بر روی *Remove* کلیک کنید.

![mhkarami97](/files/2017/10/itarfand-542-min.jpg)  

سپس بر روی *Add* کلیک کنید و مانند عکس های زیر عمل کنید.

![mhkarami97](/files/2017/10/itarfand-543-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-544-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-545-min.jpg)  

سپس در صفحه باز شده فایل *vmdk* دانلود شده را وارد کنید.

![mhkarami97](/files/2017/10/itarfand-546-min.jpg)  

اکنون به محل نصب مک بروید و فایلی با فرمت *vmx* را با *NotePad* باز کنید و کد زیر را به آخر آن اضافه کنید:

<span style="color: #008000;">smc.version=”0″</span>

![mhkarami97](/files/2017/10/itarfand-547-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-547-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-547-min-1.jpg)  

سپس نرم افزار *vmware* را اجرا کنید و بر روی *Run* کلیک کنید تا نصب مک آغاز شود.

![mhkarami97](/files/2017/10/itarfand-548-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-549-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-550-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-551-min.jpg)  

در صفحه زیر می توانید *apple ID* خود را وارد کنید و یا بر روی عدم وارد شدن کلیک کنید.

![mhkarami97](/files/2017/10/itarfand-552-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-553-min-1.jpg)  

![mhkarami97](/files/2017/10/itarfand-554-min.jpg)  

سیستم عامل مک شما اکنون نصب شده است.

<span style="color: #0000ff;">**نصب VMWare Tools**</span>

با نصب این ابزار می توانید از امکانات مک به صورت کامل استفاده کنید و همچنین اندازه صفحه نمایش را تغییر دهید.

برای این کار گزینه زیر را انتخاب کنید:

![mhkarami97](/files/2017/10/itarfand-555-min.jpg)  

سپس مانند عکس زیر عمل کنید.

![mhkarami97](/files/2017/10/itarfand-556-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-557-min.jpg)  

<span style="color: #0000ff;">**نمونه**</span>

![mhkarami97](/files/2017/10/itarfand-559-min.jpg)  

![mhkarami97](/files/2017/10/itarfand-547-min.jpg)  