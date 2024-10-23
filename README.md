# 🎨 تمپلیت های سابسکریپشن برای مرزنشین

## 🔍 آشنایی

در اینجا ما تمپلیت های سابسکریپشن مرزنشین را قرار می‌دهیم.
برای آشنایی با مرزنشین به سایت آن مراجعه کنید ([لینک](https://github.com/marzneshin/marzneshin)).
برای آموزش نصب قالب‌ها و یا کسب اطلاعات بیشتر به کانال من سر بزنید ([لینک](https://t.me/MattDevChannel)).

## 🚀 قابلیت‌ها
- نصب راحت
- آپدیت آسان
- امکان مشاهده حجم، مشاهده زمان باقیمانده، پشتیبانی و اضافه کردن برنامه‌ها

## 📋 پیش‌نیازها
- داشتن دسترسی به سرور
- نصب بودن نرم‌افزارهای مورد نیاز مانند SSH و ویرایشگر متن

## 🔧 نصب کردن
نصب کردن تمپلیت به طور کلی شامل کپی کردن یک فایل

```text
index.html
```

در مقصد

```bash
/var/lib/marzneshin/templates/subscription/
```
است. سپس باید مقادیر زیر را در فایل .env در پوشه /etc/opt/marzneshin قرار دهید:
```env
CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzneshin/templates/"
SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"
```
یا دستور زیر را در ترمینال اجرا کنید:

```sh
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzneshin/templates/"' | sudo tee -a /etc/opt/marzneshin/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /etc/opt/marzneshin/.env
```

در نهایت، برای اعمال تغییرات و ری‌استارت مرزنشین، دستور زیر را اجرا کنید:
```sh
marzneshin restart
```

## 🖼 قالب‌ها
### قالب 1
<img src="https://raw.githubusercontent.com/MatinDehghanian/marzneshin-sub/main/PreviewTemplate.png" alt="تصویر قالب 1" width="400"/>

| ویژگی 1 | ویژگی 2 | ویژگی 3 | ویژگی 4 | ویژگی 5 |
|----------|----------|----------|----------|----------|
| ❌    | ❌    | ✔️   | ✔️   | 🛠️    |

[مشاهده قالب 1](#) >>

### قالب 2
![template2-pic](https://github.com/user-attachments/assets/0a38ff19-6e46-41a6-8250-a8218d6479da)

| ویژگی 1 | ویژگی 2 | ویژگی 3 | ویژگی 4 | ویژگی 5 |
|----------|----------|----------|----------|----------|
| ❌    | ❌    | ✔️   | ✔️   | 🛠️    |

[مشاهده قالب 2](#) >>

### قالب 3
![template3-pic](https://github.com/user-attachments/assets/28323b58-9d1a-4bbf-9ed1-ad81c2d7a35f)

| ویژگی 1 | ویژگی 2 | ویژگی 3 | ویژگی 4 | ویژگی 5 |
|----------|----------|----------|----------|----------|
| ❌    | ❌    | ✔️   | ✔️   | 🛠️    |

[دانلود قالب 3](#) >>

### قالب 4
## Desktop
<img src="https://raw.githubusercontent.com/MatinDehghanian/MarzViteTemplate/assets/images/desktop.png" title="Marzneshin-Sub-Desktop"/>

## Responsive Mobile
<img src="https://raw.githubusercontent.com/MatinDehghanian/MarzViteTemplate/assets/images/web-Mobile.JPEG" title="Marzneshin-Sub-Mobile"/>
| ویژگی 1 | ویژگی 2 | ویژگی 3 | ویژگی 4 | ویژگی 5 |
|----------|----------|----------|----------|----------|
| ❌    | ❌    | ✔️   | ✔️   | 🛠️    |
[دانلود قالب 4](#) >>

### قالب 5
![template5-pic](https://github.com/user-attachments/assets/cf0bfc84-73e0-4266-9924-7bfc9328f19f)

| ویژگی 1 | ویژگی 2 | ویژگی 3 | ویژگی 4 | ویژگی 5 |
|----------|----------|----------|----------|----------|
| ❌    | ❌    | ✔️   | ✔️   | 🛠️    |

[دانلود قالب 5](#)

### قالب 6
![template6-pic](https://github.com/user-attachments/assets/00c207b8-1044-4142-aec6-9f62f1ed706a)

| ویژگی 1 | ویژگی 2 | ویژگی 3 | ویژگی 4 | ویژگی 5 |
|----------|----------|----------|----------|----------|
| ❌    | ❌    | ✔️   | ✔️   | 🛠️    |

[دانلود قالب 6](#)

## 📚 استفاده
برای استفاده از تمپلیت‌ها در پروژه خود، مراحل زیر را دنبال کنید:
1. فایل‌های لازم را به پروژه خود وارد کنید.
2. تمپلیت‌ها را بر اساس نیاز خود سفارشی کنید.
3. تمپلیت‌ها را در برنامه خود ادغام کنید.

## 💡 پشتیبانی
برای دریافت پشتیبانی به بخش مسائل (Issues) مراجعه کنید و یا سوالات خود را در بخش Discussions مطرح کنید.
