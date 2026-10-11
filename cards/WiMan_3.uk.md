# `WiMan_3.sys`

[Назад до індексу](../README.uk.md) · [English version](WiMan_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2C291AC5786A136AF0CBA172B29F8C72EFEBA9382717B9B710FD19B01E6CE6DB` | `291B2D86605D1B8213F518B013921ADED8DA30E6` | `9F1A79AFBD1F528C5DF1347449B3EDC3` |

## Метадані

- **Ім'я файлу:** `WiMan_3.sys`
- **Розмір:** 167992 bytes
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
