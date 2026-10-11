# `atihdwt6_4.sys`

[Назад до індексу](../README.uk.md) · [English version](atihdwt6_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5923CCFE8B6A0829AE8E371479B5A91765A363625E7CCEF3D4FF4961001E933C` | `A64CEEA257D68A8F80B636BA3C6ADEE476AD220E` | `B0179019DF0B09AAA15D90EF75F94D60` |

## Метадані

- **Ім'я файлу:** `atihdwt6_4.sys`
- **Розмір:** 247232 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD HD Audio Driver
- **Опис:** AMD High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
