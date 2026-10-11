# `tcusb.sys`

[Назад до індексу](../README.uk.md) · [English version](tcusb.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6AF2AEB769BD5903DA8FB6E75598C8E22A3091F4B3B8981003EC247BF3B07652` | `87A826C53DC7ACD9DEE474FBE2790D8B7DFCD208` | `C0EB9CC6E12B29CDA16DB8A200BA4765` |

## Метадані

- **Ім'я файлу:** `tcusb.sys`
- **Розмір:** 51816 bytes
- **Архітектура:** 0x14c
- **Компанія:** AuthenTec, Inc.
- **Продукт:** TouchChip USB Kernel Driver
- **Опис:** TouchChip USB Kernel Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
