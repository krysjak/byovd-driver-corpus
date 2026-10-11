# `nvpcf_1.sys`

[Назад до індексу](../README.uk.md) · [English version](nvpcf_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ED0F3F9C06A16444861A45BC0AC7F18BA40AA71DE47D8EEEB4A3EE03326FDA42` | `7D00FAE23FFA6830C0C57B59B21859D608EB0ADB` | `14844F94AE522872C0C6997A69217C5B` |

## Метадані

- **Ім'я файлу:** `nvpcf_1.sys`
- **Розмір:** 239136 bytes
- **Архітектура:** 0x8664
- **Компанія:** NVIDIA Corporation
- **Продукт:** NVPCF
- **Опис:** NVIDIA Platform Controllers and Framework
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 115

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
