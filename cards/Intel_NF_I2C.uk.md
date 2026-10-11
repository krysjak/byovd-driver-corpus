# `Intel_NF_I2C.sys`

[Назад до індексу](../README.uk.md) · [English version](Intel_NF_I2C.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4B8BB8A77A6007F3BB6B3A4EB406C5A01441F405CFF778C09743F9B2988D44BA` | `6E92E66415548B37D717082A45819056972DAB9C` | `40C4D03F576A656CA0CB125041BE12A6` |

## Метадані

- **Ім'я файлу:** `Intel_NF_I2C.sys`
- **Розмір:** 201440 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) NF I2C Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
