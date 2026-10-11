# `swmbbser00_2.sys`

[Назад до індексу](../README.uk.md) · [English version](swmbbser00_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8318DE754E108B9AF04EBF135B3CE1599419C19F65613453195FC24E8627584D` | `544C37CA26CA6F194207967DC4D70B9883B21E44` | `1E3E7F7D8DE3653A354F0590D30CF30D` |

## Метадані

- **Ім'я файлу:** `swmbbser00_2.sys`
- **Розмір:** 288112 bytes
- **Архітектура:** 0x8664
- **Компанія:** Sierra Wireless Incorporated
- **Продукт:** Sierra Wireless Incorporated USB Modem/Serial Device Driver
- **Опис:** USB Modem/Serial Device Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 80

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
