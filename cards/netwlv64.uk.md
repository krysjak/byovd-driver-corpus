# `netwlv64.sys`

[Назад до індексу](../README.uk.md) · [English version](netwlv64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DB6AD436A4AF7D94F8BB3159EF0E0A34AD93F9419957FF8AFC9978FB664CD3FF` | `B0B8B196300965031234A42BFB052700CEB830F9` | `10C475C8374F5E4905979D6C5F504DE0` |

## Метадані

- **Ім'я файлу:** `netwlv64.sys`
- **Розмір:** 7530496 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
