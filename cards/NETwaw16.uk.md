# `NETwaw16.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwaw16.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `17F604117BB4EC35ABD203DD693AC67A26C2768D084ED96651E01D3BC79A543C` | `9FFE1F6C0E58B3C4405C98F1071FAA8CD04D2ECD` | `1AB3E25AB46B6768126E29AED39A33C3` |

## Метадані

- **Ім'я файлу:** `NETwaw16.sys`
- **Розмір:** 5920152 bytes
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
