# `GSCAuxDriverx64_5.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A96431719F9961AA57550920A6F5AA045978BE530EA038C092EDE67A1690C7C4` | `FC6F4CA3416C4B9BC98A245F7904DB9BF8FE0DC9` | `22293D22B6A591684C139C6515775E2D` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_5.sys`
- **Розмір:** 109240 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Опис:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
