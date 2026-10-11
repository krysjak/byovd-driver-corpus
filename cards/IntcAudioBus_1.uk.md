# `IntcAudioBus_1.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B30069E639B5ECA82076E94395DE19A49210D98DC996533555C8CBB607DB1DD6` | `0D756CB8EB9E6BDC1768EBD1ECC2BF972726A1EA` | `F7AE4C6DBF9D5228DA5614E221099B3B` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_1.sys`
- **Розмір:** 331352 bytes
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
