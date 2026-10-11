# `GSCAuxDriverx64_2.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D3145D102584447B0DADF74E4B7A9CEED248EC7EA06C0BCA5C8BBFAB0307FA44` | `1621FA52CAE6EAC01A466337DA39B626531C23CB` | `D8A4B918367064A2AE475D9E4CB22920` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_2.sys`
- **Розмір:** 102328 bytes
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
