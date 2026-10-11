# `GSCAuxDriverx64_9.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_9.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9D7E2627BBE5F330E43D2C33EABA7347B368D85CD4AA63459086A8965FCAE018` | `12E867B316DF63B99D45D6AD0D5D0F7861F9003A` | `8829EE3E6C6A335C10C45D874D2FE809` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_9.sys`
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
