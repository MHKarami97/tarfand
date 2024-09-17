---
title: 'نصب مجازی Kali Linux بر روی VMware'
img: /files/2017/05/itarfand-229.jpg
categories:
    - 'ترفند نرم افزار'
tags:
    - 'linux kali دبیان چیست؟'
    - 'آموزش لینوکس برای هک'
    - 'آموزش لینوکس کالی'
    - 'آموزش نصب kali linux در vmware workstation 10'
    - 'آموزش نصب کالی لینوکس 2'
    - 'آموزش نصب کالی لینوکس 2016 در vmware'
    - 'آموزش نصب کالی لینوکس در virtualbox'
    - 'آموزش نصب کالی لینوکس در vmware 12'
    - 'آموزش نصب لینوکس کالی'
    - 'دانلود vmware work station'
    - 'دانلود کالی لینوکس 2'
    - 'لینوکس کالی چیست؟'
    - 'لینوکس هکینگ آموزش نصب Debian'
    - 'نصب لینوکس کالی'
---

یکی از سیستم عامل های محبوب در دنیا *Linux* می باشد که نسخه *Kali* آن برای تست امنیت توسط افراد مختلف استفاده می شود. در این پست از آی ترفند آموزش نصب از سیستم عامل را بر روی نرم افزار مجازی ساز *VMware* برای شما آموزش می دهیم.

<span style="color: #0000ff;">**ساخت یک Visual Machine**</span>

بعد از نصب نرم افزار *vmware* بر روی *Create A New Visual Machine* کلیک کنید.

![mhkarami97](/files/2017/05/itarfand-186.jpg)  

اکنون مانند عکس های زیر عمل کنید:

![mhkarami97](/files/2017/05/itarfand-187.jpg)  
![mhkarami97](/files/2017/05/itarfand-188.jpg)  
![mhkarami97](/files/2017/05/itarfand-189.jpg)  

انتخاب فایل iso برای نصب سیستم عمل

![mhkarami97](/files/2017/05/itarfand-190.jpg)  
![mhkarami97](/files/2017/05/itarfand-191.jpg)  
![mhkarami97](/files/2017/05/itarfand-192.jpg)  

تعداد پروسه های قابل استفاده توسط نرم افزار از cpu

![mhkarami97](/files/2017/05/itarfand-193.jpg)  

مقدار رم قابل استفاده

![mhkarami97](/files/2017/05/itarfand-194.jpg)  
![mhkarami97](/files/2017/05/itarfand-195.jpg)  
![mhkarami97](/files/2017/05/itarfand-197n.jpg)  
![mhkarami97](/files/2017/05/itarfand-198.jpg)  
![mhkarami97](/files/2017/05/itarfand-199.jpg)  

حافظه تخصیص داده شده به سیستم عامل

![mhkarami97](/files/2017/05/itarfand-200.jpg)  
![mhkarami97](/files/2017/05/itarfand-201.jpg)  
![mhkarami97](/files/2017/05/itarfand-202.jpg)  

برای هماهنگی سیستم عامل با صفحه های ۴K می توانید مانند عکس بالا گزینه ۳۸۴۰\*۲۱۶۰ را انتخاب کنید.

![mhkarami97](/files/2017/05/itarfand-203.jpg)  

اکنون سیستم عامل شما آماده نصب است ، پس گزینه *Power On Visual Machine* را انتخاب کنید.

مانند عکس زیر گزینه *Graphical Install* را انتخاب کنید و سپس طبق عکس ها پیش بروید.

![mhkarami97](/files/2017/05/itarfand-204.jpg)  
![mhkarami97](/files/2017/05/itarfand-205.jpg)  
![mhkarami97](/files/2017/05/itarfand-206.jpg)  
![mhkarami97](/files/2017/05/itarfand-207.jpg)  
![mhkarami97](/files/2017/05/itarfand-208.jpg)  
![mhkarami97](/files/2017/05/itarfand-209.jpg)  
![mhkarami97](/files/2017/05/itarfand-210.jpg)  
![mhkarami97](/files/2017/05/itarfand-211.jpg)  
![mhkarami97](/files/2017/05/itarfand-212.jpg)  
![mhkarami97](/files/2017/05/itarfand-213.jpg)  
![mhkarami97](/files/2017/05/itarfand-214.jpg)  
![mhkarami97](/files/2017/05/itarfand-215.jpg)  

![mhkarami97](/files/2017/05/itarfand-216-1.jpg)  
![mhkarami97](/files/2017/05/itarfand-217.jpg)  
![mhkarami97](/files/2017/05/itarfand-218.jpg)  
![mhkarami97](/files/2017/05/itarfand-219.jpg)  
![mhkarami97](/files/2017/05/itarfand-220.jpg)  
![mhkarami97](/files/2017/05/itarfand-221.jpg)  
![mhkarami97](/files/2017/05/itarfand-222.jpg)  

نام کابری *root* می باشد.  
![mhkarami97](/files/2017/05/itarfand-223.jpg)  

<span style="color: #0000ff;">**نصب VMware Tools**</span>

همان طور که مشاهده می کنید صفحه نمایش کوچک است. طبق عکس های زیر پیش بروید تا گرافیک سیستم عامل درست شود.

![mhkarami97](/files/2017/05/itarfand-224.jpg)  

بر روی آیکون پوشه که در عکس زیر با فلش آبی مشخص شده کلیک کنید.

![mhkarami97](/files/2017/05/itarfand-225.jpg)  

پوشه را بکشید و در صفحه اول رها کنید و سپس بر روی آیکون ترمینال را که با آیکون سبز مشخص شده کلیک کنید.

اکنون در صفحه باز شده کد های زیر را وارد کنید.

<span style="color: #ff6600;">*نکته: هر خط را وارد کنید و سپس Enter را بزنید.*</span>

<span style="color: #008000;">Cd Desktop</span>

<span style="color: #008000;">ls</span>

<span style="color: #000000;">آدرس زیر نام فایلی است که در صفحه اول کپی کرده اید.</span>

<span style="color: #008000;">tar -xf /root/Desktop/*VMwareTools-10.0.10-431679.tar.gz*</span>

<span style="color: #008000;">ls</span>

<span style="color: #008000;">cd vmware-tools-distrib</span>

<span style="color: #008000;">ls</span>

<span style="color: #008000;">perl vmware-install.pl</span>

<span style="color: #000000;">در صورت مشاهده پیغام زیر شما موفق به نصب شده اید.</span>

<span style="color: #008000;">enter until: enjoy</span>

اکنون با انتخاب گزینه *Setting* از دو روش زیر که با آیکون قرمز مشخص شده اند می توانید به تنظیمات دسترسی پیدا کنید.

![mhkarami97](/files/2017/05/itarfand-226.jpg)  

<span style="color: #0000ff;">**تغییر اندازه صفحه نمایش و نصب زبان فارسی**</span>

توسط دو قسمتی که در عکس بالا مشخص شده اند می توانید زبان فارسی را بر روی لینوکس نصب کنید و همچنین صفحه نمایش را کنترل کنید.

![mhkarami97](/files/2017/05/itarfand-228-1.jpg)  

![mhkarami97](/files/2017/05/itarfand-227.jpg)  

سیستم عامل لینوکس دارای جزئیات بسیاری می باشد که می توانید آن ها را در قسمت نظرات و یا انجمن بپرسید.