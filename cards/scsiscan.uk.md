# `scsiscan.sys`

[Назад до індексу](../README.uk.md) · [English version](scsiscan.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `53EBEC1DED51573DE29E99B1B556AC759C7C2B24FE4D3D47857ADF8A723317AB` | `E43FFF9F210DD82981C2BF20D7B57D7E9AA9037B` | `5AF4C8A3F553ABA303EDA6EEC9C0BF99` |

## Метадані

- **Ім'я файлу:** `scsiscan.sys`
- **Розмір:** 57344 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** SCSI Scanner Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
