# `pmem.sys`

[Назад до індексу](../README.uk.md) · [English version](pmem.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42DC33427358A149BC2CB6AFDAA03FB14D624BECF4B955AC5E27814FD4CD0F11` | `0858A1DDD0108977C522BBD584781FD131D3A357` | `952DA37086339D0E101C49EF4B545D1A` |

## Метадані

- **Ім'я файлу:** `pmem.sys` (Ідентичні копії: `pmem_1.sys`)
- **Розмір:** 185848 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Persistent memory driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
