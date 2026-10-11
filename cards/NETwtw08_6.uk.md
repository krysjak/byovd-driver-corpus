# `NETwtw08_6.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `769528B40306D620C4FBF95EAEFF0E3C98194CE69FBEC9C21E1B46D122726ED7` | `6761E4016D42B9713D203D81ADC16BA9B3213CE5` | `3A4D9CCEC6317C5C233AD4C302552870` |

## Метадані

- **Ім'я файлу:** `NETwtw08_6.sys`
- **Розмір:** 8932936 bytes
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
