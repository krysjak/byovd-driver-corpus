# `ISH.sys`

[Назад до індексу](../README.uk.md) · [English version](ISH.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2BA8B6FD6A3A6EE1B2A30E960CD5F92A8985172B63C0A38EA2EF2154C8FD5A6C` | `9D07CDF43F4EAD35385A22058313154CE17EAE4E` | `DA6DEE41B0DEEAF086E43D9D2B5DEDD2` |

## Метадані

- **Ім'я файлу:** `ISH.sys`
- **Розмір:** 167072 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel
- **Продукт:** ISS
- **Опис:** Intel(R) Integrated Sensor Solution
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
