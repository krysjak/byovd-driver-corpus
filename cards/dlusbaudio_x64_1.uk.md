# `dlusbaudio_x64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](dlusbaudio_x64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EF0056FE15BF636823D1046C259666FC76F402BC13D320B7F16A223B83B6D484` | `3B7F1B974D8518327B09ED623949A234149299B6` | `4D1CE9644DF69BC8E8CD36C6D6EE4708` |

## Метадані

- **Ім'я файлу:** `dlusbaudio_x64_1.sys`
- **Розмір:** 238856 bytes
- **Архітектура:** 0x8664
- **Компанія:** DisplayLink Corp.
- **Продукт:** DisplayLink USB Audio 2.0 Class Driver
- **Опис:** DisplayLink USB Audio Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
