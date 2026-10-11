# `urssynopsys.sys`

[Назад до індексу](../README.uk.md) · [English version](urssynopsys.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E41A3359DE99E673F16809BD00CC7697BB0E41C198A94DFB96D29B287B1F78E2` | `09A15FEC4341C7CBEAE190D326AF5E770A0CC297` | `505F4CA3A039CB41A02A28785D35ED06` |

## Метадані

- **Ім'я файлу:** `urssynopsys.sys`
- **Розмір:** 66992 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** USB Role-Switch Driver for Synopsys Core
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
