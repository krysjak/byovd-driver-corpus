# `atihdw86.sys`

[Назад до індексу](../README.uk.md) · [English version](atihdw86.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E3E0D1DD072637302731B8A60B38219C419D9BF8DF127D5B811750FBBC8FD3AB` | `6F3D4EC22CE632764BFDFADB3E159986023C9F02` | `FAFEB8F172171C471922C6D114CAA3A1` |

## Метадані

- **Ім'я файлу:** `atihdw86.sys`
- **Розмір:** 215040 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD HD Audio Driver
- **Опис:** AMD High Definition Audio Function Driver
- **Підпис:** unsigned
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 55

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
