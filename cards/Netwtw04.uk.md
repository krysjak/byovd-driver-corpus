# `Netwtw04.sys`

[Назад до індексу](../README.uk.md) · [English version](Netwtw04.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `317C8979221D4797D04FD160FC9BDD2783044DCE34D66D0DF0290A24A2ADAB89` | `4CAD743FE0F50A84BD3513F398EE6299B47D553E` | `E51C665DB70389EF5FE48F8D040894C0` |

## Метадані

- **Ім'я файлу:** `Netwtw04.sys`
- **Розмір:** 8695808 bytes
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
