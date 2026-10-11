# `RTKVHD64_9.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_9.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C9F2E2C45189FE1CDA70B5BC2E694C65893927CA5E57D392FDDC9B50CA7374F3` | `A1D39580CC355053E83B89FDB178978BE4610CFE` | `446D511357D64235FD633F62F72D91B5` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_9.sys`
- **Розмір:** 6510648 bytes
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
