# `libusb0.sys`

[Назад до індексу](../README.uk.md) · [English version](libusb0.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8058F2AFE6EF96A7D2DED432997FD8655970C9EA75A938EE4557D6A2CB4CC989` | `81D2B572EC0D24ABA11ED6BFA9174FFAD54140B7` | `16E18CED459B1824234890386EE66CD5` |

## Метадані

- **Ім'я файлу:** `libusb0.sys`
- **Розмір:** 52832 bytes
- **Архітектура:** 0x8664
- **Компанія:** http://libusb-win32.sourceforge.net
- **Продукт:** LibUSB-Win32 - Kernel Driver
- **Опис:** LibUSB-Win32 - Kernel Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
