# `iaLPSS2_GPIO2_TGL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_GPIO2_TGL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `817E3D0D0543BAE67AE0252C63BAE7C81DDFEC1D93A7664FB533B95BEF38C473` | `5EA5723D1F83BAC9443AD90CFB52F939DD1E778A` | `B6D36DEA4CB1B31635354B365EC5F9AC` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_GPIO2_TGL.sys`
- **Розмір:** 128664 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO GPIO Driver v2
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
