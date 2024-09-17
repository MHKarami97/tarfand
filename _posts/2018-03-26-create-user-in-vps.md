---
title: 'ساخت User در سرور مجازی یا VPS'
cover_image: /files/2018/03/itarfand-683-min.jpg
categories:
    - 'ترفند ویندوز'
tags:
    - 'اموزش ساخت اکانت در vps'
    - 'پنهان سازی یک یوزر'
    - 'ترفند ویندوز'
    - 'ساخت یوزر در vps با cmd'
    - 'ساخت یوزر در خط فرمان ویندوز'
    - 'ساخت یوزر در وی پی اس 2012'
    - 'ساخت یوزر در وی پی اس با cmd'
    - 'ساخت یوزر در ویندوز 2008'
    - 'ساخت یوزر در ویندوز سرور 2008'
    - 'ساخت یوزر مخفی در وی پی اس'
    - 'ساخت یوزر هیدن'
    - 'طریقه ساخت یوزر در vps'
    - 'یوزر مخفی با دسترسی ادمین'
---

در این پست از آی ترفند آموزش ساخت یوزر را در سروهای مجازی یا وی پی اس را برای شما آماده کرده ایم که توسط آن می توانید یوزهایی با دسترسی های مختلف بسازید و همچنین آن ها را مخفی کنید.

ابتدا با کلید های ترکیبی *Win+R* قسمت *Run* را باز کنید و کلمه *Lusrmgr.msc* را در آن جستجو کنید.

![mhkarami97](/files/2018/03/itarfand-676-min.jpg)  

اکنون در صفحه باز شده بر روی *User* کلیک کنید.

![mhkarami97](/files/2018/03/itarfand-677-min.jpg)  

بر روی صفحه راست کلیک کنید و گزینه *New User* را انتخاب کنید.

![mhkarami97](/files/2018/03/itarfand-678-min.jpg)  

اکنون یک نام کاربری وارد کنید و همچنین یک رمز برای آن قرار دهید.

برای یوزر مورد نظر می توانید تنظیمات زیر را اعمال کنید:

- <span style="color: #008000;">user must change password at next logon : یوزر پس از اولین ورود باید پسورد خود را تغییر دهد.</span>
- <span style="color: #008000;">User cannot change password : یوزر نمی تواند پسورد خود را تغییر دهد.</span>
- <span style="color: #008000;">Password never expires : پسورد منقضی نشود.</span>
- <span style="color: #008000;">Account is disabled : یوزر غیر فعال باشد.</span>

![mhkarami97](/files/2018/03/itarfand-679-min.jpg)  

برای تغییر گروه کاربری یوزر مورد نظر و قرار دادن آن در گروه های مختلف مانند مدیر یا *Administrator* بر روی آن راست کلیک کنید و گزینه *Properties* را انتخاب کنید.

در صفحه باز شده به سربرگ *Member Of* بروید و بر روی *Add* کلیک کنید.

اکنون صفحه زیر باز می شود که باید بر روی *Advanced* کلیک کنید.

![mhkarami97](/files/2018/03/itarfand-680-min.jpg)  

در این قسمت بر روی *Find Now* کلیک کنید و گروه مورد نظر خود را انتخاب کنید.

![mhkarami97](/files/2018/03/itarfand-681-min.jpg)  

اگر همه چیز درست پیش برود در صفحه زیر اروری مشاهده نمی کنید و کافی است بر روی *Ok* کلیک کنید.

![mhkarami97](/files/2018/03/itarfand-682-min.jpg)  

<span style="color: #0000ff;">**ساخت و پنهان سازی یوزر با CMD**</span>

ابتدا *cmd* را به صورت *Admin* باز کنید و جلمه زیر را وارد کنید تا کاربری با نام itarfand و رمز ۱۲۳ ساخته شود.

<span style="color: #008000;">net user itarfand 123 /add</span>

اکنون جلمه زیر را وارد کنید تا گروه کاربری آن مدیر بشود.

<span style="color: #008000;">net localgroup Administrators itarfand /add</span>

برای مخفی سازی یوزر در منوی استارت ، صفحه لاگین ویندوز جلمه زیر را وارد کنید.

<span style="color: #008000;">reg add “HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\Windows NT\\CurrentVersion\\Winlogon\\SpecialAccounts\\Userlist” /v itarfand /t REG\_DWORD /d 0 /f</span>

نکته : یورز ساخته شده در صفحه *Local users and Group* نمایش داده می شود.