# `scmbus_1.sys`

[Назад до індексу](../README.uk.md) · [English version](scmbus_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B74B50A7B6FF78338E48BBC4D631DC095F3EDE6A1FD7B9AFEE26E78824AE5511` | `EF1ADD5CB0C74AE7ACE6A83DD5AECE3576F6727B` | `99E5816422FE467759A2DC6A8FD300AA` |

## Метадані

- **Ім'я файлу:** `scmbus_1.sys` (Ідентичні копії: `scmbus_3.sys`)
- **Розмір:** 263576 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Storage Class Memory Bus Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 90

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
