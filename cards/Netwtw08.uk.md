# `Netwtw08.sys`

[Назад до індексу](../README.uk.md) · [English version](Netwtw08.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `18E1A3736F2D1ECCE196C008A474ABBB430B3F1310C731D5B58D9E9F13DE90B3` | `314EF12EDD6174D1D319DAB39AB7B6BBD88F008F` | `61A41DBA0D1D6159AB8BF7C0B952B064` |

## Метадані

- **Ім'я файлу:** `Netwtw08.sys`
- **Розмір:** 8815104 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
