# `MSIRCOMM.sys`

[Назад до індексу](../README.uk.md) · [English version](MSIRCOMM.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `92BE91A71A23803E3136B3F32C9BE885718FD4663F48A1D1C676450F6EDE6926` | `CE65404A8387C1BAD1C0B331DA05C94360C022C7` | `61DF366F2D37F300C5D92861B03612F8` |

## Метадані

- **Ім'я файлу:** `MSIRCOMM.sys`
- **Розмір:** 69632 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Infra-Red Communications Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
