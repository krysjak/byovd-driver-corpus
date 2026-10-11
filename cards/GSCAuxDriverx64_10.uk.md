# `GSCAuxDriverx64_10.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5AEA23AA8C8E0B1E0D01FE6B24BB7D02540BC40812DB2EF3234DE81E275E8E54` | `FDB0A44E5F66B2C2504459587114C686B5EEE51C` | `1C91B5CDD66B4B37C47823C00E0038D3` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_10.sys`
- **Розмір:** 78912 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Опис:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
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
