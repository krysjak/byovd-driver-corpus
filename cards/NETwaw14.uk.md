# `NETwaw14.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwaw14.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `462BDA4751A0284F5FF7C9CCC6C4611A3849AA17BB2C76A196BA2630676EF61B` | `82448E275208637A85EBD65F9CD9AB76BED54E8D` | `0E7951F34C7F3818665175F2CFC31CDA` |

## Метадані

- **Ім'я файлу:** `NETwaw14.sys`
- **Розмір:** 5593504 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** R Intel Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
