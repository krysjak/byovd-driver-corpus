# `iaLPSS2_GPIO2_1.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_GPIO2_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4D834A49DCB4F87655E01F46A70FF1206AA67EFD06C23189968C5848727CD30A` | `9F14DB10205A2C2C2FD47DB218583D5258B84441` | `E64E3C5E00F3ACEF92986379167A85FB` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_GPIO2_1.sys`
- **Розмір:** 128608 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO GPIO Driver v2
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
