# `ipt.sys`

[Назад до індексу](../README.uk.md) · [English version](ipt.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E14223E74D1BDA76DAE04ECEBA0EAA865C624581FBDDCA31395DF902A7837ED8` | `BA5711B674A456DB57A5681B81DAC2EE25DA4B6F` | `491C1C826221375281CC169922981B12` |

## Метадані

- **Ім'я файлу:** `ipt.sys`
- **Розмір:** 103936 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** IPT Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
