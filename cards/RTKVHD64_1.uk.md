# `RTKVHD64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2FCBC36EECC32DFB2ABE8BD23B126E976EB0CDE0B4D501B951203B5FB0A93432` | `FB9790EA9585340B2890A50F6089BFE7A73673C5` | `296938762918E026819479AFC22D57F3` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_1.sys`
- **Розмір:** 6724048 bytes
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
