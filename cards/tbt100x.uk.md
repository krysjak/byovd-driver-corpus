# `tbt100x.sys`

[Назад до індексу](../README.uk.md) · [English version](tbt100x.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1DC616577ADD7845A27FE63CD0398704B1EC00095ED06C8B35FB556BD1BE720E` | `98BBBF8E62F4E06B8EB297244F19027DFA402D30` | `561D9298C3BC0D6E191300F8DD4B8414` |

## Метадані

- **Ім'я файлу:** `tbt100x.sys`
- **Розмір:** 137680 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Thunderbolt(TM) Bus Driver
- **Опис:** Thunderbolt(TM) Bus Driver
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
