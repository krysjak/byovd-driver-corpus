# `NETwaw14_2.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwaw14_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8D4C1A18F95725EB0388BB197D685A663886E59D0CCA3829D642C9E0C097B00D` | `AD591B71BDAAE2AB34BB5DCE2AFDA899A861CFAC` | `D87E5FF24AB53A5EE69EA17C8A4F80BB` |

## Метадані

- **Ім'я файлу:** `NETwaw14_2.sys`
- **Розмір:** 5414568 bytes
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
