# `iai2c.sys`

[Назад до індексу](../README.uk.md) · [English version](iai2c.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9296A14590DFD94A3C728CAF3CA91BA211F27974F9CFF8417CDDC00D1453315C` | `458A43F7F0674B68504AF1D02EA33F2F6FD5A03F` | `48EDB9B5DAB7D294951A520330F13715` |

## Метадані

- **Ім'я файлу:** `iai2c.sys` (Ідентичні копії: `iai2c_1.sys`)
- **Розмір:** 91136 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel(R) Serial IO I2C Driver
- **Опис:** Intel(R) Serial IO I2C Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
