# `vpci_2.sys`

[Назад до індексу](../README.uk.md) · [English version](vpci_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F7D0D46266582D5C7ACEA29CC7D75D1C4A28A237DF3AD34E43BE9CD1EA78F1D1` | `297393A4002266146A055761ED2468E58CAECE7A` | `982441187C93E352D2EFF561BC9979DE` |

## Метадані

- **Ім'я файлу:** `vpci_2.sys` (Ідентичні копії: `vpci_3.sys`)
- **Розмір:** 161184 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Virtual PCI Bus
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
