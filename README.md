# MES-WCH-Configurator

<p align="center">
  <img src="Images/GitHub-Assets/MES-Hero-Banner.svg" width="100%" alt="MEMAR ELECTRONIC SANAT — MES">
</p>

<p align="center">
  <a href="#نسخه-فارسی">🇮🇷 فارسی</a>　|　<a href="#english-version">🇬🇧 English</a>
</p>

**پیکربندی پریفراال‌های میکروکنترلرهای WCH و تولید کد راه‌اندازی C**

ابزار **WCH Configurator FA-EN v1.6** برای انتخاب خانواده و مدل میکروکنترلرهای WCH، تنظیم پریفراال‌های رایج و تولید کد اولیه راه‌اندازی به زبان C طراحی شده است.

> انتخاب تراشه، پیکربندی периферال‌ها و دریافت کد راه‌اندازی — در یک ابزار سبک تحت وب.

## اجرای آنلاین برنامه

<p align="center">
  <a href="https://memar-electronic-sanat.github.io/MES-WCH-Configurator/">
    <img src="https://img.shields.io/badge/اجرای_آنلاین-WCH%20Configurator-155EEF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="اجرای آنلاین WCH Configurator">
  </a>
</p>

**[▶ ورود به WCH Configurator v1.6](https://memar-electronic-sanat.github.io/MES-WCH-Configurator/)**

با کلیک روی لینک بالا، نسخه تحت وب برنامه مستقیماً در مرورگر باز می‌شود و نیازی به دانلود یا نصب ندارد.

## نسخه و فایل برنامه

- **نسخه:** 1.6
- **زبان رابط:** فارسی / English
- **اجرای آنلاین برنامه:** [WCH Configurator v1.6](https://memar-electronic-sanat.github.io/MES-WCH-Configurator/)
- **دریافت فایل HTML برنامه:** [WCH-Configurator-FA-EN-v1_6.html](./WCH-Configurator-FA-EN-v1_6.html)
- **مشاهده سورس HTML در GitHub:** [Source Code](https://github.com/MEMAR-ELECTRONIC-SANAT/MES-WCH-Configurator/blob/main/WCH-Configurator-FA-EN-v1_6.html)

<p align="center">
  <img src="Images/GitHub-Assets/MES-Section-Header.svg" width="100%" alt="WCH Configurator Features">
</p>

## قابلیت‌ها

- انتخاب خانواده‌های پشتیبانی‌شده: CH32V، CH32F، CH32X، CH32L، CH57x، CH58x و CH59x
- انتخاب مدل میکروکنترلر از فهرست هر خانواده
- تنظیم GPIO، SPI، I²C، UART، TIMER، ADC و IRQ / EXTI
- نمایش نقشه منطقی پایه‌ها و پیکربندی‌های انتخاب‌شده
- تولید کد راه‌اندازی C متناسب با خانواده انتخاب‌شده
- کپی کد تولیدشده در کلیپ‌بورد و دریافت فایل .c
- رابط دو‌زبانه فارسی و انگلیسی
- بخش معرفی مجموعه **معمار الکترونیک صنعت**

<p align="center">
  <img src="Images/GitHub-Assets/MES-Project-Card.svg" width="100%" alt="WCH Configurator — MCU Setup and C Code Generation">
</p>

## روش استفاده

1. روی دکمه **اجرای آنلاین** در بالای این صفحه کلیک کنید.
2. خانواده میکروکنترلر و سپس مدل دقیق تراشه را انتخاب کنید.
3. peripheral موردنظر را از بخش‌های GPIO، SPI، I²C، UART، TIMER، ADC یا IRQ پیکربندی کنید.
4. روی **Add to configuration** کلیک کنید تا تنظیم به فهرست پیکربندی اضافه شود.
5. نقشه پایه‌ها و کد تولیدشده را بررسی کنید.
6. با گزینه **Copy** کد را کپی یا با گزینه **Download .c** آن را دریافت کنید.
7. کد را در پروژه خود در MounRiver Studio یا محیط توسعه مناسب ادغام کنید.

## نکات مهم فنی

- کد تولیدشده، **کد اولیه راه‌اندازی** است و جایگزین بررسی دیتاشیت، Reference Manual و مثال‌های رسمی SDK/EVT نمی‌شود.
- پیش از استفاده واقعی، peripheral، پایه‌ها، قابلیت alternate function، کلاک، وقفه‌ها و محدودیت‌های پکیج را با دیتاشیت **مدل دقیق تراشه** تطبیق دهید.
- نقشه پایه‌ها در برنامه جنبه راهنمای منطقی دارد.

<p align="center">
  <img src="./Images/privacy-notice-fa.svg?v=2" alt="نکته مهم درباره حریم خصوصی و اعتبارسنجی" width="100%">
</p>

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

<p align="center">
  <img src="Images/GitHub-Assets/MES-Divider.svg" width="100%" alt="MES Divider">
</p>

<p align="center">
  <img src="Images/GitHub-Assets/MES-Status-Strip.svg" width="100%" alt="MES Embedded Engineering Resources">
</p>

# English Version

## Overview

**WCH Configurator FA-EN v1.6** is a bilingual web-based utility for selecting WCH microcontrollers, configuring common peripherals, and generating initial C-language initialization code.

It is intended to simplify the initial MCU configuration workflow and provide a practical starting point for embedded firmware projects.

## Launch the Web Application

<p align="center">
  <a href="https://memar-electronic-sanat.github.io/MES-WCH-Configurator/">
    <img src="https://img.shields.io/badge/Launch%20Web%20App-WCH%20Configurator%20v1.6-155EEF?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white" alt="Launch WCH Configurator v1.6">
  </a>
</p>

<p align="center">
  <strong><a href="https://memar-electronic-sanat.github.io/MES-WCH-Configurator/">▶ Launch WCH Configurator v1.6</a></strong>
</p>

The GitHub Pages entry point, index.html, automatically redirects to the v1.6 application. No download or installation is required to use the online version.

## Version and Project Files

- **Application version:** 1.6
- **Interface languages:** Persian / English
- **Live application:** [GitHub Pages](https://memar-electronic-sanat.github.io/MES-WCH-Configurator/)
- **GitHub Pages entry point:** [index.html](./index.html)
- **Main application file:** [WCH-Configurator-FA-EN-v1_6.html](./WCH-Configurator-FA-EN-v1_6.html)
- **Repository:** [MES-WCH-Configurator](https://github.com/MEMAR-ELECTRONIC-SANAT/MES-WCH-Configurator)

## Features

- Supports the CH32V, CH32F, CH32X, CH32L, CH57x, CH58x, and CH59x MCU families
- Select an MCU model from the corresponding family
- Configure GPIO, SPI, I²C, UART, TIMER, ADC, and IRQ / EXTI
- Display a logical pin map and selected configurations
- Generate initial C initialization code according to the selected family
- Copy generated code to the clipboard
- Download generated source code as a C file
- Bilingual Persian and English user interface
- Built-in help and an About section for MEMAR ELECTRONIC SANAT

## How to Use

1. Click the **Launch Web App** button above.
2. Select the required microcontroller family.
3. Choose the exact MCU model.
4. Configure the required peripheral using the GPIO, SPI, I²C, UART, TIMER, ADC, or IRQ sections.
5. Click **Add to configuration** to add the selected setting.
6. Review the logical pin map and generated source code.
7. Use **Copy** to copy the code or **Download .c** to save it.
8. Integrate the generated code into your project using MounRiver Studio or another suitable development environment.

## Technical Notes and Limitations

- The generated output is initial setup code. It is not a replacement for the device datasheet, Reference Manual, or official SDK/EVT examples.
- Verify pin assignments, alternate functions, clock settings, interrupts, and peripheral availability against the datasheet for the **exact MCU model and package**.
- The pin map is a logical reference and does not necessarily represent the physical availability of every pin in every package.
- Code-generation patterns depend on the selected family. CH32V/CH32F/CH32X/CH32L families use their corresponding library patterns, while BLE families CH57x/CH58x/CH59x use their respective SDK patterns.
- Some configurations may require manual code completion or modification.
- Compile the integrated project and test it on the actual target hardware.

<p align="center">
  <img src="./Images/privacy-notice-en.svg" alt="Privacy and validation notice" width="100%">
</p>

<table>
  <tr>
    <td bgcolor="#C62828" align="center">
      <h2><font color="#FFFFFF">⚠️ IMPORTANT WARNING</font></h2>
      <h3><font color="#FFFFFF">Not all pins are available in every package.</font></h3>
      <font color="#FFFFFF">Before designing a PCB or connecting hardware, check the pin count and available functions in the datasheet for the exact microcontroller package.</font>
    </td>
  </tr>
</table>

## Official WCH Resources

- [WCH Official Website](https://www.wch-ic.com/)
- [WCH Open Source — GitHub](https://github.com/openwch)
- [MounRiver Studio](https://www.mounriver.com/)
- [WCH Downloads — Tools and SDKs](https://www.wch-ic.com/downloads)

---


# تصاویر و دیاگرام‌های راهنما | Application Screenshots and Guide

در این بخش، تصاویر برنامه بر اساس زبان رابط کاربری در دو مجموعه مستقل ارائه شده‌اند.

This section contains two separate screenshot galleries, organized by the application interface language.

## تصاویر نسخه فارسی (FA)

<p align="center">
  <img src="Images/GitHub-Assets/MES-Divider.svg" width="100%" alt="MES Divider — Persian Gallery">
</p>

### صفحه اصلی برنامه | Application Home Page

<p align="center">
  <a href="./Images/Home%20Page%20FA.jpg">
    <img src="./Images/Home%20Page%20FA.jpg" alt="صفحه اصلی WCH Configurator — نسخه فارسی" width="90%">
  </a>
</p>

### تنظیم peripheralها | Peripheral Configuration

<p align="center">
  <a href="./Images/peripherals%20FA.jpg">
    <img src="./Images/peripherals%20FA.jpg" alt="تنظیم peripheralها در WCH Configurator — نسخه فارسی" width="90%">
  </a>
</p>

### راهنمای استفاده | User Guide

<p align="center">
  <a href="./Images/Help%20FA.jpg">
    <img src="./Images/Help%20FA.jpg" alt="راهنمای استفاده از WCH Configurator — نسخه فارسی" width="90%">
  </a>
</p>

### درباره برنامه | About the Application

<p align="center">
  <a href="./Images/About%20FA.jpg">
    <img src="./Images/About%20FA.jpg" alt="درباره WCH Configurator — نسخه فارسی" width="90%">
  </a>
</p>

## English Version (EN)

<p align="center">
  <img src="Images/GitHub-Assets/MES-Divider.svg" width="100%" alt="MES Divider — English Gallery">
</p>

### Application Home Page

<p align="center">
  <a href="./Images/Home%20Page%20EN.jpg">
    <img src="./Images/Home%20Page%20EN.jpg" alt="WCH Configurator home page — English version" width="90%">
  </a>
</p>

### Peripheral Configuration

<p align="center">
  <a href="./Images/peripherals%20EN.jpg">
    <img src="./Images/peripherals%20EN.jpg" alt="WCH Configurator peripheral settings — English version" width="90%">
  </a>
</p>

### User Guide

<p align="center">
  <a href="./Images/Help%20EN.jpg">
    <img src="./Images/Help%20EN.jpg" alt="WCH Configurator user guide — English version" width="90%">
  </a>
</p>

### About the Application

<p align="center">
  <a href="./Images/About%20EN.jpg">
    <img src="./Images/About%20EN.jpg" alt="About WCH Configurator — English version" width="90%">
  </a>
</p>

### تصاویر هویت بصری MES | Shared MES Visual Assets

<p align="center">
  <img src="Images/GitHub-Assets/MES-Section-Header.svg" width="100%" alt="MES Project Section">
</p>

<p align="center">
  <img src="Images/GitHub-Assets/MES-Project-Card.svg" width="100%" alt="WCH Configurator — MCU Setup and C Code Generation">
</p>

<p align="center">
  <img src="Images/GitHub-Assets/MES-Status-Strip.svg" width="100%" alt="MES Embedded Engineering Resources">
</p>


## تهیه و تدوین

**معمار الکترونیک صنعت**
**MEMAR ELECTRONIC SANAT (MES)**

همراه شما در مسیر طراحی و ساخت مدارهای مطمئن

طراحی و توسعه مدارهای الکترونیکی، PCB، سیستم‌های embedded و ابزارهای پیکربندی میکروکنترلر.

- کانال تلگرام: [https://t.me/Memar_Electronic](https://t.me/Memar_Electronic)
- پیج اینستاگرام: [https://www.instagram.com/Memar.Electronic](https://www.instagram.com/Memar.Electronic)
- GitHub: [MEMAR-ELECTRONIC-SANAT](https://github.com/MEMAR-ELECTRONIC-SANAT)


---

<p align="center">
  <img src="Images/GitHub-Assets/MES-Thank-You-Footer.svg" width="100%" alt="Thank you for visiting MES">
</p>

<p align="center">
  <img src="Images/GitHub-Assets/MES_Animated_Logo_640x480.svg" width="360" alt="MES Animated Logo">
</p>
