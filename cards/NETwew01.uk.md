# `NETwew01.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwew01.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `801C2A1F12E6F0D646E92C98477FCDB84C6743803CD7365B774B0F88EB650584` | `D2A7B08D6A92C081B12924FA6B2B7D6EF6426C17` | `99C24A7DC1F3D4845553B4BD189274A0` |

## Метадані

- **Ім'я файлу:** `NETwew01.sys`
- **Розмір:** 3343872 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
