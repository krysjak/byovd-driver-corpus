# `pciidex.sys`

[Назад до індексу](../README.uk.md) · [English version](pciidex.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4556E5165781778FCE316704152CAFD406BA02C33C4909C51888FD6BA1C025E5` | `AC238976255CFE81613E9453AF63904111112421` | `3314DDCE20BCD33C0C3525024A3C8901` |

## Метадані

- **Ім'я файлу:** `pciidex.sys` (Ідентичні копії: `pciidex_1.sys`)
- **Розмір:** 91632 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** PCI IDE Bus Driver Extension
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
