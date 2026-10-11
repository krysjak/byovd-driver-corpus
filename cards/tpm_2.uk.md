# `tpm_2.sys`

[Назад до індексу](../README.uk.md) · [English version](tpm_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `35CA6FC27DBF6AD15ECCC66FE0D7E274E946FBC451E9417F6D7346B295CEBC65` | `BFC04E5E0D21AD7D31DED7E9BFF9DBBF69C5D911` | `27B5E4E372A7B68A1F47676351E7A34A` |

## Метадані

- **Ім'я файлу:** `tpm_2.sys` (Ідентичні копії: `tpm_3.sys`)
- **Розмір:** 374176 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** TPM Device Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 85

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
