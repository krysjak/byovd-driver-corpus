# `mtkwecx.sys`

[Назад до індексу](../README.uk.md) · [English version](mtkwecx.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E77858FCCF5A9698F7A5012EC641490DF75E5D8F0CE4B35062D8289FC59711C8` | `5D690C930849FE9DF8A57D331EFE6978E32A6984` | `2F99E8A1A621C7E6ED1B34F9E79C1B97` |

## Метадані

- **Ім'я файлу:** `mtkwecx.sys`
- **Розмір:** 2524528 bytes
- **Архітектура:** 0x8664
- **Компанія:** MediaTek Inc.
- **Продукт:** MediaTek Wi-Fi Adapter
- **Опис:** MediaTek Wi-Fi Driver
- **Підпис:** signed
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
