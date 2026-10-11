# `iaLPSS2_UART2_1.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_UART2_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B041B9A5281F1841730F6AA5960F4C4EE3D7A4ACF807562D646EBF6F2838B81F` | `E99BE7D2A185A287302F0C65E2AC597B81669AA2` | `010A4E99410D8C557099A4568B79A4FB` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_UART2_1.sys`
- **Розмір:** 305760 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO UART Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
