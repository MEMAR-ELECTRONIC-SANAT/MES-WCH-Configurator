<p align="center">
  <img src="Images/GitHub-Assets/MES-Hero-Banner.svg" width="100%" alt="MEMAR ELECTRONIC SANAT — MES">
</p>

# MES-WCH-Configurator

<p align="center">
  <a href="#نسخه-فارسی">🇮🇷 فارسی</a>　|　
  <a href="#english-version">🇬🇧 English</a>
</p>

<p align="center">
  <strong>WCH Microcontroller Peripheral Configurator &amp; C Initialization Code Generator</strong>
</p>

<p align="center">
  <a href="https://memar-electronic-sanat.github.io/MES-WCH-Configurator/">
    <img src="https://img.shields.io/badge/Launch-WCH%20Configurator%20v1.6-155EEF?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white" alt="Launch WCH Configurator v1.6">
  </a>
</p>

---

# نسخه فارسی

## معرفی

**WCH Configurator FA-EN v1.6** ابزاری تحت وب و دوزبانه برای انتخاب میکروکنترلرهای شرکت WCH، پیکربندی peripheralهای متداول و تولید کد اولیه راه‌اندازی به زبان C است.

این ابزار فرایند پیکربندی اولیه MCU را ساده‌تر می‌کند و یک نقطه شروع برای توسعه Firmware پروژه‌های Embedded در اختیار کاربر قرار می‌دهد.

## اجرای آنلاین

<p align="center">
  <a href="https://memar-electronic-sanat.github.io/MES-WCH-Configurator/">
    <img src="https://img.shields.io/badge/اجرای_آنلاین-WCH%20Configurator%20v1.6-155EEF?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white" alt="اجرای آنلاین WCH Configurator نسخه 1.6">
  </a>
</p>

<p align="center">
  <strong><a href="https://memar-electronic-sanat.github.io/MES-WCH-Configurator/">▶ اجرای WCH Configurator v1.6</a></strong>
</p>

با بازکردن لینک بالا، فایل ورودی GitHub Pages یعنی index.html به‌صورت خودکار نسخه 1.6 برنامه را در مرورگر باز می‌کند. برای استفاده از نسخه آنلاین، دانلود یا نصب برنامه لازم نیست.

## نسخه و فایل‌های پروژه

- **نسخه برنامه:** 1.6
- **زبان رابط کاربری:** فارسی / English
- **اجرای آنلاین:** [GitHub Pages](https://memar-electronic-sanat.github.io/MES-WCH-Configurator/)
- **فایل ورودی سایت:** [index.html](./index.html)
- **فایل اصلی برنامه:** [WCH-Configurator-FA-EN-v1_6.html](./WCH-Configurator-FA-EN-v1_6.html)
- **مخزن پروژه:** [MES-WCH-Configurator](https://github.com/MEMAR-ELECTRONIC-SANAT/MES-WCH-Configurator)

## قابلیت‌ها

- انتخاب خانواده‌های میکروکنترلر WCH شامل CH32V، CH32F، CH32X، CH32L، CH57x، CH58x و CH59x
- انتخاب مدل میکروکنترلر از فهرست خانواده مربوطه
- پیکربندی GPIO، SPI، I²C، UART، TIMER، ADC و IRQ / EXTI
- نمایش نقشه منطقی پایه‌ها و تنظیمات انتخاب‌شده
- تولید کد اولیه راه‌اندازی C متناسب با خانواده انتخاب‌شده
- کپی کد تولیدشده در کلیپ‌بورد
- دریافت خروجی کد در قالب فایل C
- رابط کاربری دوزبانه فارسی و انگلیسی
- بخش راهنما و معرفی مجموعه معمار الکترونیک صنعت

## روش استفاده

1. روی دکمه **اجرای آنلاین** در بالای این صفحه کلیک کنید.
2. خانواده میکروکنترلر موردنظر را انتخاب کنید.
3. مدل دقیق تراشه را از فهرست انتخاب کنید.
4. peripheral موردنظر را از بخش‌های GPIO، SPI، I²C، UART، TIMER، ADC یا IRQ پیکربندی کنید.
5. با انتخاب **Add to configuration** تنظیم را به فهرست پیکربندی اضافه کنید.
6. نقشه پایه‌ها و کد تولیدشده را بررسی کنید.
7. با گزینه **Copy** کد را کپی یا با گزینه **Download .c** آن را دریافت کنید.
8. کد را در پروژه خود در MounRiver Studio یا محیط توسعه مناسب ادغام کنید.

## نکات فنی و محدودیت‌ها

- خروجی برنامه، کد اولیه راه‌اندازی است و جایگزین دیتاشیت، Reference Manual و مثال‌های رسمی SDK/EVT نیست.
- تخصیص پایه‌ها، Alternate Function، کلاک، وقفه‌ها و قابلیت‌های peripheral باید با دیتاشیت **مدل و پکیج دقیق** میکروکنترلر تطبیق داده شوند.
- نقشه پایه‌ها در برنامه یک راهنمای منطقی است و لزوماً نشان‌دهنده اتصال فیزیکی تمام پایه‌ها در همه پکیج‌ها نیست.
- الگوی تولید کد با توجه به خانواده انتخاب‌شده تغییر می‌کند. خانواده‌های CH32V/CH32F/CH32X/CH32L از الگوی کتابخانه‌های متناسب خود و خانواده‌های BLE سری CH57x/CH58x/CH59x از الگوی SDK مربوط استفاده می‌کنند.
- ممکن است برخی پیکربندی‌ها به تکمیل یا اصلاح دستی کد نیاز داشته باشند.
- پس از ادغام کد، پروژه را کامپایل کرده و روی سخت‌افزار واقعی آزمایش کنید.

<p align="center">
  <img src="./Images/privacy-notice-fa.svg" alt="نکته مهم درباره حریم خصوصی و اعتبارسنجی" width="100%">
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

## منابع رسمی WCH

- [وب‌سایت رسمی WCH](https://www.wch-ic.com/)
- [مخزن WCH Open Source در GitHub](https://github.com/openwch)
- [MounRiver Studio](https://www.mounriver.com/)
- [دریافت ابزارها و SDKهای WCH](https://www.wch-ic.com/downloads)

---

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

تصاویر زیر بخش‌های مختلف برنامه را نشان می‌دهند. برای مشاهده هر تصویر در اندازه کامل، روی آن کلیک کنید.

The screenshots below illustrate the main application areas. Click any image to view it at full size.

## صفحه اصلی برنامه | Application Home Page

<p align="center">
  <a href="./Images/Home%20Page%20FA.jpg">
    <img src="./Images/Home%20Page%20FA.jpg" alt="صفحه اصلی WCH Configurator" width="90%">
  </a>
</p>

<p align="center">
  <a href="./Images/Home%20Page%20EN.jpg">
    <img src="./Images/Home%20Page%20EN.jpg" alt="WCH Configurator home page" width="90%">
  </a>
</p>

## تنظیم peripheralها | Peripheral Configuration

<p align="center">
  <a href="./Images/peripherals%20FA.jpg">
    <img src="./Images/peripherals%20FA.jpg" alt="تنظیم peripheralها در WCH Configurator" width="90%">
  </a>
</p>

<p align="center">
  <a href="./Images/peripherals%20EN.jpg">
    <img src="./Images/peripherals%20EN.jpg" alt="WCH Configurator peripheral settings" width="90%">
  </a>
</p>

## راهنمای استفاده | User Guide

<p align="center">
  <a href="./Images/Help%20FA.jpg">
    <img src="./Images/Help%20FA.jpg" alt="راهنمای استفاده از WCH Configurator" width="90%">
  </a>
</p>

<p align="center">
  <a href="./Images/Help%20EN.jpg">
    <img src="./Images/Help%20EN.jpg" alt="WCH Configurator user guide" width="90%">
  </a>
</p>

## درباره برنامه | About the Application

<p align="center">
  <a href="./Images/About%20FA.jpg">
    <img src="./Images/About%20FA.jpg" alt="درباره WCH Configurator" width="90%">
  </a>
</p>

<p align="center">
  <a href="./Images/About%20EN.jpg">
    <img src="./Images/About%20EN.jpg" alt="About WCH Configurator" width="90%">
  </a>
</p>

<p align="center">
  <img src="Images/GitHub-Assets/MES-Section-Header.svg" width="100%" alt="MES Project Section">
</p>

<p align="center">
  <img src="Images/GitHub-Assets/MES-Project-Card.svg" width="100%" alt="WCH Configurator — MCU Setup and C Code Generation">
</p>

<p align="center">
  <img src="Images/GitHub-Assets/MES-Divider.svg" width="100%" alt="MES Divider">
</p>

<p align="center">
  <img src="Images/GitHub-Assets/MES-Status-Strip.svg" width="100%" alt="MES Embedded Engineering Resources">
</p>

## تهیه و تدوین

**معمار الکترونیک صنعت**

**MEMAR ELECTRONIC SANAT (MES)**

همراه شما در مسیر طراحی و ساخت مدارهای مطمئن

طراحی و توسعه مدارهای الکترونیکی، PCB، سیستم‌های Embedded و ابزارهای پیکربندی میکروکنترلر.

- کانال تلگرام: [https://t.me/Memar_Electronic](https://t.me/Memar_Electronic)
- پیج اینستاگرام: [https://www.instagram.com/Memar.Electronic](https://www.instagram.com/Memar.Electronic)
- GitHub: [MEMAR-ELECTRONIC-SANAT](https://github.com/MEMAR-ELECTRONIC-SANAT)

## Prepared and Maintained by

**MEMAR ELECTRONIC SANAT (MES) | معمار الکترونیک صنعت**

*Your partner in designing and building reliable circuits.*

Electronic circuit and PCB design, embedded systems, and microcontroller configuration tools.

- Telegram: [Memar Electronic](https://t.me/Memar_Electronic)
- Instagram: [Memar.Electronic](https://www.instagram.com/Memar.Electronic)
- GitHub: [MEMAR-ELECTRONIC-SANAT](https://github.com/MEMAR-ELECTRONIC-SANAT)

---

<p align="center">
  <img src="Images/GitHub-Assets/MES-Thank-You-Footer.svg" width="100%" alt="Thank you for visiting MES">
</p>

<p align="center">
  <img src="Images/GitHub-Assets/MES_Animated_Logo_640x480.svg" width="360" alt="MES Animated Logo">
</p>
