# `AMS-MailBoxDrv.sys`

[Назад до індексу](../README.uk.md) · [English version](AMS-MailBoxDrv.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C8D3EA847F70AC079D8911C72258E911F3F26D241700B52C0E47991F23388091` | `6EE6A9FAF038654776ED6F6EEF0633F7AD1E6797` | `7965363605BCB2BF08C681499A932FB7` |

## Метадані

- **Ім'я файлу:** `AMS-MailBoxDrv.sys`
- **Розмір:** 125168 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc
- **Продукт:** AMS-MailBoxDrv
- **Опис:** AMS-MailBoxDrv
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
