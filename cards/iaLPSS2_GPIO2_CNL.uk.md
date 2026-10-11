# `iaLPSS2_GPIO2_CNL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_GPIO2_CNL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `03B7F1F6BF593BB804A3604230002EBDB679C7A11BF2F7F34388D3F16CB2FF7E` | `53BA394294308F285E4C5D34DB34E297139BF283` | `75FB2412D54AB939A349917905BB2A2E` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_GPIO2_CNL.sys`
- **Розмір:** 128776 bytes
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
