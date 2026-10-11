# `RTKVHD64.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `60BBF11CD01CBF36450F3EACFF1DCE33368F572FB42FBD1F7002E63C73A18EA7` | `EB9D8C2D2CF7C4424B1865A4D972608EAA68A07A` | `8A6D1C881AAA19A7ECBAD1BD88ADAFE5` |

## Метадані

- **Ім'я файлу:** `RTKVHD64.sys`
- **Розмір:** 6666192 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek Semiconductor Corp.
- **Продукт:** Realtek(r) High Definition Audio Function Driver
- **Опис:** Realtek(r) High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 110

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
