# `GSCAuxDriverx64_4.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FC4C3AC66F00DE8A84CF7549A566102BA288493540D301DF5EF9123F7C22962A` | `378CDD5167E11C89942B95171DA772CB37B81D38` | `D0F566B3C96EAD4B576C01D6989A77D0` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_4.sys`
- **Розмір:** 79992 bytes
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
