# `IntcOED.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A6C48B72EEC7CC13853591093077A1CED4250547D07009F32AD441DEAF6DBDD1` | `37E96401278146D8A296EDB19039D74D7D46BBB3` | `6486FBD9937060A41E2DDE200EA56CA1` |

## Метадані

- **Ім'я файлу:** `IntcOED.sys`
- **Розмір:** 1317840 bytes
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
