# `RTKVHD64_8.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F9140EF0CF1BF84830192C83A35F6005F3AAEFDEDA33885A3368AD94081C28A9` | `D7563167C0F8A6CDB8E8EA43ED20E404B9728E47` | `AE2B99CE402CAECA06CA5D8F89EFCCAB` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_8.sys`
- **Розмір:** 5874144 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek Semiconductor Corp.
- **Продукт:** Realtek(r) High Definition Audio Function Driver
- **Опис:** Realtek(r) High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 80

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
