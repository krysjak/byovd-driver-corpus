# `IntcAudioBus_11.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_11.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BA5D67C82CE1EF3B4ACF0A440C32C1645F00522B0F456BD77EDEADCF80D08A16` | `719A586B80F62587C1A2561A3C9AC981006C8E65` | `AD8F45812409D4B464736A78F62BABA3` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_11.sys`
- **Розмір:** 229464 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Опис:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
