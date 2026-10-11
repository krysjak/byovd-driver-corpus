# `ltmdm64.sys`

[Назад до індексу](../README.uk.md) · [English version](ltmdm64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `570195A36BB5162D59516708C92E8BF7A558A4B05ADCE30A624C805541962131` | `6AD83D856585C15A51C75DD2DE6E4B334F94316D` | `CC5CF4BDAA6671E4F72B1B37E0A2DB4A` |

## Метадані

- **Ім'я файлу:** `ltmdm64.sys`
- **Розмір:** 543744 bytes
- **Архітектура:** 0x8664
- **Компанія:** Agere Systems
- **Продукт:** Agere V.92 Data+Fax Modem Version 8.36
- **Опис:** Agere Windows Modem
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
