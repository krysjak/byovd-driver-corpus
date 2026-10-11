# `dlusbaudio_x64_3.sys`

[Назад до індексу](../README.uk.md) · [English version](dlusbaudio_x64_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `62713897D8495F648061CED38D89FC887284960E2877CAF69FE5DA336F84366E` | `AD76F565F8C555B46DF19EDC9FBA9FA22256C8DB` | `40DABA8F68FF6F174C797E4869E7923E` |

## Метадані

- **Ім'я файлу:** `dlusbaudio_x64_3.sys`
- **Розмір:** 229704 bytes
- **Архітектура:** 0x8664
- **Компанія:** DisplayLink Corp.
- **Продукт:** DisplayLink USB Audio 2.0 Class Driver
- **Опис:** DisplayLink USB Audio Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
