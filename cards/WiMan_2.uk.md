# `WiMan_2.sys`

[Назад до індексу](../README.uk.md) · [English version](WiMan_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A885C2557F1243CA7AF6A40D391CD327BC38C1DE8F876ADF6AB57F8CD982FC77` | `78CC91CB5E865C6FF9C6667217B5D849CAED7FAA` | `88775A02898BE551A385496B877A79F7` |

## Метадані

- **Ім'я файлу:** `WiMan_2.sys`
- **Розмір:** 171936 bytes
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
