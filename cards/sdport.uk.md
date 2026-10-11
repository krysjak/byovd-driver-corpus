# `sdport.sys`

[Назад до індексу](../README.uk.md) · [English version](sdport.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B8E738D974FC5D618665CE8CA2B1BB3C0A1BED09855B8B9BE39754EBD9AD6FED` | `53D8576B5AAAA6BD8E89E08DB3F98A0AC656B2D0` | `4ACC1409B80C14911F44D7AA9EE94DE9` |

## Метадані

- **Ім'я файлу:** `sdport.sys`
- **Розмір:** 140600 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** SD Host Controller Port Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
