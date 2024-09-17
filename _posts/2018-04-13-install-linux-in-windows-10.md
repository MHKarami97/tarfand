---
id: 1859
title: 'آموزش نصب Linux بر روی ویندوز ۱۰'
date: '2018-04-13T06:54:57+04:30'
author: 'I AM IRANIAN'
layout: post
guid: 'https://itarfand.com/?p=1859'
permalink: /install-linux-in-windows-10/
onesignal_meta_box_present:
    - ''
onesignal_send_notification:
    - ''
image: /files/2018/04/itarfand-703-min.jpg
categories:
    - 'ترفند ویندوز'
tags:
    - 'آموزش نصب کالی لینوکس 2016'
    - 'آموزش نصب کالی لینوکس 2017 در کنار ویندوز 10'
    - 'آموزش نصب کالی لینوکس در vmware'
    - 'آموزش نصب کالی لینوکس در کنار ویندوز 10'
    - 'آموزش نصب کالی لینوکس روی فلش'
    - 'ابزار هک'
    - امنیت
    - 'ترفند ویندوز'
    - 'تست نفوذ'
    - 'دانلود سیستم عامل Kali Linux'
    - 'دانلود کالی'
    - 'دانلود لینوکس کالی'
    - 'دانلود نرم افزار Kali Linux'
    - 'دانلود نسخه کالی از لینوکس'
    - 'سیستم عامل'
    - 'سیستم عامل لینوکس'
    - 'سیستم عامل مناسب هک'
    - 'سیستم عامل هک'
    - لینوکس
    - 'نرم افزار هک سفید'
    - 'نصب لینوکس در کنار ویندوز'
    - هک
---

یکی از ویژگی هایی که در آپدیت جدید ویندوز به آن اضافه شده است ، ویژگی ای به نام *Windows SubSystem Linux* می باشد که اجازه نصب سیستم عامل هایی برپایه هسته لینوکس مانند *Kali Linux* را بدون نیاز به نصب نرم افزارهای اضافی بر روی ویندوز می دهد. پس با آی ترفند همراه شوید تا آموزش نصب این سیستم عامل به همراه محیط گرافیکی را یاد بگیرید.

<span style="color: #0000ff;">**دانلود لینوکس**</span>

ابتدا به *Microsoft Store* بروید و نسخه مورد نظر خود از لینوکس را دانلود کنید.

![mhkarami97](/files/2018/04/itarfand-684-min.jpg)

اکنون فایلی اجرایی آن را که به *Start* اضافه شده است را اجرا کنید تا با صفحه زیر روبرو شوید.

در این صفحه باید یک کاربر *UNIX* بسازید. برای این کار نام کاربری و رمز عبور خود را وارد کنید و به این نکته توجه کنید که رمز عبور نمایش داده نمی شود.

![mhkarami97](/files/2018/04/itarfand-685-min.jpg)

اگر فایل اجرایی لینوکس اجرا نشد کافی است *Windows PowerShell* را به صورت *Admin* اجرا کنید و جمله زیر را در آن بنویسید.

<span style="color: #008000;">Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux</span>

![mhkarami97](/files/2018/04/itarfand-687-min.jpg)

اگر باز هم مشکل حل نشد به تنظیمات ویندوز بروید و در مسیر زیر محل نصب پیش فرض اپ های ویندوز را تغییر دهید.

<span style="color: #008000;"> Settings -&gt; Storage -&gt; More Storage Settings: Change where new content is saved</span>

![mhkarami97](/files/2018/04/itarfand-688-min.jpg)

<span style="color: #0000ff;">**نصب محیط گرافیکی**</span>

اپی که بر روی ویندوز نصب می کنید به طور پیش فرض فقط محیط ترمینال لینوکس می باشد و محیط گرافیکی ندارد. برای نصب محیط گرافیکی کافی است آموزش زیر را دنبال کنید.

بعد از اجرا لینوکس جمله زیر را در آن وارد کنید.

<span style="color: #008000;">sudo apt-get install wget</span>

![mhkarami97](/files/2018/04/itarfand-686-min.jpg)

بعد از وارد کردن شما باید رمز عبور کاربر خود را نیز وارد کنید.

![mhkarami97](/files/2018/04/itarfand-691-min.jpg)

یکی از مشکلات رایج متن های زیر می باشد که اگر شما نیز با آن مواجه شدید کافی است آموزش زیر را دنبال کنید.

![mhkarami97](/files/2018/04/itarfand-692-min.jpg)

ابتدا جمله زیر را وارد کنید.

<span style="color: #008000;">sudo apt-get update</span>

![mhkarami97](/files/2018/04/itarfand-693-min.jpg)

اکنون جمله زیر را وارد کنید.

<span style="color: #008000;">sudo apt-get remove wget</span>

و سپس جمله زیر:

<span style="color: #008000;">sudo apt-get upgrade</span>

![mhkarami97](/files/2018/04/itarfand-694-min.jpg)

اکنون باید کمی صبر کنید تا هسته لینوکس تعمیر و آپدیت شود.

![mhkarami97](/files/2018/04/itarfand-695-min.jpg)

اکنون می توانید ویژگی *wget* را با موفقیت نصب کنید.

بعد از نصب ویجت بالا جمله زیر را وارد کنید.

<span style="color: #008000;">wget https://kali.sh/xfce4.sh</span>

![mhkarami97](/files/2018/04/itarfand-696-min.jpg)

اکنون باید دستور زیر را وارد کنید تا محیط گرافیکی نصب شود. دقت کنید که این کار زمان بر می باشد.

<span style="color: #008000;">sudo sh xfce4.sh</span>

![mhkarami97](/files/2018/04/itarfand-697-min.jpg)

![mhkarami97](/files/2018/04/itarfand-698-min.jpg)

بعد از نصب کافی است دستور زیر را وارد کنید تا محیط گرافیکی شروع به کار کند.

<span style="color: #008000;">sudo /etc/init.d/xrdp start</span>

![mhkarami97](/files/2018/04/itarfand-699-min.jpg)

نکته مهم این است که محیط گرافیکی بر روی پورت ۳۳۹۰ کار می کند و حتما باید این پورت خالی باشد.

به طور مثال اگر نرم افزار *VMWare* بر روی ویندوز شما نصب است باید *vmware-hostd.exe* را از Task Manager ببندید.

برای دسترسی به محیط گرافیکی لینوکس کافی است ابزار *Remote Desktop* ویندوز را اجرا کنید و آدرس ۱۲۷٫۰٫۰٫۱:۳۳۹۰ را در آن وارد کنید.

![mhkarami97](/files/2018/04/itarfand-700-min.jpg)

اکنون با صفحه زیر روبرو می شوید که در آن باید نام کاربری و رمز عبوری که در اول آموزش ساخته اید را در آن وارد کنید.

![mhkarami97](/files/2018/04/itarfand-701-min.jpg)

همان طور که می بینید لینوکس شما با موفقیت نصب شده است.

![mhkarami97](/files/2018/04/itarfand-702-min.jpg)

برای Stop کردن این سرویس هم کافی است جمله زیر را در ترمینال وارد کنید.

<span style="color: #008000;">sudo /etc/init.d/xrdp stop</span>

<span style="color: #0000ff;">**مشکلات رایج**</span>

یکی از مسکلات رایج فراموشی رمز عبور می باشد. برای تغییر آن کافی است یوزر اصلی را بر روی *Root* قرار دهید و آموزش زیر را دنبال کنید.

برای تغییر یوزر پیش فرض *CMD* ویندوز را به صورت *Admin* اجرا کنید و جمله زیر را در آن وارد کنید.

<span style="color: #008000;">kali config –default-user root</span>

سپس در ترمینال لینوکس جمله زیر را وارد کنید و دقت کنید که *soltan* نام کاربری شما می باشد.

<span style="color: #008000;">passwd soltan</span>

![mhkarami97](/files/2018/04/itarfand-689-min.jpg)

اکنون می توانید رمز عبور خود را تغییر دهید.

![mhkarami97](/files/2018/04/itarfand-690-min.jpg)

برای تغییر دوباره یوزر پیش فرض جمله زیر را در CMD وارد کنید.

<span style="color: #008000;">kali config –default-user soltan</span>

دقت کنید که *kali* با توجه به نوع لینوکس شما تغییر می کند.