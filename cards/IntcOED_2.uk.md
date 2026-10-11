# `IntcOED_2.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `82489010B984E79046BC4716DD23AC35D375AE27EA179175B00846411523A517` | `1DCD9BDD974C2B6DF2BBAF3A63AFA51D4A58FBD7` | `F4D6453A5C75535E06E40B866F20E2EA` |

## Метадані

- **Ім'я файлу:** `IntcOED_2.sys`
- **Розмір:** 835776 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel® Smart Sound Technology (Intel® SST) OED
- **Опис:** Intel® Smart Sound Technology (Intel® SST) OED
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
