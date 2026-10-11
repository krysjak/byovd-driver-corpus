# `pci.sys`

[Назад до індексу](../README.uk.md) · [English version](pci.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BD79656414F1354A322601B0F9B374B322B717F33A593CFD8DE2D8E28B95E4AB` | `841DBD08D8C243C51FDC8D7A8185B9C8915B9CD5` | `6CFB6774ADC69FC283A4CBC0D82595EF` |

## Метадані

- **Ім'я файлу:** `pci.sys` (Ідентичні копії: `pci_1.sys`)
- **Розмір:** 603632 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** NT Plug and Play PCI Enumerator
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
