# `NETwtw04_8.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw04_8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2676C4361E1CF01502F29842EF2761B36E92E9EDA93A0E369733DC21C7C3E1F8` | `B42DE6662B2BD8E772DD2599C609CC98C18DBE13` | `18E5C382E3EBB25C87452F5A2DFF2F62` |

## Метадані

- **Ім'я файлу:** `NETwtw04_8.sys`
- **Розмір:** 8673040 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
