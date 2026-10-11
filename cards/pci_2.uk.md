# `pci_2.sys`

[Назад до індексу](../README.uk.md) · [English version](pci_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B0C7874EF57637465DE089E54D2A4C2C71671F7BF34F38223A3FB6E6D637AA0` | `4871EA1C90EA4DF7A934BE8FD39062566B32BF17` | `D3FA42F3468926F54F5CCD2E64AF3A0A` |

## Метадані

- **Ім'я файлу:** `pci_2.sys` (Ідентичні копії: `pci_3.sys`)
- **Розмір:** 611744 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** NT Plug and Play PCI Enumerator
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
