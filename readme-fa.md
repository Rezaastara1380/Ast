<h1 align="center"> 🚀 Astro 🚀 </h1>
<h3 align="center"> 🎗️A bash script that helps bypass GFW 🎗️</h3>

<p align="center"> <img src="https://komarev.com/ghpvc/?username=soroushnk&label=Profile%20views&color=0e75b6&style=flat" alt="soroushnk" />
<img src="https://img.shields.io/github/license/soroushnk/Astro?style=flat-square" alt="https://github.com/Soroushnk/Astro/blob/main/LICENSE" /> </p>
<p align="center">
  <img src="./assets/smenu.png" width="350" />
</p>










 ### نوشته شده توسط سروش نکوزاده
 
 
### چرا این کد ؟
به راحتی هر چیزی که برای ساخت یک وی پی ان نیاز داشته باشی رو میتونی با چند تا کلیک انجام بدی. 


## ✏️ معرفی
سلام.اسم من رضا هست و دانشجوی کامپیوتر هستم. حتما تجربه داشتی که برای انجام کوچیک ترین کاری که توی سرور بخوای انجام بدی کلی باید کد کپی کنی کلی تغییر بدی اونم با putty  که عذابه 😒. پس به این فکر افتادم که که همه ی اون کارهارو بندازم گردن یه اسکریپت که خودکار اونهارو انجام بده.


## 🧐 قابلیتها
&rlm;- **آپدیت کردن سرور**

&rlm;- **گرفتن مجوز (سرتیفیکیت) ssl**

&rlm;- **انتخاب از بین معروف ترین پنل ها و نصب با یه کلیک**

&rlm;- **کانفیگ سرور برای سیسکو انی کانکت**

&rlm;- **کانفیگ سرور برای اوپن وی پی ان سرور**

&rlm;- **تونل زدن بین دوتا سرور (مثلا ایران و خارج)**

&rlm;- **تغییر پورت ssh**

&rlm;- **ساخت پروکسی تلگرام**

&rlm;- **بالا اوردن سایت wordpress برای گول زدن فایروال**

&rlm;- **منو اختصاصی برای تست سرعت سرور با speedtest**

&rlm;- **اسکن آی پی تمیز کلودفلر**

&rlm;- **اجرا کردن پروکسی معکوس(reverse proxy) با انجینکس**

&rlm;- **تنظیم فایروال خود سرور**

&rlm;- **کانفیگ  و ساخت وایرگارد سرور به همراه پنل**

&rlm;- **کانفیگ  و ساخت اوتلاین سرور**


&rlm;- **کانفیگ  و ساخت وایرگارد سرور به همراه پنل**


&rlm;- **گرفتن بکاپ از سرور**
&rlm;- **انتقال اطلاعات بین دو سرور**
&rlm;- **برای گیمر ها  IPsec VPN  کانفیگ**

&rlm;- **دیدن وضعیت سیستم**

&rlm;- **استفاده از warp برای دور زدن google recapcha و ...**
&rlm;- **و کلی کلی امکانات دیگه**




## موارد مورد نیاز
شما فقط یه سرور اوبونتو با هر سخت افزاری نیاز دارین. حداقل نسخه اوبونتو (20.04) -(روی نسخه های قبلی هم اجرا میشه )

روی  debian  تست نشده خودتون تست کنین.



## 🛠️ مرحال اجرا
میتونید به راحتی فقط با دستور زیر اسکریپت رو اجرا کنین : 
```bash
bash <(curl -Ls https://raw.githubusercontent.com/Rezaastara1380/Astro/main/Astro.sh)
```
یا اینکه :


شما اول کد رو روی سرور خودتون دانلود یا اجرا کنین که دوتا روش داره :

الف)
```bash
wget https://raw.githubusercontent.com/Rezaastara1380/Astro/main/Astro.sh

```

ب) این کد کل پروژه رو دانلود میکنه:
```bash
git clone https://github.com/Rezaastara1380/Astro.git
cd Astro
```
حالا باید با کد زیر فایل رو قابل اجرا کنین:

```bash
chmod +x Astro.sh
```
بعد با یکی از کد های زیر  توسط bash  کد رو اجرا کنین :

```bash 
./Astro.sh
```
یا 

```bash 
bash Astro.sh
```
اگه هر مشکلی توی اجرای اسکریپت داشتین کد زیر رو اجرا کنین :
```bash 
sed -i -e 's/\r$//' Astro.sh
./Astro.sh
```
🌟 خوب دیگه کار تمومه  !!

## 🙏 ممنونم 
<h3 align="right">زبان های استفاده شده :</h3>
<p align="right"> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> </p>

