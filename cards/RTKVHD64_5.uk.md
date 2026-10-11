# `RTKVHD64_5.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3CC4CF23396967E4DEABCB2B79FB37E92B8FA3AD1E327BAC6968454160DD8AE1` | `5351C26C22913DA622BBE6268D17FFA3194D7C8C` | `38DB7F4B7632B40B05DE515D80D522E2` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_5.sys`
- **Розмір:** 6426600 bytes
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
