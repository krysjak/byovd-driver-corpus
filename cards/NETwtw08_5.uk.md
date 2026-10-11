# `NETwtw08_5.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B146813FBD6C76E93023DAF302080847C33AC6AB201C136C2625910FEEAE9413` | `83A290C1E1C21E21D224F1AF38AC458E98ABD40F` | `C4080E03ECF8444351E0B3F05392C96C` |

## Метадані

- **Ім'я файлу:** `NETwtw08_5.sys`
- **Розмір:** 8896568 bytes
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
