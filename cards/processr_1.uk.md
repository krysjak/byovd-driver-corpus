# `processr_1.sys`

[Назад до індексу](../README.uk.md) · [English version](processr_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B8B536A31DDBB44EA66371703FCF4DBDA83A674996DADC58F6E122B43F385690` | `AC2EC652376D28DC9692FE4DC48D450BF6349804` | `791DA3C70652B296EBBD39234B0FF671` |

## Метадані

- **Ім'я файлу:** `processr_1.sys` (Ідентичні копії: `processr_3.sys`)
- **Розмір:** 271768 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Processor Device Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
