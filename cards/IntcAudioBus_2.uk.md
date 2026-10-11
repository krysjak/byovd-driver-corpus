# `IntcAudioBus_2.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `32FF3F79A95935EFEEFF65076CCC3E39D0011DFD447CD84C807677E0CD202385` | `BD2BE7705DCD95631FA685546C940EA52CA1A25C` | `6838AD7A98E9721F98070E87171D578F` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_2.sys`
- **Розмір:** 261600 bytes
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
