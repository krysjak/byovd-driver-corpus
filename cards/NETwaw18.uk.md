# `NETwaw18.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwaw18.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9ACA0B7EBCEF5A63828496A98D22522A2D25990D5C816863340708C271A9926F` | `42D412110C189DB357E6FA0A121D2C21BC20C14C` | `84EC8A74647F3F07D8F1CEABC25682C0` |

## Метадані

- **Ім'я файлу:** `NETwaw18.sys`
- **Розмір:** 5965216 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** R Intel Wireless WiFi Link Driver
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
