<!-- Rendered at https://github.com/dsdtech-official
     ORGANIZATION rule: the repository must be named literally `.github`,
     and the file must be at `profile/README.md`.
     (Personal accounts use a different, mutually exclusive rule:
      repo name == username, README.md at the repo root.) -->

# DSD TECH

Hardware from Dongguan, China. Since 2010 we have built USB-to-serial and USB-to-CAN
adapters, USB isolators, RS485 / RS422 / RS232 converters, protocol analysers, and
Bluetooth, WiFi and LoRa modules.

This account is where we publish the open-source part of that work.

## Software

### [diSerial](https://github.com/dsdtech-official/diSerial)

A free and open-source serial port tool, in two kinds of session: a **terminal** for
talking to one device, and **dual-port passive monitoring** — both directions of a
conversation between two devices, merged onto one timeline, so you read a request and its
reply in order instead of guessing.

Written as the companion software for our diDatatracker protocol analyser, and tied to
nothing: the terminal works with any serial port, monitoring with any two.

**.NET and Avalonia** · **Apache-2.0**

**Windows**, from the [**Microsoft Store**](https://apps.microsoft.com/detail/9pljclpgnzcw) · **macOS** 12 or later on Apple Silicon, from the [**Mac App Store**](https://apps.apple.com/app/id6802570917)

Installing from either store skips the SmartScreen and "unidentified developer" prompts a
downloaded zip has to get past. Zips for all four architectures, and the exact OS versions
each build needs, are on the
[diSerial page](https://github.com/dsdtech-official/diSerial).

The interface is available in nine languages — English · 简体中文 · 日本語 · Français ·
Deutsch · Español · Italiano · Português · 繁體中文 — and the first launch follows the
operating system's language. Two regional notes: Portuguese is European rather than
Brazilian, and Traditional Chinese uses Taiwanese terminology.

---

## Hardware

### [can-adapters](https://github.com/dsdtech-official/can-adapters)

Everything that ships with our USB-to-CAN adapters, one folder per model: the manual, the
schematic and board files, the firmware and how to flash it, and example code you can run.

| Model | Bus | |
|---|---|---|
| [**SH-C30A**](https://github.com/dsdtech-official/can-adapters/tree/main/SH-C30A) | CAN 2.0A / 2.0B | STM32F072, non-isolated. USB-A plug on the board |
| [**SH-C30G**](https://github.com/dsdtech-official/can-adapters/tree/main/SH-C30G) | CAN 2.0A / 2.0B | STM32F072, **galvanically isolated** — signal and power both |
| [**SH-C30L**](https://github.com/dsdtech-official/can-adapters/tree/main/SH-C30L) | CAN 2.0A / 2.0B | STM32F072, non-isolated. USB-A plug on a lead, 19 mm shorter board |
| [**SH-C31A**](https://github.com/dsdtech-official/can-adapters/tree/main/SH-C31A) | **CAN FD** | STM32G431, non-isolated. CAN FD works on the firmware it ships with, measured to 5 Mbit/s |
| [**SH-C31G**](https://github.com/dsdtech-official/can-adapters/tree/main/SH-C31G) | **CAN FD** | STM32G431, **galvanically isolated** — signal and power both |

Design files are published in the format the boards are actually edited in, with a
schematic PDF alongside for reading without an EDA tool.
**CERN-OHL-S-2.0** for the hardware · **CC-BY-SA-4.0** for the documentation ·
**BSD-3-Clause** for the examples · **MIT** for the firmware images.

**Firmware downloads** are on each model's firmware page. **Two builds cover all five
models** — one for the SH-C30x boards
([download](https://github.com/dsdtech-official/can-adapters/blob/main/SH-C30A/firmware/README.md#download)), one for the SH-C31x boards
([download](https://github.com/dsdtech-official/can-adapters/blob/main/SH-C31A/firmware/README.md#download)).

---

More repositories will appear here as they are prepared.

## Buy

<https://www.deshide.com> · Amazon in the US, UK, Europe, Japan, Australia and the Middle East

## Contact

Issues and pull requests are welcome on any repository.
For sales, warranty and returns: <https://www.deshide.com>
