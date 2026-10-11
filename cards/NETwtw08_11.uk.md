# `NETwtw08_11.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_11.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FE28814A0D1C8DF27F04613075837E53B40201DB3EF05443390B69858BBA5A10` | `D7493E675D2E376D79BEC938A18EFFD104239B73` | `9EDB1BB4B877F61230404FDFFF049C75` |

## Метадані

- **Ім'я файлу:** `NETwtw08_11.sys`
- **Розмір:** 9143800 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
