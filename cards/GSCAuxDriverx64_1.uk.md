# `GSCAuxDriverx64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F936A819638AF4EF4E01A0AAA56A7C3652E73C34CAB50489F793655ACE952281` | `0F279583AEC244461C00C36F03380971F2781768` | `5C6A2D2F6B1C7AEFDBEC7E6033BF019D` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_1.sys`
- **Розмір:** 76048 bytes
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
