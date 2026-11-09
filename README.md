# MES-WCH-Configurator

<div align="right">

[🇮🇷 فارسی](./README.md)　|　[🇬🇧 English](./README_EN.md)

</div>

**پیکربندی پریفراال‌های میکروکنترلرهای WCH و تولید کد راه‌اندازی C**

ابزار **WCH Configurator FA-EN v1.4** برای انتخاب خانواده و مدل میکروکنترلرهای WCH، تنظیم پریفراال‌های رایج و تولید کد اولیه راه‌اندازی به زبان C طراحی شده است.

> انتخاب تراشه، پیکربندی периферال‌ها و دریافت کد راه‌اندازی — در یک ابزار سبک تحت وب.

## نسخه و فایل برنامه

- **نسخه:** 1.4
- **زبان رابط:** فارسی / English
- **فایل برنامه:** [wch-configurator FA-EN v1_4.html](./wch-configurator%20FA-EN%20v1_4.html)
- **مشاهده برنامه در GitHub:** [WCH Configurator v1.4](https://github.com/MEMAR-ELECTRONIC-SANAT/MES-WCH-Configurator/blob/main/wch-configurator%20FA-EN%20v1_4.html)

## قابلیت‌ها

- انتخاب خانواده‌های پشتیبانی‌شده: CH32V، CH32F، CH32X، CH32L، CH57x، CH58x و CH59x
- انتخاب مدل میکروکنترلر از فهرست هر خانواده
- تنظیم GPIO، SPI، I²C، UART، TIMER، ADC و IRQ / EXTI
- نمایش نقشه منطقی پایه‌ها و پیکربندی‌های انتخاب‌شده
- تولید کد راه‌اندازی C متناسب با خانواده انتخاب‌شده
- کپی کد تولیدشده در کلیپ‌بورد و دریافت فایل .c
- رابط دو‌زبانه فارسی و انگلیسی
- بخش معرفی مجموعه **معمار الکترونیک صنعت**

## روش استفاده

1. فایل HTML برنامه را از مخزن دریافت کنید.
2. فایل **wch-configurator FA-EN v1_4.html** را با مرورگر به‌روز مانند Firefox، Chrome یا Edge باز کنید.
3. خانواده میکروکنترلر و سپس مدل دقیق تراشه را انتخاب کنید.
4. از تب‌های GPIO، SPI، I²C، UART، TIMER، ADC یا IRQ، peripheral موردنظر را تنظیم کنید.
5. روی **Add to configuration** کلیک کنید تا تنظیم به فهرست پیکربندی اضافه شود.
6. کد تولیدشده را در پنل سمت راست بررسی کنید.
7. برای استفاده در پروژه، **Copy** یا **Download .c** را انتخاب کنید.
8. فایل و کد را با پروژه خود در MounRiver Studio یا محیط توسعه مناسب ادغام کنید.

## نکات مهم فنی

- کد تولیدشده، **کد اولیه راه‌اندازی** است و جایگزین بررسی دیتاشیت، Reference Manual و مثال‌های رسمی SDK/EVT نمی‌شود.
- پیش از استفاده واقعی، peripheral، پایه‌ها، قابلیت alternate function، کلاک، وقفه‌ها و محدودیت‌های پکیج را با دیتاشیت **مدل دقیق تراشه** تطبیق دهید.
- نقشه پایه‌ها در برنامه جنبه راهنمای منطقی دارد.

<table>
  <tr>
    <td bgcolor="#1565C0" align="center">
      <h2><font color="#FFFFFF">🔒 نکته مهم درباره حریم خصوصی و اعتبارسنجی</font></h2>
      <h3><font color="#FFFFFF">این برنامه به‌صورت محلی در مرورگر شما اجرا می‌شود · هیچ داده‌ای از این صفحه خارج نمی‌شود.</font></h3>
      <font color="#FFFFFF">همیشه خروجی و تنظیمات را با دیتاشیت WCH و نمونه‌های رسمی EVT مربوط به مدل دقیق قطعه تطبیق دهید.</font>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td bgcolor="#C62828" align="center">
      <h2><font color="#FFFFFF">⚠️ هشدار مهم</font></h2>
      <h3><font color="#FFFFFF">همه پایه‌ها در تمام پکیج‌ها در دسترس نیستند.</font></h3>
      <font color="#FFFFFF">پیش از طراحی PCB یا اتصال سخت‌افزار، تعداد پایه‌ها و قابلیت‌های قابل‌استفاده را در دیتاشیت پکیج دقیق میکروکنترلر بررسی کنید.</font>
    </td>
  </tr>
</table>
<div dir="rtl" align="right">

- سبک کد بر اساس خانواده انتخاب‌شده تولید می‌شود. خانواده‌های CH32V/CH32F/CH32X/CH32L از الگوی کتابخانه‌های متناسب خود و خانواده‌های BLE سری CH57x/CH58x/CH59x از الگوی SDK مربوط استفاده می‌کنند.
- در برخی موارد، به‌ویژه peripheralهای چندگانه یا پیکربندی‌های خاص، لازم است کد تولیدشده را دستی تکمیل یا اصلاح کنید.
- پس از ادغام، پروژه را کامپایل و روی سخت‌افزار واقعی آزمایش کنید؛ خروجی برنامه تضمین‌کننده صحت الکتریکی یا سازگاری قطعی با تمام مدل‌ها نیست.

</div>

## منابع رسمی WCH

- [WCH — وب‌سایت رسمی](https://www.wch-ic.com/)
- [WCH Open Source — GitHub](https://github.com/openwch)
- [MounRiver Studio](https://www.mounriver.com/)
- [WCH Downloads / ابزارها و SDK](https://www.wch-ic.com/downloads)

## مخزن

[MEMAR-ELECTRONIC-SANAT / MES-WCH-Configurator](https://github.com/MEMAR-ELECTRONIC-SANAT/MES-WCH-Configurator)

## تصاویر و راهنمای برنامه

تصاویر زیر نمایی از صفحه اصلی، تنظیم peripheralها، راهنمای استفاده و بخش معرفی برنامه را نشان می‌دهند. برای مشاهده تصویر در اندازه کامل، روی آن کلیک کنید.

### صفحه اصلی برنامه
[![صفحه اصلی WCH Configurator](./Images/Home%20Page%20FA.jpg)](./Images/Home%20Page%20FA.jpg)

نمای کلی برنامه و بخش‌های اصلی انتخاب تراشه و پیکربندی.

### تنظیم peripheralها
[![تنظیم peripheralها در WCH Configurator](./Images/peripherals%20FA.jpg)](./Images/peripherals%20FA.jpg)

نمایی از بخش تنظیم peripheralها و گزینه‌های پیکربندی در برنامه.

### راهنمای استفاده
[![راهنمای WCH Configurator](./Images/Help%20FA.jpg)](./Images/Help%20FA.jpg)

راهنمای تصویری برای آشنایی با نحوه استفاده از ابزار.

### درباره برنامه
[![درباره WCH Configurator](./Images/About%20FA.jpg)](./Images/About%20FA.jpg)

معرفی برنامه و مجموعه معمار الکترونیک صنعت.

## تهیه و تدوین

**معمار الکترونیک صنعت**  
**MEMAR ELECTRONIC SANAT (MES)**

همراه شما در مسیر طراحی و ساخت مدارهای مطمئن

طراحی و توسعه مدارهای الکترونیکی، PCB، سیستم‌های embedded و ابزارهای پیکربندی میکروکنترلر.

- کانال تلگرام: [https://t.me/Memar_Electronic](https://t.me/Memar_Electronic)
- پیج اینستاگرام: [https://www.instagram.com/Memar.Electronic](https://www.instagram.com/Memar.Electronic)
- GitHub: [MEMAR-ELECTRONIC-SANAT](https://github.com/MEMAR-ELECTRONIC-SANAT)

---
