# `Intel_NF_I2C_1.sys`

[Назад до індексу](../README.uk.md) · [English version](Intel_NF_I2C_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D02992E67A5B531A4DE899B565283EA0C54160F9AA87110BC472A163E7F065B1` | `4CC4B7A4E6BED6EC229B1133E5423B559AFF2EE3` | `81458491262AC01ECE1D581D6A3087B9` |

## Метадані

- **Ім'я файлу:** `Intel_NF_I2C_1.sys`
- **Розмір:** 218040 bytes
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
