# `NETwew00.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwew00.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `71D6AC59541091FA8D7B421E360075916CCFE20B6CF68D15E4D9224F05616D91` | `7CAAB6412FA512D1EBD19A84B5E3C493D6556200` | `F10285CEF995267A865988E1B44CF7EC` |

## Метадані

- **Ім'я файлу:** `NETwew00.sys`
- **Розмір:** 3341824 bytes
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
