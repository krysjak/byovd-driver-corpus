# `NETwtw04_9.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw04_9.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B0AC63ACBC369D4CD6B6ED61BE1A0F29255CC10657F053F895D556205F1CD9B` | `FC148F0BED2427909F813D5995E00C6F54129482` | `72ABE4AC7F43A24351E076BDE5058C02` |

## Метадані

- **Ім'я файлу:** `NETwtw04_9.sys`
- **Розмір:** 8714872 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
