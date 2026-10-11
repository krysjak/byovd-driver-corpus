# `NETwtw08_1.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4159F53FD4A5B6BBD7ACE0B395A532342DDBA49799B7DC78B6CAB589D620EED9` | `5CB0F4069C927CD9ACBF7C67840B47BCC169FE1D` | `3AD1073BFA135670EAC090C6E78A86CA` |

## Метадані

- **Ім'я файлу:** `NETwtw08_1.sys`
- **Розмір:** 8922528 bytes
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
