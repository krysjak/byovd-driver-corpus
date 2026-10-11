# `dlusbaudio_x64_2.sys`

[Назад до індексу](../README.uk.md) · [English version](dlusbaudio_x64_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B44CECF63298A7E124C5AAD7432F0731AE8818BD3CFBAF7BBA42793F75746FE6` | `7DD0733CCBC8901F9DD670A13F5A3E1C1C7A72EF` | `C0042D5EF14E2CB44D23B2C4E5D687A9` |

## Метадані

- **Ім'я файлу:** `dlusbaudio_x64_2.sys`
- **Розмір:** 229744 bytes
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
