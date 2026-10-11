# `WiMan_5.sys`

[Назад до індексу](../README.uk.md) · [English version](WiMan_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C15B0FB815CACFD4617B2DE68D33739F48B58EFD95338C0C530639EAA1919844` | `55B168F67B932CE57AB64430E7FB737AB06E813E` | `A8B631D98C704599C5AA3E2E6F33F689` |

## Метадані

- **Ім'я файлу:** `WiMan_5.sys`
- **Розмір:** 170664 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless Manageability
- **Опис:** Intel® Wireless Manageability
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
