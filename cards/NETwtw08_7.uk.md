# `NETwtw08_7.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0D6059544AA2E62450953BEA98522CCE784121803037F70DD6506522239FD707` | `8CA4EA238FB907E1A754033146A3F862CB5EDFF6` | `9F6888C119132513A0B667108743F684` |

## Метадані

- **Ім'я файлу:** `NETwtw08_7.sys`
- **Розмір:** 8831064 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
