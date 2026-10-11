# `WiMan_1.sys`

[Назад до індексу](../README.uk.md) · [English version](WiMan_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8381275F6E99739F29602AEDD2D5DA3B7F870398D62ABAF496EF0E25733F02EE` | `1EE10D47DAF1A16488503F2BEE4F6F35DC56ADF7` | `99E5B972F16C8E6CF00BADBBEF1DB729` |

## Метадані

- **Ім'я файлу:** `WiMan_1.sys`
- **Розмір:** 165224 bytes
- **Архітектура:** 0x8664
- **Компанія:** —
- **Продукт:** —
- **Опис:** —
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
