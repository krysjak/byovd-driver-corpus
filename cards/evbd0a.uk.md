# `evbd0a.sys`

[Назад до індексу](../README.uk.md) · [English version](evbd0a.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `53AF6CD54EAE4D4952BC1FA57225A6A376D27E61E7EEFD00ACAF6C1D9346BE0E` | `6F0FD28BB29F3519CC7EBDB10A4196ABCD935368` | `7F4B99B92E31D1B644503F85FEC13CB1` |

## Метадані

- **Ім'я файлу:** `evbd0a.sys` (Ідентичні копії: `evbd0a_1.sys`)
- **Розмір:** 3424160 bytes
- **Архітектура:** 0x8664
- **Компанія:** QLogic Corporation
- **Продукт:** QLogic 10 GigE
- **Опис:** QLogic 10 GigE VBD
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmMapIoSpaceEx`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
