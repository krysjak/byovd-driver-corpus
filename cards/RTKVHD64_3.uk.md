# `RTKVHD64_3.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1C4012C602B4556B547377F7CFA22F6DE81C3F22A0C6FFDDC9AA32C3079C6A35` | `0FE52F383A52DCA2B0A5656005CB98FAFB949AF4` | `276AF4F276DCBD0F195D3A8BA22F6E05` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_3.sys`
- **Розмір:** 6115696 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek Semiconductor Corp.
- **Продукт:** Realtek(r) High Definition Audio Function Driver
- **Опис:** Realtek(r) High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
