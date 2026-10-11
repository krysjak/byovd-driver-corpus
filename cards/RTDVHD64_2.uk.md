# `RTDVHD64_2.sys`

[Назад до індексу](../README.uk.md) · [English version](RTDVHD64_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FE10CD553EEB5307B689446E3AD345CB2060503080D333CB52D03C36B251F156` | `AA09D0871D35EE99F0EC08F69F08D181FE9C3E4F` | `148EE86DC038237A8E30229D884A6676` |

## Метадані

- **Ім'я файлу:** `RTDVHD64_2.sys`
- **Розмір:** 2532056 bytes
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
