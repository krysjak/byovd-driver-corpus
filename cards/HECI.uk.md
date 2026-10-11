# `HECI.sys`

[Назад до індексу](../README.uk.md) · [English version](HECI.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FECC0A73FCD9EAA124FA2EF3A2B73CD5069B22F80A5E275CF2FE943F38F7405E` | `BF1B57B438CD06C750C91E1AA72D20C8F481F1AA` | `6C87E806EDE05928EDA5E6BCB426BB7D` |

## Метадані

- **Ім'я файлу:** `HECI.sys`
- **Розмір:** 56280 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 80

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
