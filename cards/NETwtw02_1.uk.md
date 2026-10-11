# `NETwtw02_1.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw02_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8D14E800C05992A7AE960F8A7C7986234A934D3F55D0F7DA45C66367B969D931` | `FFDB69508DFEFB77929E3DB8D886AB5E2942A165` | `A223E3862DDB449F61A25C222D292C23` |

## Метадані

- **Ім'я файлу:** `NETwtw02_1.sys`
- **Розмір:** 6723848 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
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
