# `amdk8_1.sys`

[Назад до індексу](../README.uk.md) · [English version](amdk8_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F12823B0908EC5657796C38C6D3769317B68BDCFFC5D4BC6B44A729CA33E98E1` | `E2E6F92A7481905AD22CF2B9FF09797D96BF0DC4` | `A97E4A26EC88E07B6DDC900223424C63` |

## Метадані

- **Ім'я файлу:** `amdk8_1.sys` (Ідентичні копії: `amdk8_3.sys`)
- **Розмір:** 263552 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Processor Device Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
