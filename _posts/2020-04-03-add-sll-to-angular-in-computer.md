---
title: 'اضافه کردن SSL به وبسایت در حال برنامه نویسی در Localhost'
cover_image: /files/2020/04/itarfand-896-min.jpg
categories:
    - 'ترفند برنامه نویسی'
tags:
    - 'آموزش انگولار'
    - 'افزودن ssl به انگولار'
    - 'بهترین ssl رایگان'
    - 'ترفند برنامه نویسی'
    - 'نصب ssl رایگان روی cpanel'
    - 'نصب ssl روی apache'
    - 'نصب ssl روی xampp'
---

یکی از مشکلاتی که برنامه نویسان در زمان نوشتن یک برنامه در سیستم لوکال خود دارند، نیاز به گواهی SSL یا همان Https می باشد. در این پست از آی ترفند آموزش ساخت گواهی رایگان و اضافه کردن آن به برنامه Angular برای شما آماده شده است.

ابتدا پروژه زیر را از github کلون کنید.

<https://github.com/RubenVermeulen/generate-trusted-ssl-certificate>

![mhkarami97](/files/2020/04/itarfand-884-min.jpg)  
سپس GitBash را اجرا کنید و به محلی که اسکریپ بالا را کلون کرده اید بروید و دستور زیر را اجرا کنید تا تو فایل با نام ها server.crt و server.key ساخته شود.

bash generate.sh

![mhkarami97](/files/2020/04/itarfand-885-min.jpg)  
اکنون توسط Win+R قسمت Run ویندوز را اجرا کنید و سپس mmc را در آن تایپ کنید.

![mhkarami97](/files/2020/04/itarfand-886-min.jpg)  
از سمت چپ گزینه Add/Remove Snap-in را انتخاب کنید.

![mhkarami97](/files/2020/04/itarfand-887-min.jpg)  
در قسمت باز شده گزینه certificate و سپس My User Account را انتخاب کنید.

![mhkarami97](/files/2020/04/itarfand-888-min.jpg)  
اکنون یک Console 1 جدید اجرا می شود. در آن به آدرس عکس ، certificates ، بروید.

![mhkarami97](/files/2020/04/itarfand-889-min.jpg)  
بر روی آن راست کلیک کنید و از قسمت All Task گزینه Import را انتخاب کنید.

![mhkarami97](/files/2020/04/itarfand-890-min.jpg)  
سپس مانند عکس های زیر پیش بروید و فایل ساخته شده توسط روش اول را انتخاب کنید.

![mhkarami97](/files/2020/04/itarfand-891-min.jpg)  
![mhkarami97](/files/2020/04/itarfand-892-min.jpg)  
![mhkarami97](/files/2020/04/itarfand-893-min.jpg)  
اکنون به طور مثال برای قرار دادن این گواهی بر روی پروژه انگولار کافی است فایل package.json پروژه را باز کنید و قسمت Start را مانند عکس زیر تغییر دهید.

“start”: “ng serve –ssl –ssl-key d:\\certificates\\server.key –ssl-cert d:\\certificates\\server.crt”

که در کد بالا باید آدرس فایل های خود را قرار دهید.

![mhkarami97](/files/2020/04/itarfand-894-min.jpg)  
سپس پروژه بصورت خودکار در حالت https اجرا می شود.

![mhkarami97](/files/2020/04/itarfand-895-min.jpg)  
