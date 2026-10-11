# `tcusb_1.sys`

[Назад до індексу](../README.uk.md) · [English version](tcusb_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5F645C229C4F7E177AE8B1126FEDE1D9BF3F436F9EAEDDC3804A41D9AF6A5BB4` | `976EF125DA4EE8C5A3D212AC47772EE8660AE3D4` | `9BAAD1DB231539E7F786A074BC0B5264` |

## Метадані

- **Ім'я файлу:** `tcusb_1.sys`
- **Розмір:** 63848 bytes
- **Архітектура:** 0x8664
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
