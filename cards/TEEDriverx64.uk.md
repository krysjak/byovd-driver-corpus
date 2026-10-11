# `TEEDriverx64.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverx64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `10C193D1ED434A6DC2AD8C450012B9AF1C848A0A0B3B775F13495648FB77E009` | `092D2AF6AAFA27056AC5B6BD1D73511B3C6639D4` | `E0EF6C1399A9B1AAA0B28590411BED04` |

## Метадані

- **Ім'я файлу:** `TEEDriverx64.sys`
- **Розмір:** 99288 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
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
