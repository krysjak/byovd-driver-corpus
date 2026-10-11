# `terapcoip_1.sys`

[Назад до індексу](../README.uk.md) · [English version](terapcoip_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `08F25DA5DB431ECF2F3D8CAD1C3914B97B7857ED33F759773507DC60509363EE` | `ED3AF3A2554288694C4D3E3B40FC19EB8088E414` | `2B5A30C621E87DD22CCFB623812348F7` |

## Метадані

- **Ім'я файлу:** `terapcoip_1.sys`
- **Розмір:** 113664 bytes
- **Архітектура:** 0x8664
- **Компанія:** Windows (R) Win 7 DDK provider
- **Продукт:** Windows (R) Win 7 DDK driver
- **Опис:** PCoIP(R) Device
- **Підпис:** unsigned
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 55

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
