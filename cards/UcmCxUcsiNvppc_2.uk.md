# `UcmCxUcsiNvppc_2.sys`

[Назад до індексу](../README.uk.md) · [English version](UcmCxUcsiNvppc_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A386606B41C72D67C3DD6CC4FAEA0973263E850309E07E734DC4EC0A5C3BFBA4` | `135FC888C96E884E3653208BFC67209DEF7F06FE` | `445666EF082CB5223A20DBEC486072FD` |

## Метадані

- **Ім'я файлу:** `UcmCxUcsiNvppc_2.sys`
- **Розмір:** 707816 bytes
- **Архітектура:** 0x8664
- **Компанія:** NVIDIA Corporation
- **Продукт:** NVPPC
- **Опис:** NVIDIA PPC Function Driver.
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
