# `IntcAudioBus_8.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `948D308D91760A66B13FDF564FF04537B79F0A24E6C47CCBEF5163F2FC28ECFF` | `12C565F7EB72D7398A45358DE95D1F0A56624A90` | `221ABECBE3B4143921FF00C3768E585E` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_8.sys`
- **Розмір:** 331760 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel(R) Smart Sound Technology BUS
- **Опис:** Intel(R) Smart Sound Technology BUS
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
