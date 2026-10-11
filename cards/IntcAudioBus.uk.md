# `IntcAudioBus.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `07AE13A88DB54A1F0BE267921F53A532753BA951F122A9540DDFF0E66C6C7E80` | `BC1759C3402D16EA7BA635E3146E27EFA94C5ED4` | `6AD4DBBD2F79CE34AB323E988C3C873B` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus.sys`
- **Розмір:** 314880 bytes
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
