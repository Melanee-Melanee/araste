[English Version](./README_EN.md)

<div align="center">
  <h1> آراسته </h1>
  <h2> تبدیل نوشته‌های فارسی به هنر اسکی </h2>

![image](https://user-images.githubusercontent.com/85228025/178108748-21a4bae4-8e2e-46e1-966d-b98cbd56187f.png)

</div>


مشابه ابزار figlet ولی برای نوشته‌های فارسی و عربی


در حال حاضر می‌توانید با دستور زیر، با استفاده از قلمی که تنظیم شده است یک واژه، جمله یا چند سطر نوشته را بنویسید.  

```bash
araste ‌نوشته
```
یا اگر قلمی مدنظر دارید :
```bash
araste 'نوشته‌ی شما' -f 'اسم یا مسیر قلم'
```

برای دیدن فهرستی از قلم‌های نصب‌شده:

```bash
araste --list
```

درحال‌حاضر چند قلم برای این طراحی شده است که می‌توانید با اسم‌های زیر از آن‌ها استفاده کنید:
```
aipara
aipara_mini
zivar
nima
```

برای چاپ خروجی رنگی از سوییچ `--rainbow` استفاده کنید.

برای تعیین جهت چینش متن از سوییچ `-a` استفاده کنید.

برای راهنما :
```bash
araste -h
```

هم‌چنین می‌توانید ورودی را از طریق stdin به برنامه بدهید. برای مثال:

```bash
echo 'آراسته' | araste
```

یک نمونه از خروجی برنامه با قلم پیش‌فرض آیپارا :
```
                                      ██████
        ████                ██        ██
  ████                      ██          ██
  ████    ██    ██  ██  ██  ██    ██    ██
    ██████████████████████  ██    ██    ██
                                  ██
                                ██
```
## نصب و استفاده

آراسته در [PyPI](https://pypi.org/project/araste/) قرار دارد. برای نصب برنامه از مدیربستهٔ پایتون استفاده کنید.

````bash
pip install araste
````

یا اگر می‌خواهید خودتان آراسته را بیلد کنید:

```bash
pip install setuptools wheel
git clone 'https://github.com/ekm507/araste/'
cd araste
python3 setup.py bdist_wheel
pip install ./dist/araste-1.2.1-py3-none-any.whl
```

## نصب قلم‌های بیشتر
برای نصب فونت‌ها می‌توانید از araste-get استفاده کنید.
````bash
araste-get install FontName
````
[قلم های قابل نصب](https://github.com/ekm507/araste-fonts/blob/main/Fonts.md)

## حذف برنامه
برای پاک کردن برنامه از روی سیستم، می‌توانید از pip استفاده کنید.

````bash
pip uninstall araste
````

## ساخت قلم

برای دریافت قلم‌های بیشتر و هم‌چنین ساخت قلم خودتان از مخزن [araste-fonts](https://github.com/ekm507/araste-fonts) استفاده کنید.  
در آن مخزن قلم‌های ساخته‌شده و افزوده‌شده توسط کاربران، راهنماهایی برای ساخت طراحی و ساخت قلم و هم‌چنین ابزارهای مختلفی برای این منظور وجود دارد.

## برای انجام
برای انجام کار جدید فایل [TODOS.md](https://github.com/ekm507/araste/blob/main/TODOS.md) را مشاهده کنید
