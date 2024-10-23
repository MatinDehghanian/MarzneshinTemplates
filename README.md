# 🎨 تمپلیت های سابسکریپشن برای [مرزنشین](https://github.com/marzneshin/marzneshin)

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

# 🖼 قالب‌ها

## قالب 1

<img src="https://raw.githubusercontent.com/MatinDehghanian/marzneshin-sub/main/PreviewTemplate.png" alt="تصویر قالب 1" width="800"/>


| نمایش اطلاعات کاربر | نمایش مصرف کاربر و زمان اتمام | لیست اپلیکیشن ها | لیست کانفیگ ها | ریسپانسیو |
|----------|----------|----------|----------|----------|
| ✔️    | ✔️    | ✔️   | ✔️   | ⚠️    |

[مشاهده قالب 1 »](https://github.com/matinDehghanian/marzneshintemplate1)


## قالب 2
<img src="https://github.com/user-attachments/assets/0a38ff19-6e46-41a6-8250-a8218d6479da" alt="تصویر قالب 2" width="800"/>


| نمایش اطلاعات کاربر | نمایش مصرف کاربر و زمان اتمام | لیست اپلیکیشن ها | لیست کانفیگ ها | ریسپانسیو |
|----------|----------|----------|----------|----------|
| ✔️    | ✔️    | ⚠️   | ❌   | ⚠️    |

[مشاهده قالب 2 »](https://github.com/matinDehghanian/marzneshintemplate2)

## قالب 3

<img src="https://github.com/user-attachments/assets/28323b58-9d1a-4bbf-9ed1-ad81c2d7a35f" alt="تصویر قالب 3" width="800"/>


| نمایش اطلاعات کاربر | نمایش مصرف کاربر و زمان اتمام | لیست اپلیکیشن ها | لیست کانفیگ ها | ریسپانسیو |
|----------|----------|----------|----------|----------|
| ✔️    | ✔️    | ✔️   | ✔️   | ⚠️    |

[دانلود قالب 3 »](https://github.com/matinDehghanian/marzneshintemplate3) >>

## قالب 4
## Desktop

<img src="https://raw.githubusercontent.com/MatinDehghanian/MarzViteTemplate/assets/images/desktop.png" alt="تصویر دسکتاپ قالب 4" title="Marzneshin-Sub-Desktop" width="800"/>

## Responsive Mobile

<img src="https://raw.githubusercontent.com/MatinDehghanian/MarzViteTemplate/assets/images/web-Mobile.JPEG" alt="تصویر موبایل قالب 4" title="Marzneshin-Sub-Mobile" width="800"/>


| نمایش اطلاعات کاربر | نمایش مصرف کاربر و زمان اتمام | لیست اپلیکیشن ها | لیست کانفیگ ها | ریسپانسیو |
|----------|----------|----------|----------|----------|
| ✔️    | ✔️    | ✔️   | ✔️   | ✔️    |

[دانلود قالب 4 »](https://github.com/MatinDehghanian/MarzViteTemplate)

### قالب 5
<img src="https://github.com/user-attachments/assets/cf0bfc84-73e0-4266-9924-7bfc9328f19f" alt="تصویر قالب 5" title="Marzneshin-Sub-Mobile" width="800"/>

 نمایش اطلاعات کاربر | نمایش مصرف کاربر و زمان اتمام | لیست اپلیکیشن ها | لیست کانفیگ ها | ریسپانسیو |
|----------|----------|----------|----------|----------|
| ✔️    | ✔️    | ⚠️   | ✔️   | ✔️    |

[دانلود قالب 5 » ](https://github.com/matinDehghanian/marzneshintemplate5)

### قالب 6
<img src="https://github.com/user-attachments/assets/00c207b8-1044-4142-aec6-9f62f1ed706a" alt="تصویر قالب 6" title="Marzneshin-Sub-Mobile" width="800"/>

 نمایش اطلاعات کاربر | نمایش مصرف کاربر و زمان اتمام | لیست اپلیکیشن ها | لیست کانفیگ ها | ریسپانسیو |
|----------|----------|----------|----------|----------|
| ✔️    | ✔️    | ⚠️   | ❌   | ⚠️    |

[دانلود قالب 6 »](https://github.com/matinDehghanian/marzneshintemplate6)

## 📚 استفاده
برای استفاده از تمپلیت‌ها در پروژه خود، مراحل زیر را دنبال کنید:
1. فایل‌های لازم را به پروژه خود وارد کنید.
2. تمپلیت‌ها را بر اساس نیاز خود سفارشی کنید.
3. تمپلیت‌ها را در برنامه خود ادغام کنید.

## 💡 پشتیبانی
برای دریافت پشتیبانی به بخش مسائل (Issues) مراجعه کنید و یا سوالات خود را در بخش Discussions مطرح کنید.
