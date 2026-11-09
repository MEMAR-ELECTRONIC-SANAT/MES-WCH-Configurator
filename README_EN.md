# MES-WCH-Configurator

<div align="right">

[🇮🇷 فارسی](./README.md)　|　[🇬🇧 English](./README_EN.md)

</div>

**WCH microcontroller peripheral configuration and C initialization code generation**

**WCH Configurator FA-EN v1.4** is a lightweight web-based tool for selecting WCH microcontroller families and models, configuring common peripherals, and generating initial C-language initialization code.

> Select a chip, configure its peripherals, and generate initialization code — all in one lightweight web tool.

## Version and application file

- **Version:** 1.4
- **Interface languages:** فارسی / English
- **Application file:** [wch-configurator FA-EN v1_4.html](./wch-configurator%20FA-EN%20v1_4.html)
- **View application on GitHub:** [WCH Configurator v1.4](https://github.com/MEMAR-ELECTRONIC-SANAT/MES-WCH-Configurator/blob/main/wch-configurator%20FA-EN%20v1_4.html)

## Features

- Supports the CH32V, CH32F, CH32X, CH32L, CH57x, CH58x, and CH59x microcontroller families
- Select a microcontroller model from the corresponding family
- Configure GPIO, SPI, I²C, UART, TIMER, ADC, and IRQ / EXTI
- Display a logical pin map and selected configurations
- Generate C initialization code based on the selected family
- Copy generated code to the clipboard or download it as a .c file
- Persian and English user interface
- Information about **MEMAR ELECTRONIC SANAT**

## How to use

1. Download the HTML application file from this repository.
2. Open **wch-configurator FA-EN v1_7.html** in an up-to-date browser such as Firefox, Chrome, or Edge.
3. Select the microcontroller family, then choose the exact chip model.
4. Configure the required peripheral using the GPIO, SPI, I²C, UART, TIMER, ADC, or IRQ tabs.
5. Click **Add to configuration** to add the setting to the configuration list.
6. Review the generated code in the right-hand panel.
7. Select **Copy** or **Download .c** to use the generated code in your project.
8. Integrate the file and code into your project in MounRiver Studio or another suitable development environment.

## Important technical notes

- The generated output is **initialization code**. It is not a substitute for checking the datasheet, Reference Manual, and official SDK/EVT examples.
- Before using the output in a real project, verify the peripheral, pin assignment, alternate-function mapping, clock configuration, interrupts, and package limitations against the datasheet for the **exact chip model**.
- The pin map in the application is intended as a logical guide.

> [!IMPORTANT]
> <div align="center">
>
> **🔒 PRIVACY AND VALIDATION NOTICE**
>
> **This application runs locally in your browser · No data from this page is transmitted elsewhere.**
>
> Always verify the generated output and settings against the WCH datasheet and official EVT examples for the exact device model.
>
> </div>

<table>
  <tr>
    <td bgcolor="#C62828" align="center">
      <h2><font color="#FFFFFF">⚠️ IMPORTANT WARNING</font></h2>
      <h3><font color="#FFFFFF">Not all pins are available in every package.</font></h3>
      <font color="#FFFFFF">Before designing a PCB or connecting hardware, check the pin count and available functions in the datasheet for the exact microcontroller package.</font>
    </td>
  </tr>
</table>

- Code is generated according to the selected family. CH32V/CH32F/CH32X/CH32L families use their corresponding library patterns, while BLE families CH57x/CH58x/CH59x use their respective SDK patterns.
- In some cases, especially with multiple peripherals or special configurations, the generated code may need to be completed or modified manually.
- After integration, compile the project and test it on the actual hardware. The generated output does not guarantee electrical correctness or compatibility with every model.

## Official WCH resources

- [WCH — Official website](https://www.wch-ic.com/)
- [WCH Open Source — GitHub](https://github.com/openwch)
- [MounRiver Studio](https://www.mounriver.com/)
- [WCH Downloads — Tools and SDKs](https://www.wch-ic.com/downloads)

## Repository

[MEMAR-ELECTRONIC-SANAT / MES-WCH-Configurator](https://github.com/MEMAR-ELECTRONIC-SANAT/MES-WCH-Configurator)

## Application screenshots and guide

The screenshots below show the application's home page, peripheral configuration, usage guide, and About section. Click an image to view it at full size.

### Application home page
[![WCH Configurator home page](./Images/Home%20Page%20EN.jpg)](./Images/Home%20Page%20EN.jpg)

Overview of the application and its main chip selection and configuration areas.

### Peripheral configuration
[![WCH Configurator peripheral settings](./Images/peripherals%20EN.jpg)](./Images/peripherals%20EN.jpg)

A view of the peripheral configuration section and its available settings.

### User guide
[![WCH Configurator help guide](./Images/Help%20EN.jpg)](./Images/Help%20EN.jpg)

Visual guide to help users understand how to use the tool.

### About the application
[![About WCH Configurator](./Images/About%20EN.jpg)](./Images/About%20EN.jpg)

Introduction to the application and MEMAR ELECTRONIC SANAT.

## Prepared by

**MEMAR ELECTRONIC SANAT (MES) | معمار الکترونیک صنعت**

Design and development of electronic circuits, PCBs, embedded systems, and microcontroller configuration tools.

- GitHub: [MEMAR-ELECTRONIC-SANAT](https://github.com/MEMAR-ELECTRONIC-SANAT)

---
