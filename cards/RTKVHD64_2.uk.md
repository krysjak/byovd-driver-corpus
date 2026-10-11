# `RTKVHD64_2.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `10A65D6EC98FA2F10C4C8AFB6E45D1F59D5FE7790491E2C254B3B8C29FBB930C` | `9B8F1AF6703A904E1A1F44B897CDEB08CC852254` | `CE18D4E4D2030B625726E117262CA37A` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_2.sys`
- **Розмір:** 6333912 bytes
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
