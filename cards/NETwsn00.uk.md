# `NETwsn00.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwsn00.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9AD4AADA40FA8F43955834C6326DDB887FCAE7615CC4937A80FD60A4E0E7A42A` | `52F7A76E1C41E7E5FCF3533668ADBD21CB7A46DD` | `47613E9D8330024D08BF4BC10A43BF07` |

## Метадані

- **Ім'я файлу:** `NETwsn00.sys`
- **Розмір:** 10382576 bytes
- **Архітектура:** 0x14c
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
