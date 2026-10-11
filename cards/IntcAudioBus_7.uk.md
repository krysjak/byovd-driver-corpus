# `IntcAudioBus_7.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BD21989B2F2111C0C302561ABE506A84D708B6D26220BDDD180B5D1A888B2895` | `AE0AB66704CC968AB5C504EE391B59E95ED08DE2` | `D02237B85401538965E26A5CB2FF9855` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_7.sys`
- **Розмір:** 341456 bytes
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
