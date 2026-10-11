# `NETwtw08_3.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7BF12D35A02A4AF1C2245D629050F23EDFEE0F3E881779678C651A0E6414B280` | `9B07FE3B0F8AE20BA72DCD3ED7868813165C47A0` | `E2F2A9191248AC8AD6A1C813B596AF4C` |

## Метадані

- **Ім'я файлу:** `NETwtw08_3.sys`
- **Розмір:** 8917944 bytes
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
