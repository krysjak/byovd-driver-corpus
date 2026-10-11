# `ISH_3.sys`

[Назад до індексу](../README.uk.md) · [English version](ISH_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `73C4ECB45F6D82BAF194CD0E0297CCC13D2CAF2238E1811716BC95BA684456EB` | `2C3937D04E7C6403E3FBA9E929A2D2D548D810E3` | `69EBCAD2DAB8626CE3F95775FD42350A` |

## Метадані

- **Ім'я файлу:** `ISH_3.sys`
- **Розмір:** 158096 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel
- **Продукт:** ISS
- **Опис:** Intel(R) Integrated Sensor Solution
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
