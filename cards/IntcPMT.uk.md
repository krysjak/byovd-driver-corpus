# `IntcPMT.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcPMT.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BE24EBAA8B21B783A1BC9113F314D685759814E4F4A115493729DC623775893A` | `0403E23BD76211C79E30F619E3584B011475BAD5` | `0A923B4CC4DE148ED686488D196096A1` |

## Метадані

- **Ім'я файлу:** `IntcPMT.sys`
- **Розмір:** 66496 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Platform Monitoring Technology Driver
- **Опис:** Intel(R) Platform Monitoring Technology Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
