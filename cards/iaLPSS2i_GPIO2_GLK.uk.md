# `iaLPSS2i_GPIO2_GLK.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2i_GPIO2_GLK.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `71FDC25244298D62A335769D6ED43394C33FBD8DB05AA54CA924A2977F37858F` | `27406A360E030CB321D0F4F77A1C53D7BCC9B53E` | `8D3E3C431367E3BA632B4396CA662E1A` |

## Метадані

- **Ім'я файлу:** `iaLPSS2i_GPIO2_GLK.sys` (Ідентичні копії: `iaLPSS2i_GPIO2_GLK_1.sys`)
- **Розмір:** 96256 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO GPIO Driver v2
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
