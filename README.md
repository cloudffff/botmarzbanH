آموزش نصب:

برای اجرا سورس ابتدا باید یک هاست  تهیه کنید ( ترجیحا هاست ربات تلگرام هلند )  بجز هاست ایران هر هاستی میشه ربات را اجرا کرد. پس از تهیه  هاست مراحل زیر را به ترتیب انجام دهید.


1- ابتدا به ربات پدر رفته botfather@ و برای خود یک ربات بسازید و توکن ربات را کپی کنید چون در سورس باید جایگزاری کنید.

2- بعد از ساخت ربات و دریافت توکن سورس را که از لینک زیر آخرین نسخه میتوانید دانلود کنید را در هاست اپلود کرده.( ترجیحا داخل پوشه آپلود کنید )

https://github.com/mahdigholipour3/bottelegrammarzban/releases

3- پرونده ای که داخل هاست آپلود کرده اید را از حالت فشرده خارج کنید.

4- پس از خارج کردن پرونده فایل config.php را باز کرده و موارد زیر را تغییر دهید.
$url_panel = آدرس پنل  مرزبان را وارد نمایید در صورتی که آدرس پنل همراه با پورت است با پورت وارد کنید در غیراینصورت بدون پورت وارد کنید  و آخر آدرس هم نباید / نباید داشته باشد
$username_panel = نام کاربری پنل مرزبان را باید وارد کنید
$password_panel = رمز عبور پنل مرزبان را وارد کنید 
$token  = توکنی که از ربات بات فادر تهیه کردید را وارد کنید
$time = این متغییر برای بخش اکانت تست است که  تاریخ پایان  یوزر تست را باید وارد کنید زمان بر اساس ساعت باید وارد شود 
$val = این متغییر برای بخش اکانت تست است که حجم یوزر تستی که ایجاد می شود را باید وارد کنید که واحد بر اساس مگابایت باید وارد شود
$adminidnumbeer  = آیدی عددی ادمین باید وارد شود  که از ربات زیر می توانید آیدی عددی خود را بگیرید 
@myidbot


5 - پس از ذخیره  فایل را ذخیره کنید.
6 - کارتان در هاست تمام شده است حالا باید وبهوک ربات را انجام بدهید تا ربات شما روشن شود برای وب هوک از دو طریق می توانید این کار را انجام دهید 
روش اول از طریق  سایت لینک تلگرام :
برای وبهوک از طریق  لینک تلگرام  از لینک زیر میتوانید انجام دهید و باید در قسمت هایی که فارسی نوشته شده مقدار  ها را وارد کنید 
https://api.telegram.org/botتوکن/setwebhook?url=https://site.com/مسیر پوشه / index.php
در صورتی که وبهوک موفقیت آمیز باشد خروجی زیر را نشان خواهد داد.

{“ok”:true,”result”:true,”description”:”Webhook was set”}

روش دوم از طریق ربات تلگرام : 
برای انجام وبهوک ربات تلگرام از طریق آیدی زیر میتوانید ربات را استارت کرده و ربات را وبهوک کنید 
https://t.me/SwhBot


نکته های استفاده از سورس:

برای وارد به پنل ادمین از دستور "panel " استفاده کنید 
در صورتی که می خواهید متن های ربات تغییر دهید می توانید از فایل index.php  استفاده نمایید.


و در آخر در صورت وجود مشکل ، درخواست ویژگی جدید یا راهنمایی میتوانید یک درخواست باز کنید یا با آیدی تلگرام @gholipour3  در ارتباط باشید. و لطفا به این پروژه ستاره دهید


آدرس کیف پول برای حمایت :
BTC : 16SnQEz2quyZRndH3iBieHSdznF1iPkkT5
USDT (TRC20) : TEj59UfVRpHVBuwf6oQaE3TwKSEfQCnZgV 

