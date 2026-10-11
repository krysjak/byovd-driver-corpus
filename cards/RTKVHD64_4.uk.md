# `RTKVHD64_4.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `378A0866A1F4A5BDF20EB1A27288C28613AF8181B61378E7E54A1DB9C7F72DB5` | `B372472A99CB9043B52D4970FCB4A4B5614348C2` | `C264BA90BE1948C2DECE854A26EE95C5` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_4.sys`
- **Розмір:** 7068968 bytes
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
